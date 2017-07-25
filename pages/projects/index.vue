<template>
  <section class="container">
    <div>
      <h1 class="title">
        Projects
      </h1>
      <div id="bio">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc lacinia, nisi semper iaculis lobortis, nisi nunc feugiat mauris, id consectetur neque dolor sed ipsum. Nunc tellus nibh, volutpat id ex vitae, eleifend scelerisque turpis. Vestibulum dictum scelerisque tellus, nec mollis augue fringilla nec. Maecenas ornare accumsan vehicula. Nulla et ullamcorper sem, a consequat magna. Pellentesque viverra elit ac justo convallis, non ultrices magna faucibus. Pellentesque vitae hendrerit mi. Aenean tempor leo vel pretium dictum. Fusce vitae sollicitudin lacus.
      </div>
      <card/>
    </div>
  </section>
</template>

<script>
import Card from '~components/Card.vue'

export default {
  components: {
    Card
  },
  layout: 'portfolio'
}
</script>

<style>
.container
{
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.title
{
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 5em;
  color: #35495e;
  letter-spacing: 1px;
}
.bio
{
  font-weight: 300;
  font-size: 1em;
}
</style>
