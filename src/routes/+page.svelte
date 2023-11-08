<script>
</script>

<svelte:head>
	<title>April's Homepage</title>
	<meta name="description" content="Aprils Homepage" />
</svelte:head>

<section>
	<span class="main" />

	<div class="card">
		<div id="console" />
	</div>
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	.card {
		width: 100%;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
		background: lightgray;
		padding: 15px 25px 15px 25px;
		box-shadow: 7px 7px rgba(152, 232, 252, 0.5);
		border: 2px solid #4cb6eb;
	}

	#console {
		font-family: courier, monospace;
		color: #000;
		width: 750px;
		margin-left: auto;
		margin-right: auto;
		margin-top: 30px;
		font-size: 14px;
	}

	a {
		color: #0bc;
		text-decoration: none;
	}

	#a {
		color: #0f0;
	}

	#c {
		color: #0bc;
	}

	#b {
		color: #ff0096;
	}

	#k {
		animation: change 1s;
	}

	#op {
		color: #888888;
	}

	@keyframes change {
		0% {
			color: #0f0;
		}
		50% {
			color: #0f0;
		}
		99% {
			color: black;
		}
	}
</style>
