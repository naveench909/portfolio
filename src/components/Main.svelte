<script>
  import Step from "./Step.svelte";

  let steps = [
    {
      name: "Cloudberry",
      icon: "fa-solid fa-suitcase-medical",
      href: "https://www.getcloudberry.com",
      decription: "health care app for patients and doctors",
    },
    {
      name: "Netflix clone",
      icon: "fa-solid fa-clapperboard",
      href: "https://netflix-clone9t7.netlify.app/",
      decription: "netflix clone using react and firebase",
    },
    {
      name: "Quiz App",
      icon: "fa-solid fa-clipboard-question",
      href: "https://angry-shirley-0a75db.netlify.app/",
      description: "basic quiz app using react",
    },
  ];

  let benefits = [
    {
      metric: "10x",
      name: "a self taught developer",
      description:
        "I taught myself to code using free online resources and absolutely fell in love with the creativity and problem solving that is involved in developing and engineering innovative new online experiences. Starting of with JavaScript, HTML & CSS and evolving my knowledge base to include JavaScript frameworks, backend programming, design, cloud services and much much more.",
    },
    {
      name: "a product design & UX finatic",
      description:
        "Carefully crafting and designing amazing user experiences allows me to express and experiment with every morsel of creativity I have. I love the challenge of learning new design concepts and enabling users with amazing online experiences.",
    },
    {
      name: "an excellent communicator",
      description:
        "Communication is key and it's a paramount value of mine. I believe in transparency and constructive communication above all else. This helps me develop deep relationships and ensures my effectiveness and productivity in any work space with any team.",
    },
  ];
</script>

<main class="flex flex-col flex-1 p-4">
  <section
    id="introPage"
    class="grid grid-cols-1 lg:grid-cols-2 gap-10 py-8 sm:py-14"
  >
    <div
      class="flex flex-col lg:justify-center text-center lg:text-left gap-6 md:gap-8 lg:gap-10"
    >
      <h2 class="font-semibold text-4xl sm:text-5xl md:text-6xl">
        Hi! I'm <span class="poppins text-violet-400">Naveen</span> Kumar
        <br />Front End
        <span class="poppins text-violet-400">Developer</span>
      </h2>
      <p class="text-base sm:text-lg md:text-xl">
        My <span class="text-violet-400"> favorite tech</span> includes JavaScript
        (NEXT.JS or SvelteKit), TailwindCSS, Node.js + Express.js & MongoDB or Firebase/Firestore!
      </p>
      <a
        href="files/2years.pdf"
        download
        class="blueShadow mx-auto lg:mr-auto lg:ml-0 text-base sm:text-lg md:text-xl poppins relative overflow-hidden px-6 py-3 group rounded-full bg-white text-slate-950"
      >
        <div
          class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200"
        />
        <h4 class="relative z-9">
          Download Resume
          <i class="fa-solid fa-download ml-2" />
        </h4>
      </a>
    </div>
    <svg
      id="sw-js-blob-svg"
      viewBox="0 0 100 100"
      xmlns="http://www.w3.org/2000/svg"
    >
      <defs>
        <linearGradient id="sw-gradient" x1="0" x2="1" y1="1" y2="0">
          <stop id="stop1" stop-color="rgba(0, 0, 0, 1)" offset="0%" />
          <stop
            id="stop2"
            stop-color="rgba(91.897, 91.897, 91.897, 1)"
            offset="100%"
          />
        </linearGradient>
      </defs>
      <mask id="mask1" mask-type="alpha">
        <path
          fill="url(#sw-gradient)"
          d="M19.1,-33C24.9,-29.6,30.1,-25,33.4,-19.3C36.6,-13.5,38.1,-6.8,38.5,0.2C38.9,7.2,38.2,14.5,35.5,21.2C32.9,28,28.2,34.4,21.9,39C15.7,43.7,7.8,46.8,0.1,46.6C-7.7,46.5,-15.3,43.2,-21.9,38.7C-28.5,34.1,-33.9,28.4,-38.4,21.8C-42.8,15.1,-46.3,7.6,-46.5,-0.1C-46.6,-7.7,-43.4,-15.5,-38.4,-21.2C-33.4,-26.9,-26.6,-30.6,-19.9,-33.5C-13.2,-36.4,-6.6,-38.5,0,-38.5C6.6,-38.5,13.2,-36.4,19.1,-33Z"
          width="100%"
          height="100%"
          transform="translate(50 50)"
          stroke-width="0"
          style="transition: all 0.3s ease 0s;"
          stroke="url(#sw-gradient)"
        />
      </mask>
      <g mask="url(#mask1)">
        <path
          fill="url(#sw-gradient)"
          d="M19.1,-33C24.9,-29.6,30.1,-25,33.4,-19.3C36.6,-13.5,38.1,-6.8,38.5,0.2C38.9,7.2,38.2,14.5,35.5,21.2C32.9,28,28.2,34.4,21.9,39C15.7,43.7,7.8,46.8,0.1,46.6C-7.7,46.5,-15.3,43.2,-21.9,38.7C-28.5,34.1,-33.9,28.4,-38.4,21.8C-42.8,15.1,-46.3,7.6,-46.5,-0.1C-46.6,-7.7,-43.4,-15.5,-38.4,-21.2C-33.4,-26.9,-26.6,-30.6,-19.9,-33.5C-13.2,-36.4,-6.6,-38.5,0,-38.5C6.6,-38.5,13.2,-36.4,19.1,-33Z"
          width="100%"
          height="100%"
          transform="translate(50 50)"
          stroke-width="0"
          style="transition: all 0.3s ease 0s;"
          stroke="url(#sw-gradient)"
        />
        <image
          href="images/profile.jpg"
          x="0"
          y="-100"
          height="320"
          width="100"
        />
      </g>
    </svg>
  </section>
  <section class="py-20 lg:py-32 flex flex-col gap-24" id="projects">
    <div class="flex flex-col gap-2 text-center">
      <h6 class="text-large sm:text-xl md:text-2xl">
        A few of my creative endeavors.
      </h6>
      <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
        Curious to <span class="poppins text-violet-400">see</span> my work?
      </h3>
    </div>
    <!-- <a
      href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"
      target="_blank"
      class="mx-auto px-4 py-2 rounded-md border border-solid border-white flex items-center gap-2 -mb-4 sm:-mb-0 -mt-10 hover:border-violet-700 duration-200"
    >
      <i class="fa-regular fa-circle-play" />
      <p>Watch the video</p>
    </a> -->
    <div class="grid grid-cols-1 lg:grid-cols-3 gap-12 lg:gap-10">
      <Step step={steps[0]}>
        <p>
          It's a platform that serves as a nexus for healthcare teams, fostering
          seamless collaboration, task prioritization, and effective
          communication. It's created with <strong class="text-violet-400"
            >React.js and GraphQL</strong
          >
        </p>
      </Step>
      <Step step={steps[1]}>
        <p>
          This is a netflix clone which shows the latest shows and movies on
          netflix. It's built with <strong class="text-violet-400"
            >React.js</strong
          > and some other react librarys .
        </p>
      </Step>
      <Step step={steps[2]}>
        <p>
          This is a quiz app game where a user can test his general knowledge in
          fun way. It's built with
          <strong class="text-violet-400">React and Typescript</strong> and for
          getting the question I've used
          <strong class="text-violet-400">Open Trivia DB</strong>.
        </p>
      </Step>
    </div>
  </section>

  <section
    id="about"
    class="py-20 pt-10 lg:pt-16 lg:py-32 flex flex-col gap-16 sm:gap-20 md:gap-24 relative"
  >
    <!-- <div class="z-[-1] bg-violet-950 w-screen left-1/2 -translate-x-1/2 top-0 h-full absolute"> </div> -->
    <div
      class="flex flex-col gap-2 text-center relative before:absolute before:top-0 before:left-0 before:w-2/3 before:h-1.5 before:bg-violet-700 after:absolute after:bottom-0 after:right-0 after:w-2/3 after:h-1.5 after:bg-violet-700 py-4"
    >
      <h6 class="text-large sm:text-xl md:text-2xl">Want to know more?</h6>
      <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
        A bit <span class="poppins text-violet-400">about</span> me.
      </h3>
    </div>
    <p class="mx-auto poppins font-semibold text-lg sm:text-xl md:text-2xl">
      I am . . .
    </p>
    <div class="flex flex-col gap-20 w-full mx-auto max-w-[800px]">
      {#each benefits as benefit, index}
        <div class="flex gap-6 sm:gap-8">
          <p
            class="poppins text-4xl sm:text-5xl md:text-6xl text-slate-500 font-semibold"
          >
            0{index + 1}
          </p>
          <div class="flex flex-col gap-6 sm:gap-8">
            <h3 class="text-2xl sm:text-3xl md:text-5xl">
              {benefit.name}
            </h3>
            <p>{benefit.description}</p>
          </div>
        </div>
      {/each}
    </div>
    <h5 class={" text-2xl sm:text-3xl font-semibold text-center poppins "}>
      The <span class="text-violet-400">Complete</span> Package
    </h5>
    <div
      class="flex flex-col overflow-x-scroll gap-10 max-w-[800px] mx-auto w-full"
    >
      <table class="bg-white text-slate-700 rounded text-center">
        <thead class={"border-b border-solid border-slate-200  "}>
          <tr class="">
            <th />
            <th class="whitespace-nowrap p-2 px-4">Candidate #1</th>
            <th class="whitespace-nowrap p-2 px-4">Candidate #2</th>
            <th class="whitespace-nowrap p-2 px-4">Candidate #3</th>
            <th class="bg-violet-700 text-white whitespace-nowrap p-4 px-8"
              >Me</th
            >
          </tr>
        </thead>
        <tbody>
          <tr class="border-b border-solid border-slate-200">
            <td
              class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
              >Dedication</td
            >
            <td><i class="fa-solid fa-xmark text-slate-500" /></td>
            <td><i class="fa-solid fa-check text-slate-500" /></td>
            <td><i class="fa-solid fa-xmark text-slate-500" /></td>
            <td><i class="fa-solid fa-check text-green-500" /></td>
          </tr>
          <tr class="border-b border-solid border-slate-200">
            <td
              class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
              >Critical Thought</td
            >
            <td><i class="fa-solid fa-xmark text-slate-500" /></td>
            <td><i class="fa-solid fa-check text-slate-500" /></td>
            <td><i class="fa-solid fa-check text-slate-500" /></td>
            <td><i class="fa-solid fa-check text-green-500" /></td>
          </tr>
          <tr>
            <td
              class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
              >Interpersonal Skills</td
            >
            <td><i class="fa-solid fa-check text-slate-500" /></td>
            <td><i class="fa-solid fa-check text-slate-500" /></td>
            <td><i class="fa-solid fa-xmark text-slate-500" /></td>
            <td><i class="fa-solid fa-check text-green-500" /></td>
          </tr>
          <tr class="border-t border-solid border-slate-200">
            <td
              class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
              >Progamming Ability</td
            >
            <td><i class="fa-solid fa-check text-slate-500" /></td>
            <td><i class="fa-solid fa-xmark text-slate-500" /></td>
            <td><i class="fa-solid fa-check text-slate-500" /></td>
            <td><i class="fa-solid fa-check text-green-500" /></td>
          </tr>
        </tbody>
      </table>
    </div>
    <div class="mx-auto -mt-12 italic sm:hidden opacity-50">
      <p>Scroll to see more &rarr;</p>
    </div>
    <p class="mx-auto">So why not invest?</p>
  </section>
</main>
