<template>
  <div class="container">
    <div>
      <a class="title">
        Takamasa Matsui
      </a>
      <div class="description">
        <a>A Software Developper (Server)</a>
        <br />
        <a>CAMPFIRE Engineer</a>
        <br />
        <a>Saitama University Student (Economics)</a>
        <br />
        <a href="https://www.facebook.com/tkmsaaaam" target="_blank">Contact</a>
      </div>
      <div class="description">
        <h3>Experience</h3>
        <a>Ruby(Main Skill)</a>
        <br />
        <a>Vue.js</a>
        <br />
        <a>HTML/CSS</a>
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
        title: 'Profile'
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
