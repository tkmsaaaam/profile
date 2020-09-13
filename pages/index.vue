<template>
  <div class="container">
    <div>
      <a class="title">
        Takamasa Matsui
      </a>
      <div class="description">
        <a>A Software Developper(Server Side)</a>
        <br />
        <a href="https://tkmsaaaam.github.io/profile/gh-pages/profile/">
          Profile
        </a>
        <a href="https://www.facebook.com/tkmsaaaam" target="_blank">Contact</a>
      </div>
      <div class="links">
        <a
          href="https://www.facebook.com/tkmsaaaam"
          target="_blank"
          rel="noopener noreferrer"
          class="button--facebook"
        >
          Facebook
        </a>
        <a
          href="https://github.com/tkmsaaaam/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--github"
        >
          GitHub
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'Home'
    }
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  display: block;
  font-weight: 300;
  font-size: 80px;
  color: #102961;
  letter-spacing: 1px;
}

.description {
  font-weight: 300;
  font-size: 24px;
  color: #102961;
  padding-top: 15px;
}

.links {
  padding-top: 15px;
}
</style>
