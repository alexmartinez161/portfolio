<template>
  <section class="container">
    <div>
      <h1 class="title">
        Alex Martinez
      </h1>
      <div id="bio">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc lacinia, nisi semper iaculis lobortis, nisi nunc feugiat mauris, id consectetur neque dolor sed ipsum. Nunc tellus nibh, volutpat id ex vitae, eleifend scelerisque turpis. Vestibulum dictum scelerisque tellus, nec mollis augue fringilla nec. Maecenas ornare accumsan vehicula. Nulla et ullamcorper sem, a consequat magna. Pellentesque viverra elit ac justo convallis, non ultrices magna faucibus. Pellentesque vitae hendrerit mi. Aenean tempor leo vel pretium dictum. Fusce vitae sollicitudin lacus.
      </div>
    </div>
    <nuxt-link to="/projects"><h2>Projects</h2></nuxt-link>
    <div id="skills">
      <h2> Skills </h2>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit.
Phasellus nec nunc eu massa maximus ornare nec sed lacus.
Fusce luctus nibh laoreet, sollicitudin odio id, faucibus lectus.
Suspendisse sollicitudin nibh ut ante posuere, a laoreet augue lobortis.
Praesent eu erat facilisis, mollis metus blandit, iaculis dolor.
In iaculis odio a ligula aliquet facilisis.
Vivamus eleifend erat sed leo imperdiet, nec congue libero consectetur.
Nam non risus faucibus, dapibus sem ut, cursus nisl.
Maecenas rhoncus nulla eget feugiat iaculis.
Aenean a nibh egestas, mollis enim eu, consectetur nisi.
Nunc sed diam in ex convallis finibus quis quis nisl.
Pellentesque ut velit non velit commodo pulvinar sit amet vitae erat.
Etiam sit amet odio interdum, facilisis urna in, fringilla magna.
Quisque egestas est eget dictum convallis.
Cras faucibus nulla in metus volutpat varius.
Sed hendrerit velit quis ante vulputate sagittis.
Phasellus eleifend est eget augue vulputate, nec posuere ligula facilisis.
    </div>
  </section>
</template>

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
