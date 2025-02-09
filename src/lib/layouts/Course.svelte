<script>
    export let course;
    export let number;
    export let catalog;
</script>
<style>
  .blog-post-container {
    max-width: 800px;
    margin: 3rem auto 0;
    padding: 20px;
    background-color: #f9f9f9;
    border-radius: 8px;
  }
  :global(.blog-post-container h1) {
    color: #2c3e50;
    font-size: 2.5rem;
    margin-bottom: 0.5rem;
  }
  :global(.blog-post-container h2) {
    color: #16a085;
    font-size: 2rem;
    margin-bottom: 1rem;
  }
  :global(.blog-post-container blockquote) {
    color: #7f8c8d;
    font-style: italic;
    border-left: 4px solid #16a085;
    line-height: 1.4;
    font-size: 1.2rem;
    padding-left: 1rem;
    margin: 1rem 0;
  }
</style>

<div class="blog-post-container">
    <h1>{course}</h1>
    <h2>{number}</h2>
    <blockquote>{catalog}</blockquote>
    <slot/>
</div>