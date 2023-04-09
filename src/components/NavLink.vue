<template>
  <a class="link" :href="to">{{ text }}</a>
</template>

<script>
export default {
  props: {
    to: String,
    text: String,
  },
  data() {
    return {};
  },
};
</script>

<style scoped>
.link {
  display: inline-block;
  vertical-align: top;
  margin: 0 10px;
  position: relative;
  color: #fff;
  text-decoration: none;

  transition: color 0.2s linear;
}
.link:after {
  content: "";
  display: block;
  width: 100%;
  height: 3px;
  display: none;

  background-color: #fce38a;
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1;
}

.link:hover {
  color: #fce38a;
}

.link:hover:after,
.link.active:after {
  display: block;
}

.link.active {
  color: #fce38a;
}
</style>
