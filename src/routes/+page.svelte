<script>
	import Block from '$lib/components/Block.svelte';
	import PaperIcon from 'virtual:icons/mingcute/pdf-line';
	import GithubIcon from 'virtual:icons/mdi/github';
	import ArxivIcon from 'virtual:icons/simple-icons/arxiv';
	import Person from '$lib/components/Person.svelte';
	import NavLink from '$lib/components/NavLink.svelte';
	import Call from '../content/call.md';
	import Intro from '../content/intro.md';
	import PCmembers from '../content/pc-members.md';
	import PaperList from '$lib/components/PaperList.svelte';
</script>

<svelte:head>
	<title>NeurIPS 2025 ML×OR Workshop: Mathematical Foundations and
Operational Integration of Machine Learning for
Uncertainty-Aware Decision-Making</title>
</svelte:head>

<div class="text-lg">
	<div class="flex w-full items-end justify-center font-serif">
		<div class="mx-8 w-full max-w-2xl pt-8 pb-8 text-black md:pt-28">
			<div class="mb-4 text-sm">
				<div class="inline-block rounded-md border border-black px-2 py-1 font-mono">
					NeurIPS 2025 WORKSHOP
				</div>
			</div>
			<div class="inline-block text-4xl"><strong>ML×OR Workshop:</strong><br>Mathematical Foundations and Operational Integration of Machine Learning for Uncertainty-Aware Decision-Making</div>
			<div class="mt-8 flex items-center space-x-2">
				<div class="font-mono text-sm text-gray-500">Supported by</div>
				<a href="https://connect.informs.org/aps/home" target="_blank" rel="noreferrer">
					INFORMS Applied Probability Society
				</a>
			</div>
			<div class="text-md mt-8 text-gray-800">December 6, 2025</div>
			<div class="mt-2 text-sm text-gray-500">Upper Level Room 26AB</div>
			<div class="text-sm text-gray-500">San Diego Convention Center</div>
		</div>
	</div>
	<!-- <div class="w-full border-b border-gray-500"></div> -->
	<div
		class="sticky top-0 z-10 my-2 flex w-full items-start justify-center bg-gray-100/70 backdrop-blur-md md:py-1.5"
	>
		<div class="mx-8 w-full max-w-2xl select-none">
			<div
				class="my-2 flex flex-row flex-wrap items-center justify-start font-mono text-sm md:text-base"
			>
				<NavLink href="#schedule">Schedule</NavLink>
				<div class="mx-2 text-gray-400">/</div>
				<NavLink href="#speakers">Speakers</NavLink>
				<div class="mx-2 text-gray-400">/</div>
				<NavLink href="#organizers">Organizers & PC Members</NavLink>
				<div class="mx-2 text-gray-400">/</div>
				<!-- <NavLink href="#program_committee">PC Members</NavLink>
				<div class="mx-2 text-gray-400">/</div> -->
				<NavLink href="#call">Call for Papers</NavLink>
				<div class="mx-2 text-gray-400">/</div>
				<NavLink href="#papers">Accepted Papers</NavLink>
			</div>
		</div>
	</div>
	<!-- <div class="flex w-full items-end justify-center font-serif">
		<div class="mx-8 w-full max-w-2xl text-black">
			<div class="mt-8 mb-8 flex text-sm md:text-base"></div>
		</div>
	</div> -->
	<Block padding="py-8" class="md:text-justify">
		<Intro />
	</Block>
	<Block>
		<h1 class="mb-6 text-2xl font-bold" id="schedule">Schedule</h1>
		<div class="mb-6 text-sm">
			<p><strong>Location:</strong> Upper Level Room 26AB, San Diego Convention Center</p>
		</div>
		<div>
			<table class="w-full border-collapse border border-gray-300 text-sm">
				<thead>
					<tr class="bg-gray-100">
						<th class="border border-gray-300 px-4 py-2 text-left whitespace-nowrap">Time</th>
						<th class="w-full border border-gray-300 px-4 py-2 text-left">Event</th>
					</tr>
				</thead>
				<tbody>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">8:00 - 8:20</td>
						<td class="w-full border border-gray-300 px-4 py-2">Morning Coffee</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">8:20 - 8:30</td>
						<td class="w-full border border-gray-300 px-4 py-2">Introduction and Opening Remark</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">8:30 - 9:00</td>
						<!-- <td class="w-full border border-gray-300 px-4 py-2">Invited Talk: R. Srikant</td> -->
						 <td class="w-full border border-gray-300 px-4 py-2">Invited Talk: Can Large Language Models Make Decisions? Mathematical Formulations and Open Problems
							<br/>Speaker: R. Srikant (UIUC)</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">9:00 - 9:30</td>
						<td class="w-full border border-gray-300 px-4 py-2">Spotlight Presentations
							<br/>1. Ask or Play: Scalable Oversight through Markov Potential Games
							<br/>2. Neural Decision Rule for Constrained Contextual Stochastic Optimization
							<br/>3. Accelerating Diffusion via Compressed Sensing: Applications to Imaging and Finance
						</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">9:30 - 09:45</td>
						<td class="w-full border border-gray-300 px-4 py-2">Coffee Break (and Poster Setup)</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">09:45 - 10:30</td>
						<td class="w-full border border-gray-300 px-4 py-2">Poster Session 1</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">10:30 - 11:15</td>
						<td class="w-full border border-gray-300 px-4 py-2">MLxOR Theory-Geared Panel: Peter Glynn (Stanford), Daniel Russo (Columbia), Masashi Sugiyama (U.of Tokyo, RIKEN), Renyuan Xu (NYU)
							<br/>Moderator: Assaf Zeevi (Columbia)
						</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">11:15 - 12:25</td>
						<td class="w-full border border-gray-300 px-4 py-2">Spotlight Presentations
							<br/>1. Achieving O(1/N) Optimality Gap in Weakly-Coupled Markov Decision Processes through Gaussian Approximation
							<br/>2. Fairness Is More Than Algorithms: Racial Disparities in Time-to-Recidivism
							<br/>3. Human-Centric Perishable Inventory Management with AI-Assistance
							<br/>4. Ensuring Fairness in Priority-Based Admissions with Uncertain Scores
							<br/>5. Scalable First-order Method for Certifying Optimal k-Sparse GLMs
							<br/>6. Model-Free Assessment of Simulator Fidelity via Quantile Curves
							<br/>7. Autoregressive Learning under Joint KL Analysis: Horizon-Free Approximation and Computational-Statistical Tradeoffs
						</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">12:25 - 12:55</td>
						<td class="w-full border border-gray-300 px-4 py-2">Invited Talk: The AI-XR Scientist that Sees and Works with Humans
							<br/>Speaker: Mengdi Wang (Princeton)</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">12:55 - 13:25</td>
						<td class="w-full border border-gray-300 px-4 py-2">Lunch Break (and Poster Setup)</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">13:25 - 14:10</td>
						<td class="w-full border border-gray-300 px-4 py-2">Poster Session 2</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">14:10 - 14:40</td>
						<td class="w-full border border-gray-300 px-4 py-2">Invited Talk: Learning What to Optimize: ML Methods for Accessible Operations Research
							<br/>Speaker: Peter Frazier (Cornell)</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">14:40 - 15:10</td>
						<td class="w-full border border-gray-300 px-4 py-2">Invited Talk: OR and ML in Amazon’s Middle Mile Freight Capacity Marketplace
							<br/>Speaker: Phil Kaminsky (Amazon)</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">15:10 - 15:25</td>
						<td class="w-full border border-gray-300 px-4 py-2">Coffee Break (and Poster Setup)</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">15:25 - 16:10</td>
						<td class="w-full border border-gray-300 px-4 py-2">Poster Session 3</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">16:10 - 16:55</td>
						<td class="w-full border border-gray-300 px-4 py-2">ML×OR Industry-Geared Panel: Hongseok Namkoong (Columbia), Sanjay Shakkottai (UT Austin), Dawn Woodard (LinkedIn), Kuang Xu (Stanford)
						<br/>Moderator: Jose Blanchet (Stanford)
						</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">16:55 - 17:00</td>
						<td class="w-full border border-gray-300 px-4 py-2">Closing Remark</td>
					</tr>
				</tbody>
			</table>
		</div>
		<div class="mt-4 text-sm text-gray-600 italic">
			<p>All times are in Pacific Time (PT).</p>
		</div>
	</Block>
	<Block padding="pb-4">
		<h1 class="mb-4 text-2xl font-bold" id="speakers">Speakers & Panelists</h1>
	</Block>
	<Block>
	<!-- <Block size="max-w-4xl"> -->
		<div class="flex flex-col items-center justify-center">
			<div class="flex flex-wrap justify-center">
				<Person
					name="Peter Frazier"
					affiliation="Cornell University"
					link="https://people.orie.cornell.edu/pfrazier/"
					image="./imgs/pfrazier.jpg"
				></Person>
				<Person
					name="Peter Glynn"
					affiliation="Stanford University"
					link="https://web.stanford.edu/~glynn/"
					image="./imgs/pglynn.jpg"
				></Person>
				<Person
					name="Hongseok Namkoong"
					affiliation="Columbia Universisty"
					link="https://hsnamkoong.github.io/"
					image="./imgs/hong.jpg"
				></Person>
				<Person
					name="Phil Kaminsky"
					affiliation="Amazon"
					link="https://kaminsky.ieor.berkeley.edu/"
					image="./imgs/phil.jpg"
				></Person>
				<!-- <Person
					name="Eric Moulines"
					affiliation="Ecole Polytechnique"
					link="https://www.polytechnique.edu/en/directory/moulines-eric"
					image="https://simons.berkeley.edu/sites/default/files/styles/post_card_xxl_2x/public/eric-perou_1.jpg?h=6b865382&itok=MKFRFLQ4"
				></Person> -->
				<Person
					name="Daniel Russo"
					affiliation="Columbia Universisty"
					link="https://djrusso.github.io/"
					image="./imgs/drusso.jpg"
				></Person>
				<Person
					name="Sanjay Shakkottai"
					affiliation="UT Austin"
					link="https://sites.google.com/view/sanjay-shakkottai/"
					image="./imgs/sanjay.jpg"
				></Person>
				<Person
					name="Rayadurgam Srikant"
					affiliation="UIUC"
					link="https://sites.google.com/a/illinois.edu/srikant/"
					image="./imgs/rsrikant.jpg"
				></Person>
				<Person
					name="Masashi Sugiyama"
					affiliation="University of Tokyo, RIKEN"
					link="https://www.ms.k.u-tokyo.ac.jp/sugi/profile.html"
					image="./imgs/masashi.jpg"
				></Person>
				<!-- <Person
					name="Stefan Wager"
					affiliation="Stanford University"
					link="https://www.gsb.stanford.edu/faculty-research/faculty/stefan-wager"
					image="./imgs/stefan.jpg"
				></Person> -->
				<Person
					name="Mengdi Wang"
					affiliation="Princeton University"
					link="https://mwang.princeton.edu/"
					image="./imgs/mengdi.jpg"
				></Person>
				<Person
					name="Dawn Woodard"
					affiliation="LinkedIn"
					link="https://woodardscience.com/"
					image="./imgs/dawn.jpg"
				></Person>
				<Person
					name="Kuang Xu"
					affiliation="Stanford University"
					link="https://gsb-faculty.stanford.edu/kuang-xu/"
					image="./imgs/kuang.jpg"
				></Person>
				<Person
					name="Renyuan Xu"
					affiliation="New York University"
					link="https://renyuanxu.github.io/"
					image="./imgs/renyuan.jpg"
				></Person>
<!-- 				<Person
					name="Lei Ying"
					affiliation="University of Michigan"
					link="https://leiying.engin.umich.edu/"
					image="./imgs/ying.jpg"
				></Person> -->
			</div>
		</div>
	</Block>
	<Block padding="pb-4">
		<h1 class="mb-4 text-2xl font-bold" id="organizers">Organizers</h1>
	</Block>
	<Block>
	<!-- <Block size="max-w-4xl"> -->
		<div class="flex flex-col items-center justify-center">
			<div class="flex flex-wrap justify-center">
				<Person
					name="Jose Blanchet"
					affiliation="Stanford University"
					link="https://joseblanchet.com/"
					image="https://joseblanchet.com/wp-content/uploads/2024/06/blanchet-800x800.jpg"
				></Person>
				<Person
					name="Jing Dong"
					affiliation="Columbia University"
					link="https://www.columbia.edu/~jd2736/"
					image="https://www.columbia.edu/~jd2736/index_files/image004.jpg"
				></Person>
				<Person
					name="Henry Lam"
					affiliation="Columbia University"
					link="https://www.columbia.edu/~khl2114/"
					image="http://www.columbia.edu/~khl2114/files/pic_updated.jpg"
				></Person>
				<Person
					name="Min-hwan Oh"
					affiliation="Seoul National University"
					link="https://minoh.io/"
					image="https://minoh.io/assets/img/mho.webp"
				></Person>
				<Person
					name="Qiaomin Xie"
					affiliation="University of Wisconsin-Madison"
					link="https://qiaominxie.github.io/"
					image="https://qiaominxie.github.io/assets/img/prof_pic.jpg"
				></Person>
				<Person
					name="Yao Xie"
					affiliation="Georgia Institute of Technology"
					link="https://www2.isye.gatech.edu/~yxie77/"
					image="./imgs/yao.jpg"
				></Person>
				<Person
					name="Assaf Zeevi"
					affiliation="Columbia University"
					link="https://business.columbia.edu/faculty/people/assaf-zeevi"
					image="https://business.columbia.edu/sites/default/files-efs/styles/default_content_image_cinema/public/person/photos/assaf-pic-19.jpg?h=6ef299b7&itok=09SgCMLG"
				></Person>
				<Person
					name="Enlu Zhou"
					affiliation="Georgia Institute of Technology"
					link="https://www.enluzhou.gatech.edu/"
					image="https://enluzhou.gatech.edu/images/Enlu2017.jpg"
				></Person>
			</div>
		</div>
	</Block>

	<Block padding="pb-4">
		<h1 class="mb-4 text-2xl font-bold" id="program_committee">Program Committee Members</h1>
		<div class="text-base">
			<PCmembers />
		</div>
	</Block>

	<!-- <Block padding="pb-4"> -->
	<Block padding="py-8">
		<h1 class="mb-4 text-2xl font-bold" id="call">Call For Papers</h1>
		<div class="text-base">
			<Call />
		</div>
	</Block>
	<Block>
		<h1 class="mb-4 text-2xl font-bold" id="papers">Accepted Papers</h1>
		<PaperList />
	</Block>

	<div class="mt-8 flex w-full justify-center bg-gray-100 pt-4 font-sans">
		<div class="mx-8 w-full max-w-3xl">
			<div class="flex w-full flex-col items-center justify-start">
				<div class="mt-4 mb-8 text-2xl text-gray-500">
					<a
						href="https://github.com/pr4al-workshop/pr4al-workshop.github.io"
						target="_blank"
						rel="noreferrer"
						class="mr-2"
					>
						<GithubIcon class="inline-block hover:text-black" />
					</a>
				</div>
			</div>
			<div class="mb-24 text-sm text-gray-600">
				This website is licensed under a <a
					class="underline"
					href="http://creativecommons.org/licenses/by-sa/4.0/"
					target="_blank"
					rel="noreferrer">Creative Commons Attribution-ShareAlike 4.0 International License</a
				>
				and is based on the
				<a class="underline" href="https://leela-interp.github.io/" target="_blank" rel="noreferrer"
					>Leela Interp</a
				> project. That means you're free to borrow the source code of this website with attribution.
			</div>
		</div>
	</div>
</div>
