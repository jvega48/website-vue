<template>
  <div class="hello">
   <section id="header">
				<header>
					<span class="image avatar"><img src="images/me.png" alt="" /></span>
					<h1 id="logo"><a href="#">Jose A. Vega</a></h1>
					<p>A passionate software engineer<br />
					and a space explorer.</p>
                    <ul class="icons">
                        <li><a href="https://twitter.com/jose_dev48" target="_blank" class="icon fa-twitter"><span class="label">Twitter</span></a></li>
                        <li><a href="https://www.linkedin.com/in/jose-vega-b3aa1b129/" target="_blank" class="icon fa-linkedin"><span class="label">Linkedin</span></a></li>
                        <li><a href="https://github.com/jvega48" target="_blank" class="icon fa-github"><span class="label">Github</span></a></li>
                        <li><a href="mailto: jvega48@calstatela.edu" class="icon fa-envelope"><span class="label">Email</span></a></li>
                    </ul>
				</header>
				<nav id="nav">
					<ul>
						<li><a href="#one" class="active">About</a></li>
						<li><a href="#two">Things I Can Do</a></li>
						<li><a href="#three">Experience & Projects</a></li>
						<li><a href="#four">Contact</a></li>
					</ul>
				</nav>
				<footer>
                    <h6>Thank you for stopping by don't forget to leave a message or follow me on one of my social media platforms.</h6>
				</footer>
			</section>
  </div>
</template>

<script>
export default {
  name: "Header"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
