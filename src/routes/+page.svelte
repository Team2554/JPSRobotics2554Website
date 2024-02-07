<script lang="ts">
	import PlatinumSponsor from "../components/PlatinumSponsor.svelte";

	let carouselImage = 1;
</script>

<svelte:head>
	<title>Team 2554: The WarHawks</title>
</svelte:head>

<div class="bg-space p-20 flex align-middle">
	<img src="/warhawks-logo-2-smol_orig.png" alt="Warhawks Logo" />
</div>
<div class="border border-zinc-300 mt-10 max-w-4xl rounded mx-auto" />

<!-- Use <PlatinumSponsor>s inside -->

<div class="p-5 w-80 absolute right-0 bg-slate-50">
	<h3 class="text-center font-bold">A SPECIAL THANKS TO OUR PLATINUM SPONSORS!</h3>
	<PlatinumSponsor sponsorWebsiteURL="https://olightworld.com/" sponsorImgURL="/olight.jpg" sponsorName="Olight"/>
</div>

<div class="max-w-5xl mx-auto mt-5 grid grid-cols-2 pt-2 space-x-6">
	<div>
		<div class="flex flex-row">
			<img src="/jps.jpeg" alt="John P. Stevens High School" />
			<h3 class="text-2xl mt-8 ml-1">JOHN P. STEVENS HIGH SCHOOL ROBOTICS TEAM</h3>
		</div>
		<div class="mt-5">
			<p>
				​​Team 2554, The Warhawks, is John P. Stevens High School’s FIRST Robotics team. All FIRST
				participants seek to inspire new generations to explore the wonders of science and
				technology. ​
			</p>
			<br />
			<p>
				Every year, high school students have 6 weeks to design and build a robot that can complete
				the challenge and compete with teams from across the nation. The 2022 theme is Rapid React.
				Through the guidance and leadership of our captains and mentors, students are able to
				acquire the knowledge necessary for and develop a powerful interest in STEM careers.
			</p>
			<br />
			<p>
				​Our team is divided into four separate sub-teams: Mechanical, Electrical, Programming, and
				<s>Marketing</s> Operations. Although each individual group specializes in their field, all of the sub-teams
				come together to create a well-functioning robot for the competition.
			</p>
		</div>
	</div>
	<div>
		<div class="flex flex-row">
			<img src="/hoodie.jpeg" alt="Team 2554 Apparel" />
			<h3 class="text-2xl mt-8 ml-3">INTERESTED IN OUR TEAM'S APPAREL AND PRODUCTS?</h3>
		</div>
		<p class="text-center mt-8">
			Click the button below to view and buy our apparel from our team store. Our products range
			from mugs to sweatshirts!
		</p>
		<div class="text-center pt-8">
			<a
				class="bg-gray-400 px-4 py-3 rounded text-white"
				href="https://team-2554-store.creator-spring.com/"
				target="_blank"
				rel="noopener noreferrer">TEAM 2554 Apparel Store</a
			>
		</div>
		<div class="mt-12 flex flex-col">
			<img src={`/c${carouselImage}.jpeg`} class="mx-auto" width="350" alt="Apparel Carousel" />
			<div class="mt-3 grid grid-cols-2 space-x-2">
				<button
					on:click={() => {
						if (carouselImage > 1) carouselImage--;
					}}><span class="material-symbols-outlined"> arrow_back </span></button
				>
				<button
					on:click={() => {
						if (carouselImage < 3) carouselImage++;
					}}><span class="material-symbols-outlined"> arrow_forward </span></button
				>
			</div>
		</div>
	</div>
</div>

<style>
	.bg-space {
		width: 100%;
		height: 400px;
		background-image: url('/space.png');
	}
</style>
