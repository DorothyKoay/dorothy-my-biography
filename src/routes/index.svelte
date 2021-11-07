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

<div>
	<Header title="My Biography" />
	<Section {...myInfo} />
	<Section {...myHobby} />
	<Section {...myPersonality} />
	<Footer gitHub="https://github.com/DorothyKoay/dorothy-my-biography" />
</div>
