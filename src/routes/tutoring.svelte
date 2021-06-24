<script>
	import Footer from '../components/Footer.svelte';
</script>

<svelte:head>
	<title>Tutoring</title>
</svelte:head>

<div class="app">
	<div class="center">
		<h1>Tutoring</h1>
		<div class="descriptor_container">
			<div class="descriptor">
				<h2>Maths</h2>
				<ul>
					<li>Completed GCSE and A level maths</li>
					<li>I offer tutoring for GCSE level students</li>
				</ul>
			</div>
			<div class="descriptor">
				<h2>Computer Science</h2>
				<ul>
					<li>Complete GCSE and A level computer science.</li>
					<li>Currently studying Computer science at RHUL</li>
					<li>Happy to tutor GCSE and upwards</li>
					<li>Exerpienced in full stack javascript web development and python.</li>
				</ul>
			</div>
		</div>
	</div>
	<!-- <Footer /> -->
</div>

<style lang="scss">
	h1 {
		color: white;
		font-size: 75px;
		text-align: center;
	}
	.center {
		flex-direction: column;
	}
	.descriptor_container {
		display: flex;
		justify-content: space-around;
		flex-wrap: wrap;
		flex-direction: row;
		align-items: center;

		& > .descriptor {
			background-color: white;
			border-radius: 8px;
			padding: 8px;
			margin: 15px;
			box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px,
				rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
		}
	}
</style>
