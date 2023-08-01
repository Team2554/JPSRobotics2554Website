<script>
	import SponsorProfile from "../../components/SponsorProfile.svelte";
	import SponsorWebsiteWrapper from "../../components/SponsorWebsiteWrapper.svelte";

</script>
<svelte:head>
	<title>Team 2554: Sponsors</title>
</svelte:head>

<h2 class="uppercase text-center text-4xl font-medium text-green-600 mt-8">
How to Become a Sponsor
</h2>

<div class="border border-zinc-300 mt-4 max-w-4xl rounded mx-auto" />

<p class="text-center mt-6 text-2xl font-medium">
	Click <a
		class="italic text-red-700"
		target="_blank"
		rel="noopener noreferrer"
		href="/2023-2024 Sponsor Packet.pdf">here</a
	>
	to view the <a href="/2023-2024 Sponsor Packet.pdf" target="_blank" class="text-red-700 italic">2023 - 2024 Team 2554 Sponsorship Packet</a>
</p>

<!-- <div class="border border-zinc-300 mt-10 max-w-3xl rounded mx-auto" /> -->

<h2 class="uppercase text-center text-4xl font-medium text-green-600 mt-8">
	2023-2024 Sponsors Pending!
</h2>

<!-- <p class="text-center mt-6 text-2xl font-medium">
	We would like to thank our current sponsors for their support!
</p> -->

<div class="border border-zinc-300 mt-6 max-w-4xl rounded mx-auto" />

<SponsorWebsiteWrapper sponsorWebsiteURL="https://olightworld.com/">
	<SponsorProfile sponsorImgURL="/olight.jpg" sponsorName="Olight" sponsorBlurb="OLIGHT is a leading provider of portable lighting solutions, dedicated to its mission of &quot;illuminating the world&quot;. Our diverse range of products serves various scenarios, including household, outdoor, and other applications. Our products are sold and utilized across Europe, the Americas, and other regions worldwide."/>
</SponsorWebsiteWrapper>

<SponsorWebsiteWrapper sponsorWebsiteURL="https://www.optimum.com/">
	<SponsorProfile sponsorImgURL="/Optimum-Logo.png" sponsorName="Optimum" sponsorBlurb="Optimum provides cost-effective and reliable internet and television services throughout the United States." />
</SponsorWebsiteWrapper>

<SponsorWebsiteWrapper sponsorWebsiteURL="https://www.firstinspires.org/">
	<SponsorProfile sponsorImgURL="/first-logo.png" sponsorName="FIRST" sponsorBlurb="FIRST inspires young people to be science and technology leaders and innovators by engaging them in exciting mentor-based programs that build science, engineering, and technology skills, that inspire innovation, and that foster well-rounded life capabilities including self-confidence, communication, and leadership." sponsorImgWidth="40%"/>
</SponsorWebsiteWrapper>
