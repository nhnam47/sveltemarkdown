<script>
// @ts-nocheck

  export let data;
</script>

<h1>Blog</h1>

<p>My blog posts will go here eventually…</p>

<h1>Blog</h1>

<ul>
  {#each data.posts as post}
    <li>
      <h2>
        <a href={post.path}>
          {post.meta.title}
        </a>
      </h2>
      Published {post.meta.date}
    </li>
  {/each}
</ul>
