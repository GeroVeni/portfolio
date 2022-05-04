<main class="bg-black text-white">
	<section title="Hero" class="min-h-screen flex items-center justify-center">
		<button
			class="power-button bg-white w-32 aspect-square rounded-full flex items-center justify-center"
		>
			<span class="text-black material-symbols-rounded align-middle text-8xl">
				power_settings_new
			</span>
		</button>
	</section>
</main>

<style>
	.power-button {
		background: white;
		box-shadow: 0 0 0 0 rgba(255, 255, 255, 1);
		animation: pulse-white 2s infinite;
	}

	@keyframes pulse-white {
		0% {
			transform: scale(0.95);
			box-shadow: 0 0 0 0 rgba(255, 255, 255, 0.2);
		}

		70% {
			transform: scale(1);
			box-shadow: 0 0 0 60rem rgba(255, 255, 255, 0);
		}

		100% {
			transform: scale(0.95);
			box-shadow: 0 0 0 0 rgba(255, 255, 255, 0);
		}
	}
</style>
