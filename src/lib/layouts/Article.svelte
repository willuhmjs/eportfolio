<script>
  export let title;
  export let date;
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
    margin-bottom: 10px;
  }
  :global(p) {
    line-height: 2;
  }
  .published-date {
    color: #7f8c8d;
    font-size: 1.2rem;
    margin-bottom: 1rem;
    font-style: italic;
  }
</style>

<div class="blog-post-container">
  <h1>{title}</h1>
  <p class="published-date">
    {new Date(date).toLocaleDateString('en-US', {
      year: 'numeric',
      month: 'long',
      day: '2-digit'
    })}
  </p>
  <slot/>
</div>
