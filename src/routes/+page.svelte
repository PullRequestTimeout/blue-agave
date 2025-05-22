<main>
	<div>
		<h1>Blue <img src="/logo.png" alt="Blue Agave Logo" />Agave</h1>
		<h2>Tequila Grill</h2>
	</div>
	<p>🚧 Under Contruction 🚧</p>
</main>
<svg width="0" height="0">
	<filter id="filter">
		<feTurbulence type="fractalNoise" baseFrequency="0.8" numOctaves="7" seed="200" result="turb" />
		<feColorMatrix type="saturate" values="0" />
		<feComposite in2="SourceGraphic" operator="in" />
		<feBlend in2="SourceGraphic" mode="multiply" />
	</filter>
</svg>

<style>
	* {
		margin: 0;
	}

	main {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100vh;
		background: url('/BackGround.jpg') no-repeat center center fixed;
		background-size: cover;
		color: #d82f28;
	}

	div {
		position: relative;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		scale: 0.4;
	}

	h1 {
		font-family: 'Las Flores', sans-serif;
		font-size: 8rem;
		filter: url(#filter);
		display: flex;
		justify-content: center;
		align-items: center;
	}

	h2 {
		position: absolute;
		top: 75%;
		right: 0;
		font-family: sans-serif;
		font-size: 1.8rem;
		font-weight: 100;
		text-transform: uppercase;
		letter-spacing: 0;
	}

	img {
		max-width: 10rem;
	}

	svg {
		position: absolute;
	}

	p {
		position: absolute;
		bottom: 2rem;
		left: 50%;
		transform: translateX(-50%);
		font-family: sans-serif;
		font-weight: 700;
		font-size: 1rem;
		width: 100%;
		text-align: center;
	}

	@media (min-width: 768px) {
		div {
			scale: 0.5;
		}
	}
	@media (min-width: 1024px) {
		div {
			scale: 0.7;
		}
	}

	@media (min-width: 1280px) {
		div {
			scale: 0.8;
		}
	}
</style>
