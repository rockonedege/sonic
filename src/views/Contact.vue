<template>
    <section class="hero is-dark">

    <div class="hero-body"><div class="container"> 
      <nav class="level">  
          <div class="level-item is-size-3" v-for='c in contacts' :key='c'>
            <div v-html="c"></div>
          </div>
      </nav>
    </div></div> 

    </section> 
</template>

<script>
export default {
  data() {
    return {
      contacts: [
        '<i class="fab fa-weixin"></i> 13524826926',
        '<i class="far fa-envelope"></i> <a href="mailto:tom.tan@live.com">tom.tan@live.com</a>',
        // '<i class="fas fa-mobile-alt"></i> +86 135-248-26926'
      ]
    };
  },
  methods: {
    // join(items) {
    //   return items ? items.join(" &middot; ") : "";
    // }
  }
};
</script>

