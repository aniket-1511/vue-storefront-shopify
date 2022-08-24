<template>
	<div id="about-us">
	  <h1 class="about-us-title">About Us</h1>
	    <MyCustomComponent />
    </div>
</template>

<script type="module">
import MyCustomComponent from '~/components/MyCustomComponent.vue';

export default {
  name: 'AboutUs',
  components: {
    MyCustomComponent 
  }
};
</script>

<style lang="postcss" scoped>
.about-us-title {
  text-align: center;
  color: #5ece7b;
}
</style>