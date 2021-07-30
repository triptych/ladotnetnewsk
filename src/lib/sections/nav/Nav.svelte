<script>

    function handleClick(){
        document.querySelector(".navbar-burger").classList.toggle("is-active");
        document.querySelector(".navbar-menu").classList.toggle("is-active");

    }

    function closeMenu(){
        document.querySelector(".navbar-menu").classList.remove("is-active");
        document.querySelector(".navbar-burger").classList.toggle("is-active");

    }

</script>
<nav class="navbar is-info navbar-default" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
        <!-- <a class="navbar-item" href="https://bulma.io">
          <img src="https://bulma.io/images/bulma-logo.png" alt="Bulma: Free, open source, and modern CSS framework based on Flexbox" width="112" height="28">
        </a> -->
    
        <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false" on:click={handleClick}>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div>

	<div id="navbarBasicExample" class="navbar-menu" on:click={closeMenu}>
		<div class="navbar-start">
			<a class="navbar-item" href="."> Home </a>

			<a class="navbar-item" href="books"> Books </a>
			<a class="navbar-item" href="about"> About </a>
			<a class="navbar-item" href="contact"> Contact </a>
      <a class="navbar-item" href="newsletter"> Newsletter </a>

			<!--
        <div class="navbar-item has-dropdown is-hoverable">
          <a class="navbar-link">
            More
          </a>
  
          <div class="navbar-dropdown">
            <a class="navbar-item">
              About
            </a>
            <a class="navbar-item">
              Jobs
            </a>
            <a class="navbar-item">
              Contact
            </a>
            <hr class="navbar-divider">
            <a class="navbar-item">
              Report an issue
            </a>
          </div>
        </div> -->
		</div>
        <div class="navbar-end"></div>
		<!-- <div class="navbar-end">
			<div class="navbar-item">
				<div class="buttons">
					<a class="button is-primary">
						<strong>Sign up</strong>
					</a>
					<a class="button is-light"> Log in </a>
				</div>
			</div>
		</div> -->
	</div>
</nav>
