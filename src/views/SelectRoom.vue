<template>
  <div>
    <section class="hero is-fullheight">
      <div class="hero-body">
        <div class="container">
          <div class="card">
            <header class="card-header">
              <h1 class="card-header-title"></h1>
            </header>
            <div class="card-content">
              <div class="content columns">
                <div class="column">
                  <img src="/img/standard.jpg" />
                </div>

                <div class="column buttons has-text-justified">
                  <h2>选择墙体面</h2>
                  <div>
                    <a @click="prev" class="button is-link">前墙</a>
                  </div>
                  <div>
                    <a @click="prev" class="button is-link">主席台</a>
                  </div>
                  <div>
                    <a @click="prev" class="button is-link">台唇</a>
                  </div>
                  <div>
                    <a @click="prev" class="button is-link">听众席</a>
                  </div>
                  <div>
                    <a @click="prev" class="button is-link">后墙</a>
                  </div>
                  <div>
                    <a @click="prev" class="button is-link">顶棚</a>
                  </div>
                  <div>
                    <a @click="prev" class="button is-link">左侧墙</a>
                  </div>
                  <div>
                    <a @click="prev" class="button is-link">右侧墙</a>
                  </div>
                </div>
              </div>
            </div>
            <footer class="card-footer">
              <div class="field is-grouped right-aligned">
                <p class="control">
                  <a class="is-pulled-right  button is-link" @click="prev">上一步</a>
                </p>
                <p class="control">
                  <a class="button" @click="next">下一步</a>
                </p>
                <p class="control">
                  <a class="button is-danger" @click="exit">退出</a>
                </p>
              </div>
            </footer>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  mounted() {},
  data() {
    return {};
  },
  methods: {
    prev(e) {alert(e.target.innerText)},
    next(e) {alert(e.target.innerText)},
    exit(e) {alert(e.target.innerText)}
  },
  components: {
    // md
  }
};
</script>
<style scoped>
.chart div {
  font: 10px sans-serif;
  background-color: steelblue;
  text-align: right;
  padding: 3px;
  margin: 1px;
  color: white;
}
</style>
