<svelte:head>
	<title>Team 2554: Info</title>
</svelte:head>

<h2 class="uppercase text-center text-4xl font-medium text-zinc-900 mt-8">Information & Updates</h2>

<div class="border border-zinc-300 mt-4 max-w-4xl rounded mx-auto" />

<div class="max-w-4xl mx-auto mt-14">
	<div class="grid grid-cols-2">
		<div class="flex flex-col">
			<p class="text-center text-lg font-medium">
				To find more information about the FIRST Robotics Competition (FRC) click the link below.
			</p>
			<a
				class="btn"
				target="_blank"
				rel="noopener noreferrer"
				href="https://www.firstinspires.org/robotics/frc">FIRST Robotics</a
			>
			<img src="/first-logo.png" class="mx-auto mt-8" width="60%" alt="FIRST Logo" />
		</div>
		<div class="flex flex-col">
			<p class="text-center text-lg font-medium">
				To see our past performance and keep up to date, ​check out our Blue Alliance page.
			</p>
			<a
				class="btn"
				target="_blank"
				rel="noopener noreferrer"
				href="https://www.thebluealliance.com/team/2554">Blue Alliance Page</a
			>
			<img src="/tba.png" class="mx-auto mt-8" width="45%" alt="The Blue Alliance Logo" />
		</div>
	</div>
	<div class="grid grid-cols-1 mt-20">
		<div class="flex flex-col">
			<p class="text-center text-lg font-medium">
				To see information on how our subteams work, check out our documentation.
			</p>
			<a
				class="btn"
				target="_blank"
				rel="noopener noreferrer"
				href="https://docs.jpsrobotics2554.org/">Documentation</a
			>
			<img src="/documentation.jpeg" class="mx-auto mt-8" width="20%" alt="Documentation" />
		</div>
	</div>
</div>

<style lang="postcss">
	.btn {
		@apply uppercase border-2 px-4 py-3 border-blue-500 w-52 text-center mt-7 mx-auto text-blue-500 hover:text-white hover:bg-blue-500 duration-300 rounded;
	}
</style>
