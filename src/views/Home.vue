<script setup>
import { ref } from "vue";

const uniClassCards = ref([{ name: "CS 135" }, { name: "PHIL 114 " }]);

const uniSkills = ref([
  { name: "C++" },
  { name: "Symbolic Logic: LFOL & LPL " },
  { name: "Computer Science" },
]);

const projectArr = ref([
  {
    title: "LearnTigrigna",
    duration: "October 2023 - Present",
    discontinued: false,
    link: "https://www.learntigrigna.com",
    focus:
      "Founder & Developer of a new easy way to solo-learn Tigrigna: enabling the Eritrean and Ethiopian diasporas to connect back with their families back home and learn the culture of the Tigrigna-speaking peoples.",
    skills: [
      {
        skill_name: "JavaScript",
        logo: "https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png",
      },
      {
        skill_name: "Vue.js",
        logo: "https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/1184px-Vue.js_Logo_2.svg.png",
      },
      {
        skill_name: "Web Development",
        logo: "https://media.discordapp.net/attachments/1201662358171435030/1259300190083485788/208-2082229_html-code-coding-language-html-code-icon-png-removebg-preview.png?ex=668b2e31&is=6689dcb1&hm=3bfa7c74408d7f88732a3e490d97f18fdc9e272774ac1f9c47006c4f50b1a7ce&=&format=webp&quality=lossless",
      },
      {
        skill_name: "Tailwind CSS",
        logo: "https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/Tailwind_CSS_Logo.svg/768px-Tailwind_CSS_Logo.svg.png?20230715030042",
      },
    ],
  },
  {
    title: "Engineers Without Borders - UNLV",
    duration: "Feburary 2024 - Present",
    discontinued: false,
    link: "https://www.ewbunlv.org",
    focus:
      "This is the official website of UNLV's EWB branch. I made the whole website from scratch, and I continue to make sure that this website is up-to-date and represents the EWB mission well.",
    skills: [
      {
        skill_name: "JavaScript",
        logo: "https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png",
      },
      {
        skill_name: "Vue.js",
        logo: "https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/1184px-Vue.js_Logo_2.svg.png",
      },
      {
        skill_name: "Web Development",
        logo: "https://media.discordapp.net/attachments/1201662358171435030/1259300190083485788/208-2082229_html-code-coding-language-html-code-icon-png-removebg-preview.png?ex=668b2e31&is=6689dcb1&hm=3bfa7c74408d7f88732a3e490d97f18fdc9e272774ac1f9c47006c4f50b1a7ce&=&format=webp&quality=lossless",
      },
      {
        skill_name: "Tailwind CSS",
        logo: "https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/Tailwind_CSS_Logo.svg/768px-Tailwind_CSS_Logo.svg.png?20230715030042",
      },
      {
        skill_name: "Team Work",
        logo: "https://media.discordapp.net/attachments/1201662358171435030/1259301897458946089/pngtree-colorful-teamwork-logo-png-image_4127029-removebg-preview.png?ex=668b2fc9&is=6689de49&hm=fcdabeb9a1ba5b0a369c4603705e6402e9f4e20dab8fb3764818dd5d40635f6b&=&format=webp&quality=lossless",
      },
      {
        skill_name: "Volunteering",
        logo: "https://gallery.yopriceville.com/var/albums/Free-Clipart-Pictures/Hands-PNG/Handshake_Transparent_PNG_Clip_Art_Image.png?m=1629804916",
      },
    ],
  },
  {
    title: "MZGBT",
    duration: "January 2024 - Present",
    discontinued: false,
    link: "https://www.mzgbt.org",
    focus:
      "Founder & developer of the first unofficial online internet archive of East African history and culture. This site archives text documents, images, and artifacts with search and a contribution mechanism for aspiring archive contributors.",
    skills: [
      {
        skill_name: "TypeScript",
        logo: "https://upload.wikimedia.org/wikipedia/commons/thumb/4/4c/Typescript_logo_2020.svg/768px-Typescript_logo_2020.svg.png",
      },
      {
        skill_name: "JavaScript",
        logo: "https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png",
      },
      {
        skill_name: "Vue.js",
        logo: "https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/1184px-Vue.js_Logo_2.svg.png",
      },
      {
        skill_name: "Web Development",
        logo: "https://media.discordapp.net/attachments/1201662358171435030/1259300190083485788/208-2082229_html-code-coding-language-html-code-icon-png-removebg-preview.png?ex=668b2e31&is=6689dcb1&hm=3bfa7c74408d7f88732a3e490d97f18fdc9e272774ac1f9c47006c4f50b1a7ce&=&format=webp&quality=lossless",
      },
      {
        skill_name: "Tailwind CSS",
        logo: "https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/Tailwind_CSS_Logo.svg/768px-Tailwind_CSS_Logo.svg.png?20230715030042",
      },
    ],
  },
  {
    title: "My Portfolio",
    duration: "September 2023 - Present",
    discontinued: false,
    link: "https://www.abrahaatsbeha.com",
    focus:
      "I made this portfolio to showcase my work and effort. This website was build from scratch using the Vue 3 javascript framework, and hosted using Heroku.",
    skills: [
    {
        skill_name: "TypeScript",
        logo: "https://upload.wikimedia.org/wikipedia/commons/thumb/4/4c/Typescript_logo_2020.svg/768px-Typescript_logo_2020.svg.png",
      },
      {
        skill_name: "Vue.js",
        logo: "https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/1184px-Vue.js_Logo_2.svg.png",
      },
      {
        skill_name: "Web Development",
        logo: "https://media.discordapp.net/attachments/1201662358171435030/1259300190083485788/208-2082229_html-code-coding-language-html-code-icon-png-removebg-preview.png?ex=668b2e31&is=6689dcb1&hm=3bfa7c74408d7f88732a3e490d97f18fdc9e272774ac1f9c47006c4f50b1a7ce&=&format=webp&quality=lossless",
      },
      {
        skill_name: "Tailwind CSS",
        logo: "https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/Tailwind_CSS_Logo.svg/768px-Tailwind_CSS_Logo.svg.png?20230715030042",
      },
    ],
  },
  {
    title: "Tigray Community of Las Vegas",
    duration: "Feburary 2024 - Present",
    discontinued: false,
    link: "https://www.tigrayclv.org",
    focus:
      "I volunteered to create & deploy an official website for the Tigray diaspora community of Las Vegas. The website organizes a list of events, businesses, info about our community, our history, etc.",
    skills: [
      {
        skill_name: "JavaScript",
        logo: "https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png",
      },
      {
        skill_name: "Vue.js",
        logo: "https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/1184px-Vue.js_Logo_2.svg.png",
      },
      {
        skill_name: "Web Development",
        logo: "https://media.discordapp.net/attachments/1201662358171435030/1259300190083485788/208-2082229_html-code-coding-language-html-code-icon-png-removebg-preview.png?ex=668b2e31&is=6689dcb1&hm=3bfa7c74408d7f88732a3e490d97f18fdc9e272774ac1f9c47006c4f50b1a7ce&=&format=webp&quality=lossless",
      },
      {
        skill_name: "Tailwind CSS",
        logo: "https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/Tailwind_CSS_Logo.svg/768px-Tailwind_CSS_Logo.svg.png?20230715030042",
      },
      {
        skill_name: "Team Work",
        logo: "https://media.discordapp.net/attachments/1201662358171435030/1259301897458946089/pngtree-colorful-teamwork-logo-png-image_4127029-removebg-preview.png?ex=668b2fc9&is=6689de49&hm=fcdabeb9a1ba5b0a369c4603705e6402e9f4e20dab8fb3764818dd5d40635f6b&=&format=webp&quality=lossless",
      },
      {
        skill_name: "Volunteering",
        logo: "https://gallery.yopriceville.com/var/albums/Free-Clipart-Pictures/Hands-PNG/Handshake_Transparent_PNG_Clip_Art_Image.png?m=1629804916",
      },
    ],
  },
  {
    title: "You&LV",
    duration: "May 2023 - October 2023",
    discontinued: false,
    link: "https://www.younlv.com",
    focus:
      "This project focused on providing the UNLV community with a new UNLV-centered platform for online conection, academic cooperation, and student-based selling of unneeded productions, such as textbooks.",
    skills: [
      {
        skill_name: "JavaScript",
        logo: "https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png",
      },
      {
        skill_name: "Vue.js",
        logo: "https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/1184px-Vue.js_Logo_2.svg.png",
      },
      {
        skill_name: "Web Development",
        logo: "https://media.discordapp.net/attachments/1201662358171435030/1259300190083485788/208-2082229_html-code-coding-language-html-code-icon-png-removebg-preview.png?ex=668b2e31&is=6689dcb1&hm=3bfa7c74408d7f88732a3e490d97f18fdc9e272774ac1f9c47006c4f50b1a7ce&=&format=webp&quality=lossless",
      },
      {
        skill_name: "Tailwind CSS",
        logo: "https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/Tailwind_CSS_Logo.svg/768px-Tailwind_CSS_Logo.svg.png?20230715030042",
      },
    ],
  },
  {
    title: "HSWeb",
    duration: "October 2022 - May 2023",
    discontinued: true,
    focus:
      "My first successful website, where I made a forum for my high school (similar to YouNLV). This was aimed at being able to foster better academic cooperation, awareness, and community engagement with students at my high school.",
    skills: [
      {
        skill_name: "JavaScript",
        logo: "https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png",
      },
      {
        skill_name: "Vue.js",
        logo: "https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/1184px-Vue.js_Logo_2.svg.png",
      },
      {
        skill_name: "Web Development",
        logo: "https://media.discordapp.net/attachments/1201662358171435030/1259300190083485788/208-2082229_html-code-coding-language-html-code-icon-png-removebg-preview.png?ex=668b2e31&is=6689dcb1&hm=3bfa7c74408d7f88732a3e490d97f18fdc9e272774ac1f9c47006c4f50b1a7ce&=&format=webp&quality=lossless",
      },
      {
        skill_name: "Vuetify CSS",
        logo: "https://cdn.worldvectorlogo.com/logos/vuetify.svg",
      },
    ],
  },
]);

const interests = ref([
  { name: "Computer Science student" },
  { name: "Chess enjoyer" },
  { name: "Deacon candidate" },
  { name: "History enthusiast" },
  { name: "Swimming" },
  { name: "Basketball" },
]);
</script>

<template>
  <div
    class="w-full p-2 max-w-[1200px] flex flex-col items-center justify-center mx-auto"
  >
    <div class="flex flex-col items-center justify-center">
      <div class="w-40">
        <img
          class="rounded-full"
          src="https://imgix.brilliant-ethiopia.com/Tigray-Gheralta-View.jpg?auto=format,enhance,compress&fit=crop&crop=entropy,faces,focalpoint&w=580&h=480&q=40"
        />
      </div>
      <div class="p-1"></div>
      <div class="text-center">
        <p class="font-semibold text-xl">Hi!</p>
        <p>Welcome to my portfolio :)</p>
      </div>
    </div>

    <div class="flex my-5">
      <div class="mb-2 flex items-center">
        <a href="https://www.linkedin.com/in/abrahaatsbeha/" target="_blank">
          <button class="sociallink">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              x="0px"
              y="0px"
              width="35"
              height="35"
              viewBox="0 0 24 24"
            >
              <path
                d="M19,3H5C3.895,3,3,3.895,3,5v14c0,1.105,0.895,2,2,2h14c1.105,0,2-0.895,2-2V5C21,3.895,20.105,3,19,3z M9,17H6.477v-7H9 V17z M7.694,8.717c-0.771,0-1.286-0.514-1.286-1.2s0.514-1.2,1.371-1.2c0.771,0,1.286,0.514,1.286,1.2S8.551,8.717,7.694,8.717z M18,17h-2.442v-3.826c0-1.058-0.651-1.302-0.895-1.302s-1.058,0.163-1.058,1.302c0,0.163,0,3.826,0,3.826h-2.523v-7h2.523v0.977 C13.93,10.407,14.581,10,15.802,10C17.023,10,18,10.977,18,13.174V17z"
              ></path>
            </svg>
          </button>
        </a>
        <a href="https://www.instagram.com/tgryeth_student/" target="_blank">
          <button class="sociallink">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              x="0px"
              y="0px"
              width="35"
              height="35"
              viewBox="0 0 24 24"
            >
              <path
                d="M 8 3 C 5.239 3 3 5.239 3 8 L 3 16 C 3 18.761 5.239 21 8 21 L 16 21 C 18.761 21 21 18.761 21 16 L 21 8 C 21 5.239 18.761 3 16 3 L 8 3 z M 18 5 C 18.552 5 19 5.448 19 6 C 19 6.552 18.552 7 18 7 C 17.448 7 17 6.552 17 6 C 17 5.448 17.448 5 18 5 z M 12 7 C 14.761 7 17 9.239 17 12 C 17 14.761 14.761 17 12 17 C 9.239 17 7 14.761 7 12 C 7 9.239 9.239 7 12 7 z M 12 9 A 3 3 0 0 0 9 12 A 3 3 0 0 0 12 15 A 3 3 0 0 0 15 12 A 3 3 0 0 0 12 9 z"
              ></path>
            </svg>
          </button>
        </a>
        <a href="https://github.com/theplaceincan" target="_blank">
          <button class="sociallink">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              x="0px"
              y="0px"
              width="35"
              height="35"
              viewBox="0 0 24 24"
            >
              <path
                d="M 12 2 C 6.476563 2 2 6.476563 2 12 C 2 17.523438 6.476563 22 12 22 C 17.523438 22 22 17.523438 22 12 C 22 6.476563 17.523438 2 12 2 Z M 12 4 C 16.410156 4 20 7.589844 20 12 C 20 12.46875 19.953125 12.929688 19.875 13.375 C 19.628906 13.320313 19.265625 13.253906 18.84375 13.25 C 18.53125 13.246094 18.140625 13.296875 17.8125 13.34375 C 17.925781 12.996094 18 12.613281 18 12.21875 C 18 11.257813 17.53125 10.363281 16.78125 9.625 C 16.988281 8.855469 17.191406 7.535156 16.65625 7 C 15.074219 7 14.199219 8.128906 14.15625 8.1875 C 13.667969 8.070313 13.164063 8 12.625 8 C 11.933594 8 11.273438 8.125 10.65625 8.3125 L 10.84375 8.15625 C 10.84375 8.15625 9.964844 6.9375 8.34375 6.9375 C 7.777344 7.507813 8.035156 8.953125 8.25 9.6875 C 7.484375 10.417969 7 11.28125 7 12.21875 C 7 12.546875 7.078125 12.859375 7.15625 13.15625 C 6.878906 13.125 5.878906 13.03125 5.46875 13.03125 C 5.105469 13.03125 4.542969 13.117188 4.09375 13.21875 C 4.03125 12.820313 4 12.414063 4 12 C 4 7.589844 7.589844 4 12 4 Z M 5.46875 13.28125 C 5.863281 13.28125 7.0625 13.421875 7.21875 13.4375 C 7.238281 13.492188 7.257813 13.542969 7.28125 13.59375 C 6.851563 13.554688 6.019531 13.496094 5.46875 13.5625 C 5.101563 13.605469 4.632813 13.738281 4.21875 13.84375 C 4.1875 13.71875 4.148438 13.597656 4.125 13.46875 C 4.5625 13.375 5.136719 13.28125 5.46875 13.28125 Z M 18.84375 13.5 C 19.242188 13.503906 19.605469 13.570313 19.84375 13.625 C 19.832031 13.691406 19.796875 13.746094 19.78125 13.8125 C 19.527344 13.753906 19.109375 13.667969 18.625 13.65625 C 18.390625 13.652344 18.015625 13.664063 17.6875 13.6875 C 17.703125 13.65625 17.707031 13.625 17.71875 13.59375 C 18.058594 13.546875 18.492188 13.496094 18.84375 13.5 Z M 6.09375 13.78125 C 6.65625 13.785156 7.183594 13.824219 7.40625 13.84375 C 7.929688 14.820313 8.988281 15.542969 10.625 15.84375 C 10.222656 16.066406 9.863281 16.378906 9.59375 16.75 C 9.359375 16.769531 9.113281 16.78125 8.875 16.78125 C 8.179688 16.78125 7.746094 16.160156 7.375 15.625 C 7 15.089844 6.539063 15.03125 6.28125 15 C 6.019531 14.96875 5.929688 15.117188 6.0625 15.21875 C 6.824219 15.804688 7.097656 16.5 7.40625 17.125 C 7.683594 17.6875 8.265625 18 8.90625 18 L 9.03125 18 C 9.011719 18.109375 9 18.210938 9 18.3125 L 9 19.40625 C 6.691406 18.472656 4.933594 16.5 4.28125 14.0625 C 4.691406 13.960938 5.152344 13.855469 5.5 13.8125 C 5.660156 13.792969 5.863281 13.777344 6.09375 13.78125 Z M 18.625 13.90625 C 19.074219 13.917969 19.472656 14.003906 19.71875 14.0625 C 19.167969 16.132813 17.808594 17.855469 16 18.90625 L 16 18.3125 C 16 17.460938 15.328125 16.367188 14.375 15.84375 C 15.957031 15.554688 16.988281 14.863281 17.53125 13.9375 C 17.910156 13.910156 18.355469 13.898438 18.625 13.90625 Z M 12.5 18 C 12.773438 18 13 18.226563 13 18.5 L 13 19.9375 C 12.671875 19.980469 12.339844 20 12 20 L 12 18.5 C 12 18.226563 12.226563 18 12.5 18 Z M 10.5 19 C 10.773438 19 11 19.226563 11 19.5 L 11 19.9375 C 10.664063 19.894531 10.324219 19.832031 10 19.75 L 10 19.5 C 10 19.226563 10.226563 19 10.5 19 Z M 14.5 19 C 14.742188 19 14.953125 19.175781 15 19.40625 C 14.675781 19.539063 14.34375 19.660156 14 19.75 L 14 19.5 C 14 19.226563 14.226563 19 14.5 19 Z"
              ></path>
            </svg>
          </button>
        </a>
      </div>
    </div>

    <div class="mt-5 w-full flex flex-col items-center justify-center mx-auto">
      <p class="text-lg font-semibold mb-5">About Me</p>
      <div class="w-full max-w-[800px] flex items-center flex-row">
        <div class="w-full">
          <div
            class="flex flex-col items-center justify-center text-center space-y-3"
          >
            <p>
              I have a long-developed passion for expanding opportunities and
              solving problems through technology and science. I study computer
              science and apply my knowledge & passion towards developing
              innovative web applications for education, organizations, and
              communities.
            </p>
            <p>
              Outside of studying and projects, I enjoy playing Chess. My
              favorite sport is Basketball. I’m also originally from Ethiopia.
            </p>
            <div class="flex flex-wrap items-center justify-center">
              <p
                v-for="interest in interests"
                class="mt-4 m-1 bg-zinc-100 rounded-xl px-2 font-semibold text-sm"
              >
                {{ interest.name }}
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="px-5 w-full">
      <div class="p-[0.8px] mt-10 mb-5 w-full bg-zinc-200"></div>
    </div>
    <div class="mt-5 w-full flex flex-col items-center justify-center mx-auto">
      <p class="text-lg font-semibold mb-5">Education</p>
      <div class="w-full max-w-[800px] flex items-center flex-row">
        <div class="isPC">
          <img class="w-32" src="/src/assets/unlv.png" />
        </div>
        <div class="p-1"></div>
        <div class="w-full">
          <div class="flex justify-between">
            <p>University of Nevada, Las Vegas</p>
            <div class="p-2"></div>
            <p class="text-zinc-400 text-sm">2023 - Present</p>
          </div>
          <p class="text-zinc-500">BS Computer Science</p>
          <div class="flex mt-1">
            <p
              v-for="uniclass in uniClassCards"
              class="px-2 mr-1 text-sm font-semibold bg-zinc-100 rounded-xl"
            >
              {{ uniclass.name }}
            </p>
          </div>
        </div>
      </div>
      <div class="flex mt-5 flex-wrap justify-center">
        <p
          v-for="skill in uniSkills"
          class="px-2 m-1 text-sm font-semibold bg-zinc-100 rounded-xl"
        >
          {{ skill.name }}
        </p>
      </div>
    </div>
    <div class="px-5 w-full">
      <div class="p-[0.8px] mt-6 mb-5 w-full bg-zinc-200"></div>
    </div>
    <div class="mt-5 w-full flex flex-col items-center justify-center mx-auto">
      <p class="text-lg font-semibold mb-5">Experience</p>
      <div class="w-full max-w-[800px] flex items-center flex-row">
        <div class="isPC">
          <img class="w-32" src="/src/assets/ewbunlv.jpeg" />
        </div>
        <div class="p-1"></div>
        <div class="w-full">
          <div class="flex justify-between">
            <p class="">Engineers Without Borders - UNLV</p>
            <div class="p-2"></div>
            <p class="text-zinc-400 text-sm">Feb 2024 - Present</p>
          </div>
          <p class="text-lg font-semibold">Webmaster</p>
          <p class="text-zinc-500">
            I"ve been responsible for upkeeping and developing the official EWB
            UNLV website. I continue to cooperate with my fellow EWB team
            members to make sure that the website always reflects the mission
            and effort of EWB.
          </p>
        </div>
      </div>
    </div>

    <div class="px-5 w-full">
      <div class="p-[0.8px] mt-10 mb-5 w-full bg-zinc-200"></div>
    </div>
    <div class="mt-5 w-full flex flex-col items-center justify-center mx-auto">
      <p class="text-lg font-semibold mb-5">Projects & Works</p>
      <div class="w-full flex flex-row flex-wrap items-start justify-center">
        <div
          v-for="project in projectArr"
          :key="project.id"
          class="m-1 p-3 rounded-xl border transition w-72 ease-in-out hover:bg-zinc-50"
        >
          <a target="_blank" :href="project.link">
            <p
              v-if="project.discontinued"
              class="text-sm text-zinc-500 bg-red-100 w-fit mb-2 px-2 rounded-xl"
            >
              Discontinued
            </p>
            <p class="text-xl font-semibold mb-2">{{ project.title }}</p>
            <p class="indent-3 text-zinc-700">{{ project.focus }}</p>
            <p class="text-sm text-zinc-400 mt-2">{{ project.duration }}</p>
            <div class="flex flex-wrap mt-12">
              <div
                v-for="skill in project.skills"
                :key="skill.skill_name"
                class="px-2 p-1 m-1 flex items-center justify-center space-x-2 text-sm font-semibold bg-zinc-200 rounded-xl"
              >
                <img class="w-5" :src="skill.logo" />
                <p>{{ skill.skill_name }}</p>
              </div>
            </div>
          </a>
        </div>
      </div>
      <div class="px-5 w-full">
        <div class="p-[0.8px] mt-6 mb-5 w-full bg-zinc-200"></div>
      </div>
    </div>
    <div class="mt-5 flex flex-col items-center justify-center text-center">
      <p class="font-semibold">Fun Fact</p>
      <p class="text-sm text-zinc-500">
        Abraha Atsbeha is the name of one of Ethiopia's oldest churches; completely rock-hewn. It was
        build by Abraha and Atsbeha, who were brothers that both co-ruled the
        Aksumite Kingdom: a powerful East African & Southern Arabian trading
        empire that lasted 1110 years. The church is still used today and has
        developed into a small village, located in central Tigray.
      </p>
      <div class="max-w-[700px]">
        <img
          class="mt-3"
          src="https://i.redd.it/815cn1dr6xq51.jpg"
        />
      </div>
      <div class="max-w-[700px]">
        <img
          class="mt-3"
          src="https://cloudflare1.360gigapixels.com/pano/martin-c-broomfield/01636904_church-1-jpg/equirect_crop_3_1/6.jpg"
        />
      </div>
    </div>
  </div>
</template>

<style scoped></style>
