<template>
  <Layout>
    <div class="container">
      <Hero />
      <div class="proj-title" id="about">
        <span class="label">projects</span>
      </div>
      <ProjectsGrid :projects="$page.projects.edges" />
      <JobsInfo></JobsInfo>
    </div>
    <LatestJournals :journals="$page.journals.edges" />
  </Layout>
</template>

<page-query>
query Posts {
	projects: allProjectPost {
    edges {
      node {
        id
        date (format: "YYYY")
        title
        categories
        thumbnail (quality: 90)
        path
      }
    }
  },
  journals: allJournalPost (perPage: 4) {
    edges {
      node {
        id
        path
        title
      }
    }
  }
}
</page-query>

<script>
import Hero from "@/components/Hero"
import ProjectsGrid from "@/components/ProjectsGrid"
// import LatestJournals from "@/components/LatestJournals"
// import JobsInfo from "@/components/JobsInfo"

export default {
  components: {
    Hero,
    ProjectsGrid,
    // LatestJournals,
    // JobsInfo
  }
}
</script>
<style scoped>
.proj-title {
    font-size: 3rem;
    font-weight: 700;
    padding: 0rem 0rem .5rem;
    margin: 0;
    color: var(--color-base-1);
    letter-spacing: -0.01em;
    text-align: left;
}
</style>