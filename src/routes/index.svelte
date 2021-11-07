<script>
	import Header from '$lib/Header.svelte';
	import Section from '$lib/Section.svelte';
	import Footer from '$lib/Footer.svelte';
	let myInfo = {
		title: 'Info',
		item1: 'Koay Yi Wen Dorothy',
		item2: 12,
		item3: 'SJK(C) Perempuan China'
	};
	let myHobby = {
		title: 'Hobby',
		item1: 'Playing Piano',
		item2: 'Cooking',
		item3: 'Play badminton'
	};
	let myPersonality = {
		title: 'Personality',
		item1: 'Quiet',
		item2: 'Humble',
		item3: 'Kind'
	};
</script>

<Header title="My Biography" />
<div class="container-fluid">
	<div class="card1 text-center">
		<div class="row g-3">
			<div class="col-lg-4">
				<Section {...myInfo} />
			</div>
			<div class="col-lg-4">
				<Section {...myHobby} />
			</div>
			<div class="col-lg-4">
				<Section {...myPersonality} />
			</div>
		</div>
	</div>
</div>
<Footer></Footer>