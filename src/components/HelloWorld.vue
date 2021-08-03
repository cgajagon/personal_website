<template>
  <div class="main">
    <section class="intro">
      <h1 class="text">Carlos Gajardo Gonzalez</h1>
      <h3>&#8220;No music. No rituals. At home I write in my office or on the laptop in the kitchen where our puppy likes to sleep, and I love his company. But I've trained myself to be able to work anywhere, and I write on trains, planes, in automobiles (if I'm not the driver), airports, hotel rooms. I travel often. If I couldn't write wherever I was I would get little done. I also can write in short bursts. Fifteen minutes are enough to move a story forward. — Gail Carson Levine&#8221;</h3>
    </section>
    <section class="iconTable">
      <ul>
        <li>
          <a href="mailto:cgajagon@gmail.com" target="_blank" class="icon-link">
            <img src="../assets/email_100.png" class="icon"/>
          </a>
        </li>
        <li>
          <a href="https://github.com/cgajagon" target="_blank" class="icon-link">
            <img src="../assets/github_100.png" class="icon"/>
          </a>
        </li>
        <li>
          <a href="linkedin.com/in/carlos-gajardo-gonzález-product-development-it" target="_blank" class="icon-link">
            <img src="../assets/linkedin_100.png" class="icon"/>
          </a>
        </li>
        <li>
          <a href="https://www.thingiverse.com/cgajagon/designs" target="_blank" class="icon-link">
            <img src="../assets/thingiverse_100.png" class="icon"/>
          </a>
        </li>
      </ul>
    </section>
  </div>

</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.main {
  display: flex;
  align-items: center;
  justify-content: center;
}


.intro {
  position: absolute;
  top: 15%;
  width: 60%;
  color: lightgray;
}

h1 {
  font-size: 30pt;
  color: lightgray;
}

h3 {
  color: lightgray;
}

.iconTable {
  position: absolute;
  top: 81%;}

.iconTable ul {
  list-style: none;
  margin: 20px auto;
  padding:0;
}

.iconTable li {
  display: inline-block;
  margin: 0px 30px;
}

.icon-link:hover {
  opacity: 0.5;
}

.icon {
  filter: invert(0.4) sepia(1) saturate(500) hue-rotate(199deg) brightness(0.72);
  width: 100%;
  height: auto;
}

</style>
