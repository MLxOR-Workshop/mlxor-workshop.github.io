<script>
	import Block from '$lib/components/Block.svelte';
	import PaperIcon from 'virtual:icons/mingcute/pdf-line';
	import GithubIcon from 'virtual:icons/mdi/github';
	import ArxivIcon from 'virtual:icons/simple-icons/arxiv';
	import Person from '$lib/components/Person.svelte';
	import NavLink from '$lib/components/NavLink.svelte';
	import Call from '../content/call.md';
	import Intro from '../content/intro.md';
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
			<div class="text-md mt-8 text-gray-800">December 6 or 7, 2025</div>
			<div class="mt-2 text-sm text-gray-500">San Diego Convention Center</div>
			<div class="text-sm text-gray-500">San Diego, CA, USA</div>
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
				<NavLink href="#schedule">SCHEDULE</NavLink>
				<div class="mx-2 text-gray-400">/</div>
				<NavLink href="#speakers">SPEAKERS</NavLink>
				<div class="mx-2 text-gray-400">/</div>
				<NavLink href="#organizers">ORGANIZERS</NavLink>
				<div class="mx-2 text-gray-400">/</div>
				<NavLink href="#program_committee">PROGRAM COMMITTEE</NavLink>
				<div class="mx-2 text-gray-400">/</div>
				<NavLink href="#call">CALL FOR PAPERS</NavLink>
				<!-- <div class="mx-2 text-gray-400">/</div>
				<NavLink href="#papers">ACCEPTED PAPERS</NavLink> -->
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
		<h1 class="mb-6 text-2xl font-bold" id="schedule">Tentative Schedule</h1>
		<div class="mb-6 text-sm">
			<p><strong>Location:</strong> TBD</p>
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
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">8:30 - 8:50</td>
						<td class="w-full border border-gray-300 px-4 py-2">Morning Coffee</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">8:50 - 9:00</td>
						<td class="w-full border border-gray-300 px-4 py-2">Introduction and Opening Remark</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">9:00 - 9:30</td>
						<td class="w-full border border-gray-300 px-4 py-2">Invited Talk 1</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">9:30 - 10:00</td>
						<td class="w-full border border-gray-300 px-4 py-2">Invited Talk 2</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">10:00 - 10:25</td>
						<td class="w-full border border-gray-300 px-4 py-2">Coffee Break</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">10:25 - 11:10</td>
						<td class="w-full border border-gray-300 px-4 py-2"
							>Panel Discussion 1</td
						>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">11:10 - 12:00</td>
						<td class="w-full border border-gray-300 px-4 py-2"
							>Poster Session 1</td
						>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">12:00 - 13:00</td>
						<td class="w-full border border-gray-300 px-4 py-2"
							>Lunch Break</td
						>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">13:00 - 13:30</td>
						<td class="w-full border border-gray-300 px-4 py-2">Invited Talk 3</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">13:30 - 14:00</td>
						<td class="w-full border border-gray-300 px-4 py-2">Invited Talk 4</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">14:00 - 14:25</td>
						<td class="w-full border border-gray-300 px-4 py-2">Coffee Break</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">14:25 - 15:05</td>
						<td class="w-full border border-gray-300 px-4 py-2">Spotlight Presentations</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">15:05 - 15:55</td>
						<td class="w-full border border-gray-300 px-4 py-2">Poster Session 2</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">15:55 - 16:25</td>
						<td class="w-full border border-gray-300 px-4 py-2">Invited Talk 5</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">16:25 - 17:10</td>
						<td class="w-full border border-gray-300 px-4 py-2">Panel Discussion 2</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">17:10 - 17:15</td>
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
		<h1 class="mb-4 text-2xl font-bold" id="speakers">Confirmed Speakers & Panelists (So Far)</h1>
	</Block>
	<!-- <Block> -->
	<Block size="max-w-4xl">
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
					name="Phil Kaminsky"
					affiliation="Amazon"
					link="https://kaminsky.ieor.berkeley.edu/"
					image="./imgs/phil.jpg"
				></Person>
				<Person
					name="Eric Moulines"
					affiliation="Ecole Polytechnique"
					link="https://www.polytechnique.edu/en/directory/moulines-eric"
					image="https://simons.berkeley.edu/sites/default/files/styles/post_card_xxl_2x/public/eric-perou_1.jpg?h=6b865382&itok=MKFRFLQ4"
				></Person>
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
					affiliation="University of Tokyo"
					link="https://www.ms.k.u-tokyo.ac.jp/sugi/profile.html"
					image="./imgs/masashi.jpg"
				></Person>
				<Person
					name="Stefan Wager"
					affiliation="Stanford University"
					link="https://www.gsb.stanford.edu/faculty-research/faculty/stefan-wager"
					image="./imgs/stefan.jpg"
				></Person>
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
				<Person
					name="Lei Ying"
					affiliation="University of Michigan"
					link="https://leiying.engin.umich.edu/"
					image="./imgs/ying.jpg"
				></Person>
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
		<h1 class="mb-4 text-2xl font-bold" id="program_committee">Program Committee</h1>
		<!-- <div class="text-base"> -->
			Yeganeh Alimohammadi (Berkeley), Alessandro Arlotto (Duke), Baris Ata (Chicago), Santiago Balseiro (Columbia), Mohsen Bayati (Stanford), Sem Borst (Eindhoven Univ. of Technology), Anton Braverman (Northwestern), Ana Busic (École Normale Supérieure), Prakash Chakraborty (Penn State), Vasileios Charisopoulos (Chicago), Minshuo Chen (Northwestern), Xinyun Chen (CUHK Shenzhen), Yi Chen (HKUST), Zaiwei Chen (Purdue), Stephen Chick (INSEAD), Souvik Dhara (Georgia Tech), Ton Dieker (Columbia), Sebastian Engelke (Univ. of Geneva), Ethan Fang (Duke), Daniel Freund (MIT), Rui Gao (UT Austin), David Gamarnik (MIT), Julia Gaudio (Northwestern), Soumyadip Ghosh (IBM), Peter Glynn (Stanford), Varun Gupta (Univ. of Utah), Mert Gurbuzbalaban (Rutgers), Bernd Heidergott (Vrije Universiteit Amsterdam), Xuedong He (CUHK), Harsha Honnappa (Purdue), Yue Hu (Stanford), Sajad Khodadadian (Virginia Tech), Yanwei Jia (CUHK), Jiashuo Jiang (HKUST), Ramesh Johari (Stanford), Gauri Joshi (CMU), Andrew Li (CMU), Michael Lingzhi Li (Harvard), Shuangning Li (Chicago), Yueyang Liu (Rice), Yiping Lu (Northwestern), Thodoris Lykouris (MIT), Debankur Mukherjee (Georgia Tech), Karthyek Murthy (USC), Raghu Pasupathy (Purdue), Marek Petrik (Univ. of New Hampshire), Chara Podimata (MIT), Pengyu Qian (Boston Univ.), Chang-Han Rhee (Northwestern), Luc Rey-Bellet (UMass), Ilya Ryzhov (Maryland), Sujay Sanghavi (UT Austin), Ziv Scully (Cornell), Devavrah Shah (MIT), Sanjay Shakkottai (UT Austin), Nian Si (HKUST), Raghav Singal (Dartmouth), Fiona Sloothaak (Eindhoven Univ. of Technology), Emina Soljanin (Rutgers), Rayadurgam Srikant (UIUC), Mark Squillante (IBM), Vijay Subramanian (Michigan), Vasilis Syrgkanis (Stanford), Wenpin Tang (Columbia), Bruno Tuffin (INRIA), Stefan Wager (Stanford), Neil Walton (Durham), Kaizheng Wang (Columbia), Weina Wang (CMU), Zhaoran Wang (Northwestern), Ermin Wei (Northwestern), Renyuan Xu (NYU), Chen Yan (Michigan), Zixian Yang (Michigan),David Yao (Columbia),  Lei Ying (Michigan), Sophie Yu (UPenn), Zeyu Zheng (Berkeley), Xunyu Zhou (Columbia), Zhengyuan Zhou (NYU), Bert Zwart (CWI)
		<!-- </div> -->
	</Block>

	<!-- <Block padding="pb-4"> -->
	<Block padding="py-8">
		<h1 class="mb-4 text-2xl font-bold" id="call">Call For Papers</h1>
		<div class="text-base">
			<Call />
		</div>
	</Block>
	<!-- <Block>
		<h1 class="mb-4 text-2xl font-bold" id="papers">Accepted Papers</h1>
		<PaperList />
	</Block> -->

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
