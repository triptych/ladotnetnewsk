<script>
	//import "../../../global.scss";
</script>

<div class="la-social">
	<ul style="display:flex">
		<li>
			<a href="https://www.facebook.com/LisaAnneIlluminated/">
				<span class="icon has-text-info">
					<i class="fab fa-facebook-square" />
				</span></a
			>
		</li>
		<li>
			<a href="mailto:lisaannebooks@gmail.com">
				<span class="icon has-text-info">
					<i class="fas fa-envelope-square" />
				</span></a
			>
		</li>
		<li>
			<a href="https://www.instagram.com/lisaannebooks/">
				<span class="icon has-text-info">
					<i class="fab fa-instagram-square" />
				</span>
			</a>
		</li>
		<li>
			<a href="https://twitter.com/LisaAnneBooks1">
				<span class="icon has-text-info">
					<i class="fab fa-twitter-square" />
				</span>
			</a>
		</li>
		<li>
			<a href="https://www.pinterest.com/1lisaanne">
				<span class="icon has-text-info">
					<i class="fab fa-pinterest-square" />
				</span>
			</a>
		</li>
		<li>
			<a href="https://www.amazon.com/Lisa-Anne-Wooldridge/e/B08BF3NWNG">
				<span class="icon has-text-info">
					<i class="fab fa-amazon" />
				</span>
			</a>
		</li>
	</ul>
</div>

<style lang="scss">
	.la-social {
		position: absolute;
		right: 8px;
		li {
			cursor: pointer;
			margin: 8px;
		}
	}
	@media only screen and (max-width: 600px) {

		.la-social{
			display: none;
		}
	}
</style>
