<template>
  <div class="single-post-page">
    <section class="post">
      <h1>Title of the post</h1>
      <h1>ここにタイトルが表示される。</h1>
      <div class="post-details">
        <div>Last updated on XXX</div>
        <div>written on NAME</div>
      </div>
      <p>Content of the post</p>
    </section>
    <section class="post-feedback">
      <p>let me know what you think about the post, send a mail to <a href="mailto:aaaa.com">feedback@my-domain.com</a> </p>
    </section>
  </div>
</template>

<style scoped>
.single-post-page{
  margin: 0 auto;
  max-width: 1200px;
  text-align: center;
}
.post-details{
  font-size: 30px;
  color: green;
}
</style>