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

			<!-- <div class="mt-8 flex flex-wrap items-center gap-2 text-sm">
				<div class="font-mono text-sm text-gray-500 mr-2">
					Supported by
				</div>
				<a href="https://connect.informs.org/aps/home"
					target="_blank" rel="noreferrer"
					class="hover:underline">
					INFORMS Applied Probability Society
				</a>
				<span>/</span>
				<a href="https://connect.informs.org/simulation/home"
					target="_blank" rel="noreferrer"
					class="hover:underline">
					INFORMS Simulation Society
				</a>				
				<span>/</span>
				<a href="https://galux.co.kr/"
					target="_blank" rel="noreferrer"
					class="hover:underline">
					Galux
				</a>
				<span>/</span>
				<a href="https://www.columbia.edu/"
					target="_blank" rel="noreferrer"
					class="hover:underline">
					Columbia University
				</a>

			</div> -->
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
				<NavLink href="#call">CfP</NavLink>
				<div class="mx-2 text-gray-400">/</div>
				<NavLink href="#papers">Accepted Papers</NavLink>
				<div class="mx-2 text-gray-400">/</div>
				<NavLink href="#sponsors">Sponsors</NavLink>
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
          <td class="w-full border border-gray-300 px-4 py-2">
            <strong>Keynote Talk:</strong>
            <a
              href="https://neurips.cc/virtual/2025/loc/san-diego/136366"
              target="_blank"
              rel="noopener noreferrer"
              class="underline hover:bg-blue-50 rounded-sm px-0.5"
            >
              Can Large Language Models Make Decisions? Mathematical Formulations and Open Problems
            </a>
            <br />Speaker: R. Srikant (UIUC)
          </td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">9:00 - 9:30</td>
          <td class="w-full border border-gray-300 px-4 py-2">
            <strong>Spotlight Presentations</strong>
            <br />1.
            <a
              href="https://openreview.net/forum?id=IC0Qo09FxF"
              target="_blank"
              rel="noopener noreferrer"
              class="underline hover:bg-blue-50 rounded-sm px-0.5"
            >
              The Oversight Game: Learning AI Control &amp; Corrigibility in Markov Games
            </a>,
            <br />&nbsp;&nbsp;&nbsp; William Overman, Mohsen Bayati
            <br />2.
            <a
              href="https://openreview.net/forum?id=FLD5JWpR67"
              target="_blank"
              rel="noopener noreferrer"
              class="underline hover:bg-blue-50 rounded-sm px-0.5"
            >
              Neural Decision Rule for Constrained Contextual Stochastic Optimization
            </a>,
            <br />&nbsp;&nbsp;&nbsp; Zhangyi Liu, Zhongling Xu, Feng Liu, Rui Gao, Shuang Li
            <br />3.
            <a
              href="https://openreview.net/forum?id=ToUWDGP0st"
              target="_blank"
              rel="noopener noreferrer"
              class="underline hover:bg-blue-50 rounded-sm px-0.5"
            >
              Accelerating Diffusion via Compressed Sensing: Applications to Imaging and Finance
            </a>,
            <br />&nbsp;&nbsp;&nbsp; Zhengyi Guo, Jiatu Li, Wenpin Tang, David Yao
          </td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">9:30 - 09:45</td>
          <td class="w-full border border-gray-300 px-4 py-2">Coffee Break (and Poster Setup)</td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">09:45 - 10:30</td>
          <td class="w-full border border-gray-300 px-4 py-2">
            <strong>Poster Session 1</strong> (Paper ID: 1-71)
          </td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">10:30 - 11:15</td>
          <td class="w-full border border-gray-300 px-4 py-2">
            <strong>MLxOR Theory-Geared Panel:</strong> Peter Glynn (Stanford), Daniel Russo (Columbia), Masashi Sugiyama (U.of Tokyo, RIKEN), Renyuan Xu (NYU)
            <br />Moderator: Assaf Zeevi (Columbia)
          </td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">11:15 - 12:25</td>
          <td class="w-full border border-gray-300 px-4 py-2">
            <strong>Spotlight Presentations</strong>
            <br />4.
            <a
              href="https://openreview.net/forum?id=xufNFlDoKj"
              target="_blank"
              rel="noopener noreferrer"
              class="underline hover:bg-blue-50 rounded-sm px-0.5"
            >
              Achieving O(1/N) Optimality Gap in Weakly-Coupled Markov Decision Processes through Gaussian Approximation
            </a>,
            <br />&nbsp;&nbsp;&nbsp; Chen Yan, Weina Wang, Lei Ying
            <br />5.
            <a
              href="https://openreview.net/forum?id=v7YPtir432"
              target="_blank"
              rel="noopener noreferrer"
              class="underline hover:bg-blue-50 rounded-sm px-0.5"
            >
              Fairness Is More Than Algorithms: Racial Disparities in Time-to-Recidivism
            </a>,
            <br />&nbsp;&nbsp;&nbsp; Jessy Xinyi Han, Kristjan Greenewald, Devavrat Shah
            <br />6.
            <a
              href="https://openreview.net/forum?id=zxaMZHF1JW"
              target="_blank"
              rel="noopener noreferrer"
              class="underline hover:bg-blue-50 rounded-sm px-0.5"
            >
              Human-Centric Perishable Inventory Management with AI-Assistance
            </a>,
            <br />&nbsp;&nbsp;&nbsp; Yu Nu, Meng Qi, Karan Girotra, Elena Belavina
            <br />7.
            <a
              href="https://openreview.net/forum?id=XMZgZfBTwv"
              target="_blank"
              rel="noopener noreferrer"
              class="underline hover:bg-blue-50 rounded-sm px-0.5"
            >
              Ensuring Fairness in Priority-Based Admissions with Uncertain Scores
            </a>,
            <br />&nbsp;&nbsp;&nbsp; Zhiqiang Zhang, Pengyi Shi, Amy R. Ward
            <br />8.
            <a
              href="https://openreview.net/forum?id=HUkPaXsB3s"
              target="_blank"
              rel="noopener noreferrer"
              class="underline hover:bg-blue-50 rounded-sm px-0.5"
            >
              Scalable First-order Method for Certifying Optimal k-Sparse GLMs
            </a>,
            <br />&nbsp;&nbsp;&nbsp; Jiachang Liu, Soroosh Shafiee, Andrea Lodi
            <br />9.
            <a
              href="https://openreview.net/forum?id=CTGNVLAqgQ"
              target="_blank"
              rel="noopener noreferrer"
              class="underline hover:bg-blue-50 rounded-sm px-0.5"
            >
              Model-Free Assessment of Simulator Fidelity via Quantile Curves
            </a>,
            <br />&nbsp;&nbsp;&nbsp; Yu-Shiou Willy Lin, Garud Iyengar, Kaizheng Wang
            <br />10.
            <a
              href="https://openreview.net/forum?id=tQgfqyT6If"
              target="_blank"
              rel="noopener noreferrer"
              class="underline hover:bg-blue-50 rounded-sm px-0.5"
            >
              Autoregressive Learning under Joint KL Analysis: Horizon-Free Approximation and Computational-Statistical Tradeoffs
            </a>,
            <br />&nbsp;&nbsp;&nbsp; Yunbei Xu, Yuzhe Yuan, Ruohan Zhan
          </td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">12:25 - 12:55</td>
          <td class="w-full border border-gray-300 px-4 py-2">
            <strong>Keynote Talk:</strong>
            <a
              href="https://neurips.cc/virtual/2025/loc/san-diego/136382"
              target="_blank"
              rel="noopener noreferrer"
              class="underline hover:bg-blue-50 rounded-sm px-0.5"
            >
              The AI-XR Scientist that Sees and Works with Humans
            </a>
            <br />Speaker: Mengdi Wang (Princeton)
          </td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">12:55 - 13:25</td>
          <td class="w-full border border-gray-300 px-4 py-2">Lunch Break (and Poster Setup)</td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">13:25 - 14:10</td>
          <td class="w-full border border-gray-300 px-4 py-2">
            <strong>Poster Session 2</strong> (Paper ID: 72-161)
          </td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">14:10 - 14:40</td>
          <td class="w-full border border-gray-300 px-4 py-2">
            <strong>Keynote Talk:</strong>
            <a
              href="https://neurips.cc/virtual/2025/loc/san-diego/136385"
              target="_blank"
              rel="noopener noreferrer"
              class="underline hover:bg-blue-50 rounded-sm px-0.5"
            >
              Learning What to Optimize: ML Methods for Accessible Operations Research
            </a>
            <br />Speaker: Peter Frazier (Cornell)
          </td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">14:40 - 15:10</td>
          <td class="w-full border border-gray-300 px-4 py-2">
            <strong>Keynote Talk:</strong>
            <a
              href="https://neurips.cc/virtual/2025/loc/san-diego/136386"
              target="_blank"
              rel="noopener noreferrer"
              class="underline hover:bg-blue-50 rounded-sm px-0.5"
            >
              OR and ML in Amazon’s Middle Mile Freight Capacity Marketplace
            </a>
            <br />Speaker: Phil Kaminsky (Amazon)
          </td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">15:10 - 15:25</td>
          <td class="w-full border border-gray-300 px-4 py-2">Coffee Break (and Poster Setup)</td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">15:25 - 16:10</td>
          <td class="w-full border border-gray-300 px-4 py-2">
            <strong>Poster Session 3</strong> (Paper ID: 162-245)
          </td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">16:10 - 16:55</td>
          <td class="w-full border border-gray-300 px-4 py-2">
            <strong>ML×OR Industry-Geared Panel:</strong> Hongseok Namkoong (Columbia), Sanjay Shakkottai (UT Austin), Dawn Woodard (LinkedIn), Kuang Xu (Stanford)
            <br />Moderator: Jose Blanchet (Stanford)
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


<!-- <Block>
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
          <td class="w-full border border-gray-300 px-4 py-2">
            <strong>Keynote Talk:</strong>
            <a
              href="https://neurips.cc/virtual/2025/loc/san-diego/136366"
              target="_blank"
              rel="noopener noreferrer"
              class="hover:underline"
            >
              Can Large Language Models Make Decisions? Mathematical Formulations and Open Problems
            </a>
            <br />Speaker: R. Srikant (UIUC)
          </td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">9:00 - 9:30</td>
          <td class="w-full border border-gray-300 px-4 py-2">
            <strong>Spotlight Presentations</strong>
            <br />1.
            <a
              href="https://openreview.net/forum?id=IC0Qo09FxF"
              target="_blank"
              rel="noopener noreferrer"
              class="hover:underline"
            >
              The Oversight Game: Learning AI Control &amp; Corrigibility in Markov Games
            </a>,
            <br />&nbsp;&nbsp;&nbsp; William Overman, Mohsen Bayati
            <br />2.
            <a
              href="https://openreview.net/forum?id=FLD5JWpR67"
              target="_blank"
              rel="noopener noreferrer"
              class="hover:underline"
            >
              Neural Decision Rule for Constrained Contextual Stochastic Optimization
            </a>,
            <br />&nbsp;&nbsp;&nbsp; Zhangyi Liu, Zhongling Xu, Feng Liu, Rui Gao, Shuang Li
            <br />3.
            <a
              href="https://openreview.net/forum?id=ToUWDGP0st"
              target="_blank"
              rel="noopener noreferrer"
              class="hover:underline"
            >
              Accelerating Diffusion via Compressed Sensing: Applications to Imaging and Finance
            </a>,
            Zhengyi Guo, Jiatu Li, Wenpin Tang, David Yao
          </td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">9:30 - 09:45</td>
          <td class="w-full border border-gray-300 px-4 py-2">Coffee Break (and Poster Setup)</td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">09:45 - 10:30</td>
          <td class="w-full border border-gray-300 px-4 py-2">
            <strong>Poster Session 1</strong> (Paper ID: 1-71)
          </td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">10:30 - 11:15</td>
          <td class="w-full border border-gray-300 px-4 py-2">
            <strong>MLxOR Theory-Geared Panel:</strong> Peter Glynn (Stanford), Daniel Russo (Columbia), Masashi Sugiyama (U.of Tokyo, RIKEN), Renyuan Xu (NYU)
            <br />Moderator: Assaf Zeevi (Columbia)
          </td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">11:15 - 12:25</td>
          <td class="w-full border border-gray-300 px-4 py-2">
            <strong>Spotlight Presentations</strong>
            <br />4.
            <a
              href="https://openreview.net/forum?id=xufNFlDoKj"
              target="_blank"
              rel="noopener noreferrer"
              class="hover:underline"
            >
              Achieving O(1/N) Optimality Gap in Weakly-Coupled Markov Decision Processes through Gaussian Approximation
            </a>,
            <br />&nbsp;&nbsp&nbsp; Chen Yan, Weina Wang, Lei Ying
            <br />5.
            <a
              href="https://openreview.net/forum?id=v7YPtir432"
              target="_blank"
              rel="noopener noreferrer"
              class="hover:underline"
            >
              Fairness Is More Than Algorithms: Racial Disparities in Time-to-Recidivism
            </a>,
            <br />&nbsp;&nbsp;&nbsp; Jessy Xinyi Han, Kristjan Greenewald, Devavrat Shah
            <br />6.
            <a
              href="https://openreview.net/forum?id=zxaMZHF1JW"
              target="_blank"
              rel="noopener noreferrer"
              class="hover:underline"
            >
              Human-Centric Perishable Inventory Management with AI-Assistance
            </a>,
            <br />&nbsp;&nbsp;&nbsp; Yu Nu, Meng Qi, Karan Girotra, Elena Belavina
            <br />7.
            <a
              href="https://openreview.net/forum?id=XMZgZfBTwv"
              target="_blank"
              rel="noopener noreferrer"
              class="hover:underline"
            >
              Ensuring Fairness in Priority-Based Admissions with Uncertain Scores
            </a>,
            <br />&nbsp;&nbsp;&nbsp; Zhiqiang Zhang, Pengyi Shi, Amy R. Ward
            <br />8.
            <a
              href="https://openreview.net/forum?id=HUkPaXsB3s"
              target="_blank"
              rel="noopener noreferrer"
              class="hover:underline"
            >
              Scalable First-order Method for Certifying Optimal k-Sparse GLMs
            </a>,
            <br />&nbsp;&nbsp;&nbsp; Jiachang Liu, Soroosh Shafiee, Andrea Lodi
            <br />9.
            <a
              href="https://openreview.net/forum?id=CTGNVLAqgQ"
              target="_blank"
              rel="noopener noreferrer"
              class="hover:underline"
            >
              Model-Free Assessment of Simulator Fidelity via Quantile Curves
            </a>,
            <br />&nbsp;&nbsp;&nbsp; Yu-Shiou Willy Lin, Garud Iyengar, Kaizheng Wang
            <br />10.
            <a
              href="https://openreview.net/forum?id=tQgfqyT6If"
              target="_blank"
              rel="noopener noreferrer"
              class="hover:underline"
            >
              Autoregressive Learning under Joint KL Analysis: Horizon-Free Approximation and Computational-Statistical Tradeoffs
            </a>,
            <br />&nbsp;&nbsp;&nbsp; Yunbei Xu, Yuzhe Yuan, Ruohan Zhan
          </td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">12:25 - 12:55</td>
          <td class="w-full border border-gray-300 px-4 py-2">
            <strong>Keynote Talk:</strong>
            <a
              href="https://neurips.cc/virtual/2025/loc/san-diego/136382"
              target="_blank"
              rel="noopener noreferrer"
              class="hover:underline"
            >
              The AI-XR Scientist that Sees and Works with Humans
            </a>
            <br />Speaker: Mengdi Wang (Princeton)
          </td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">12:55 - 13:25</td>
          <td class="w-full border border-gray-300 px-4 py-2">Lunch Break (and Poster Setup)</td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">13:25 - 14:10</td>
          <td class="w-full border border-gray-300 px-4 py-2">
            <strong>Poster Session 2</strong> (Paper ID: 72-161)
          </td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">14:10 - 14:40</td>
          <td class="w-full border border-gray-300 px-4 py-2">
            <strong>Keynote Talk:</strong>
            <a
              href="https://neurips.cc/virtual/2025/loc/san-diego/136385"
              target="_blank"
              rel="noopener noreferrer"
              class="hover:underline"
            >
              Learning What to Optimize: ML Methods for Accessible Operations Research
            </a>
            <br />Speaker: Peter Frazier (Cornell)
          </td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">14:40 - 15:10</td>
          <td class="w-full border border-gray-300 px-4 py-2">
            <strong>Keynote Talk:</strong>
            <a
              href="https://neurips.cc/virtual/2025/loc/san-diego/136386"
              target="_blank"
              rel="noopener noreferrer"
              class="hover:underline"
            >
              OR and ML in Amazon’s Middle Mile Freight Capacity Marketplace
            </a>
            <br />Speaker: Phil Kaminsky (Amazon)
          </td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">15:10 - 15:25</td>
          <td class="w-full border border-gray-300 px-4 py-2">Coffee Break (and Poster Setup)</td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">15:25 - 16:10</td>
          <td class="w-full border border-gray-300 px-4 py-2">
            <strong>Poster Session 3</strong> (Paper ID: 162-245)
          </td>
        </tr>

        <tr class="odd:bg-white even:bg-gray-50">
          <td class="border border-gray-300 px-4 py-2 whitespace-nowrap">16:10 - 16:55</td>
          <td class="w-full border border-gray-300 px-4 py-2">
            <strong>ML×OR Industry-Geared Panel:</strong> Hongseok Namkoong (Columbia), Sanjay Shakkottai (UT Austin), Dawn Woodard (LinkedIn), Kuang Xu (Stanford)
            <br />Moderator: Jose Blanchet (Stanford)
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
</Block> -->

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

	<Block padding="py-8">
	<h1 class="mb-4 text-2xl font-bold" id="sponsors">Sponsors</h1>
	<div class="text-base">
		We are grateful for the sponsorships from
		<a
		href="https://connect.informs.org/aps/home"
		target="_blank"
		rel="noreferrer"
		class="underline hover:bg-blue-50 rounded-sm px-0.5"
		>
		INFORMS Applied Probability Society
		</a>,
		<a
		href="https://connect.informs.org/simulation/home"
		target="_blank"
		rel="noreferrer"
		class="underline hover:bg-blue-50 rounded-sm px-0.5"
		>
		INFORMS Simulation Society
		</a>,
		<a
		href="https://galux.co.kr/"
		target="_blank"
		rel="noreferrer"
		class="underline hover:bg-blue-50 rounded-sm px-0.5"
		>
		Galux
		</a>,
		and
		<a
		href="https://www.columbia.edu/"
		target="_blank"
		rel="noreferrer"
		class="underline hover:bg-blue-50 rounded-sm px-0.5"
		>
		Columbia University
		</a>.
	</div>

 <!-- Logo grid -->
  <div class="mt-6 grid grid-cols-2 gap-6 items-center justify-items-center">
    <a
      href="https://connect.informs.org/aps/home"
      target="_blank"
      rel="noreferrer"
      class="inline-block"
    >
      <img
        src="./imgs/INFORMS_APS.png"
        alt="INFORMS Applied Probability Society"
        class="h-16 object-contain"
      />
    </a>

    <a
      href="https://connect.informs.org/simulation/home"
      target="_blank"
      rel="noreferrer"
      class="inline-block"
    >
      <img
        src="./imgs/IINFORMS_Simulation.png"
        alt="INFORMS Simulation Society"
        class="h-16 object-contain"
      />
    </a>

    <a
      href="https://galux.co.kr/"
      target="_blank"
      rel="noreferrer"
      class="inline-block"
    >
      <img
        src="./imgs/Galux.jpg"
        alt="Galux"
        class="h-16 object-contain"
      />
    </a>

    <a
      href="https://www.columbia.edu/"
      target="_blank"
      rel="noreferrer"
      class="inline-block"
    >
      <img
        src="./imgs/Columbia.png"
        alt="Columbia University"
        class="h-16 object-contain"
      />
    </a>
  </div>

	<!-- <div class="mt-6 grid grid-cols-2 gap-6 items-center justify-items-center">
    <img
      src="./imgs/INFORMS_APS.png"
      alt="INFORMS Applied Probability Society"
      class="h-16 object-contain"
    />
    <img
      src="./imgs/IINFORMS_Simulation.png"
      alt="INFORMS Simulation Society"
      class="h-16 object-contain"
    />
    <img
      src="./imgs/Galux-long.jpg"
      alt="Galux"
      class="h-16 object-contain"
    />
    <img
      src="./imgs/Columbia.png"
      alt="Columbia University"
      class="h-16 object-contain"
    />
  </div> -->
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
