<svelte:head>
	<title>Team 2554: About</title>
</svelte:head>

<div class="bg-space p-20 text-center flex justify-center align-middle">
	<h1 class="text-7xl uppercase text-green-400 font-semibold mt-8">About Us</h1>
</div>

<h2 class="uppercase text-center text-4xl font-medium text-amber-400 mt-10">Sub-Teams</h2>
<div class="border border-zinc-300 mt-6 max-w-4xl rounded mx-auto" />

<div class="max-w-5xl mx-auto pt-2">
	<div class="mt-6 flex flex-row">
		<img class="rounded" src="/mech_team.jpeg" alt="Mechanical Subteam" />
		<p class="ml-6 text-xl mt-5">
			The <span class="font-semibold">Mechanical Team</span> is in charge of creating a prototype and
			the physical construction of the robot. They train new members to safely use power tools and handle
			build equipment to create a practice field to use before competition. They also design components
			such as drive chains, the chassis, and shooters. Students in this sub-team build the skeletal structure
			of the robot, and efficiently arrange the motors, electronics, and various mechanisms onto the
			robot.
		</p>
	</div>
	<div class="mt-8 flex flex-row border-t-2 pt-8">
		<p class="mr-6 text-xl mt-14">
			The <span class="font-semibold">Electrical Team</span> organizes and puts together the electrical
			board. The electrical board essentially connects the power and the programming to the motors and
			other parts of the robot so that it may perform all the desired functions!
		</p>
		<img class="rounded" src="/elec_team.jpeg" alt="Electrical Subteam" />
	</div>
	<div class="mt-8 flex flex-row border-t-2 pt-8">
		<img class="rounded" src="/prog_team.jpeg" alt="Programming Subteam" />
		<p class="ml-6 text-xl mt-14">
			The <span class="font-semibold">Programming Team</span> creates and runs a program in Java that
			allows students to control the robot. Programming code directs the robot to carry out a specific
			job within the limits of its hardware but also has to take into account the limits of human ability
			in order to program AI for competitions. The code for the program is on GitHub. A button to the
			page will be provided below.
		</p>
	</div>
</div>

<style>
	.bg-space {
		width: 100%;
		height: 400px;
		background-image: url('/team.jpeg');
		background-repeat: no-repeat;
		background-position: 50% 60%;
		background-size: 100%;
	}
</style>
