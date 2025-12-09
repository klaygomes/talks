---
htmlAttrs:
  lang: en
  dir: ltr
fonts:
  sans: Inter
  serif: Montserrat
  mono: Consolas
themeConfig:
  primary: '#7be495'
colorSchema: dark
glowSeed: 213
transition: fade-out
addons:
  - slidev-addon-inalia
title: Centralizing strategy, Node.js backend services, and frontend applications for small business financing.
titleTemplate: '%s - Cleiton Loiola'
author: Cleiton Loiola
keywords: web,development
---

<h1 class="text-center font-serif">
  Qred's Case Study
</h1>

<p class="text-center">
  By Cleiton Loiola
</p>

<div class="absolute right-6 bottom-6 flex flex-col gap-4 items-end">
  <span class="text-sm op-40">Qred</span>
  <span class="text-xs op-20 mt--4">06 November 2025</span>
</div>

<!--

https://remix.run/docs/en/main/discussion/pending-ui
https://dnlytras.com/blog/optimistic-updates

 -->

---
class: flex flex-col justify-between
glowSeed: 2
---

<div class="flex flex-col items-center justify-center">
  <img src="https://avatars.githubusercontent.com/u/522884?v=4" class="size-32" style="border-radius: 50%; object-fit: cover; overflow: hidden;"/>
  <div class="mt-4 text-xl font-serif font-medium">
    Cleiton Loiola
  </div>
  <div class="mt-1 text-sm op-60">
    Software design is an art, and like any art it cannot be taught and learned as precise science, by means of theorems and formulas.
  </div>
</div>

<Tools />

<div v-click class="grid grid-cols-2 gap-8">
  <Card>
    <div class="text-sm">
        Frontend Developer with over two decades of experience in the rapidly changing world of technology.
      </div>
      <div class="mt-1 text-xs op-60">
        Lifelong learner, always eager to use cutting-edge tools and learn new things. Currently focused on Node, Docker, and React on Linux-based systems.
      </div>
  </Card>

  <Card>
      <div class="text-sm">
        I have a crush on embedded devices and their development.
      </div>
      <div class="mt-1 text-xs op-60">
        I spend a lot of spare time playing with them, especially ARM Cortex M and the STM32F103xx series.
      </div>
  </Card>
</div>

<Socials />

<!--

Hi New Scrap! Para o Orkut que teve bastante atração
Ceifadeira Feliz - Um game cheater engine um game que fez sucesso no Orkut (Rede Social)

...

 -->

---
layout: center
clicks: 2
---

<h1 class="text-center font-serif transition ease duration-150" :class="{ 'text-[#877B8D]': $clicks >= 1 }">
  Qred's <span class="transition ease duration-150" :class="{ 'text-white' : $clicks === 1 }"></span> API <span class="transition ease duration-150" :class="{ 'text-white' : $clicks === 1 }">development process</span> is delayed and <span class="transition ease duration-150" :class="{ 'text-white' : $clicks === 1 }">misaligned</span>,<br>creating bottlenecks that prevent <span class="transition ease duration-150" :class="{ 'text-white' : $clicks === 1 }">parallel</span> frontend and backend work.
</h1>

<div v-click="2" class="absolute bottom-14 left-1/2 -translate-x-1/2 flex items-center gap-8 delay-300">
  <InlineCard>Alignment</InlineCard>
  <span class="i-lucide-arrow-right size-5 inline-block"></span>
  <InlineCard>Process</InlineCard>
  <span class="i-lucide-arrow-right size-5 inline-block"></span>
  <InlineCard>Automation</InlineCard>
</div>

<!--

  Alignment - A shared vocabulary is established to bridge communication gaps between technical and business teams. Developers implement this exact terminology in the code, aligning it with stakeholder discussions.

  Process -

 -->

---
layout: section
---

<h1 class="text-center font-serif flex items-center justify-center gap-3">
  <span class="i-ph-chats-teardrop-duotone text-3xl" aria-label="Common Language Icon" />
  Common Language
</h1>

---
layout: center
---

<h1 class="text-center font-serif flex items-center justify-center gap-3">
  <span class="i-ph-link-break-duotone text-3xl text-red-500" aria-label="Misalignment Icon" />
  Misalignment
</h1>

<div class="flex flex-wrap gap-2 justify-center mt-8">
  <span class="text-base font-bold text-gray-300">CQRS</span>
  <span class="text-sm text-gray-400">Saga pattern</span>
  <span class="text-base text-gray-400">Idempotency</span>
  <span class="text-lg font-bold text-gray-200">Webhooks</span>
  <span class="text-sm text-gray-500">Polyfill</span>
  <span class="text-base text-gray-500">SSR</span>
  <span class="text-sm text-gray-500">Rehydration</span>
  <span class="text-base text-gray-400">Shadow DOM</span>
  <span class="text-sm text-gray-300">Memoization</span>
  <span class="text-base text-gray-300">Debounce</span>
  <span class="text-lg text-gray-200">Throttling</span>
  <span class="text-base text-gray-200">Race condition</span>
  <span class="text-sm text-gray-400">Deadlock</span>
  <span class="text-base text-gray-500">Atomic commit</span>
  <span class="text-sm text-gray-500">Immutable state</span>
  <span class="text-base text-gray-500">Observables</span>
  <span class="text-sm text-gray-500">Pub/Sub</span>
  <span class="text-base text-gray-500">WebSocket handshake</span>
  <span class="text-lg text-gray-300">JWT</span>
  <span class="text-base text-gray-400">OAuth</span>
  <span class="text-sm text-gray-500">SAML</span>
  <span class="text-base text-gray-500">GraphQL mutation</span>
  <span class="text-sm text-gray-500">RESTful endpoint</span>
  <span class="text-base text-gray-500">gRPC</span>
  <span class="text-sm text-gray-500">Circuit breaker</span>
  <span class="text-base text-gray-500">Feature flag</span>
  <span class="text-lg text-gray-200">Blue/Green deployment</span>
  <span class="text-base text-gray-300">Canary release</span>
  <span class="text-sm text-gray-400"><span v-mark.yellow.underline="{at:1,padding:-2,seed:2,strokeWidth:2}">Smoke test</span></span>
  <span class="text-base text-gray-500"><span v-mark.yellow.underline="{at:1,padding:-2,seed:1,strokeWidth:2}">Dark launch</span></span>
  <span class="text-sm text-gray-500">Telemetry</span>
  <span class="text-base text-gray-500">Tracing</span>
  <span class="text-sm text-gray-500">Distributed logging</span>
  <span class="text-base text-gray-500">Backpressure</span>
  <span class="text-lg text-gray-300">Sharding</span>
  <span class="text-base text-gray-400">CAP theorem</span>
  <span class="text-sm text-gray-500">Quorum</span>
  <span class="text-base text-gray-500"><span v-mark.yellow.underline="{at:1,padding:-2,seed:3,strokeWidth:2}">Leader election</span></span>
  <span class="text-sm text-gray-500">Consensus algorithm</span>
  <span class="text-sm text-gray-500">Eventual consistency</span>
  <span class="text-base text-gray-500">Strong consistency</span>
  <span class="text-lg text-gray-200">Cache invalidation</span>
  <span class="text-sm text-gray-400">Cache warming</span>
  <span class="text-base text-gray-500">Edge computing</span>
  <span class="text-sm text-gray-500">Serverless</span>
  <span class="text-base text-gray-500">Lambda</span>
  <span class="text-lg text-gray-300"><span v-mark.yellow.underline="{at:1,padding:-2,seed:5,strokeWidth:2}">Cold start</span></span>
</div>

---
name:  Collaborative Tools
layout: section
---

<h1 class="text-center font-serif flex items-center justify-center gap-3">
  <span class="i-ph-handshake-duotone text-3xl" aria-label="Collaborative Tools Icon" />
  Collaborative Tools
</h1>

---
layout: center
---

<div class="flex flex-col items-center justify-center gap-4">
  <img src="/collaboration.png" alt="Main Slide Image" class="max-w-sm w-full rounded-xl shadow-lg" style="margin: 0 auto;" />
</div>

<div class="absolute right-6 bottom-6 flex flex-col gap-4 items-end">
  <span class="text-sm op-40">Conceptual phase</span>
</div>

<!--

  Antes de começar um novo projeto, usar o Miro ou outra ferramenta qualquer
  de colaboração e criar uma pequena apresentação onde a gente pode discutir pontos:

  - O que será o projeto?
  - Qual o objetivo?
  - Brainstorming

Defer judgment: All ideas are welcome initially, and criticism is forbidden to foster a free-thinking environment.
Encourage wild ideas: "Off-the-wall" or unusual ideas are encouraged, as they can spark new insights.
Build on others' ideas: Participants should listen to and expand on the ideas of others, using "and" to connect concepts instead of "but" to shut them down.
Focus on quantity: The goal is to generate as many ideas as possible, with the belief that quantity will lead to quality.
Stay on topic: Keep the discussion focused on the defined problem or goal to maintain productivity.

 -->

---
layout: center
---

<h1 class="text-center font-serif flex items-center justify-center gap-3">
  Conceptual phase
</h1>

<div class="grid grid-cols-1 gap-8 text-2xl font-medium text-left">
  <div class="flex items-start gap-4">
    <span class="i-ph-gavel-duotone inline-block size-10 mt-1"></span>
    <div>
      <span :class="{ 'opacity-100': $clicks == 1 }" class="font-bold opacity-20">Defer judgment</span>
      <span v-click="1" :class="{ 'opacity-20': $clicks > 1 }" class="block mt-2 text-base font-normal">All ideas are welcome initially, and criticism is forbidden to foster a free-thinking environment.</span>
    </div>
  </div>
  <div class="flex items-start gap-4">
    <span class="i-ph-lightbulb-duotone inline-block size-10 mt-1"></span>
    <div>
      <span :class="{ 'opacity-100': $clicks == 2 }" class="font-bold opacity-20">Encourage wild ideas</span>
      <span v-click="2" :class="{ 'opacity-20': $clicks > 2 }" class="block mt-2 text-base font-normal">"Off-the-wall" or unusual ideas are encouraged, as they can spark new insights.</span>
    </div>
  </div>
  <div class="flex items-start gap-4">
    <span class="i-ph-stack-duotone inline-block size-10 mt-1"></span>
    <div>
      <span :class="{ 'opacity-100': $clicks == 3 }" class="font-bold opacity-20">Focus on quantity</span>
      <span v-click="3" :class="{ 'opacity-20': $clicks > 3 }" class="block mt-2 text-base font-normal">The goal is to generate as many ideas as possible, with the belief that quantity will lead to quality.</span>
    </div>
  </div>
  <div class="flex items-start gap-4">
    <span class="i-ph-target-duotone inline-block size-10 mt-1"></span>
    <div>
      <span :class="{ 'opacity-100': $clicks == 4 }" class="font-bold opacity-20">Stay on topic</span>
      <span v-click="4" :class="{ 'opacity-20': $clicks > 4 }" class="block mt-2 text-base font-normal">Keep the discussion focused on the defined problem or goal to maintain productivity.</span>
    </div>
  </div>
</div>

---
name: wireframe
layout: center
---

<div class="flex flex-col items-center justify-center gap-4">
  <img src="/wireframe.png" alt="Main Slide Image" class="max-w-sm w-full rounded-xl shadow-lg" style="margin: 0 auto;" />
</div>

<div class="absolute right-6 bottom-6 flex flex-col gap-4 items-end">
  <span class="text-sm op-40">Wireframes and Design Docs</span>
</div>

<!--

  Antes de começar um novo projeto, é sempre legal a gente usar o Miro ou outra ferramenta qualquer
  de colaboração e criar uma pequena apresentação onde a gente pode discutir pontos
 -->

---
name: wireframe-uses
layout: section
---
<h1 class="text-center font-serif flex items-center justify-center gap-3">
  Wireframes
</h1>

<div class="grid grid-cols-1 gap-8 text-2xl font-medium text-left">
  <div class="flex items-start gap-4">
    <span class="i-ph-chat-circle-dots-duotone inline-block size-10 mt-1"></span>
    <div>
      <span :class="{ 'opacity-100': $clicks == 1 }" class="font-bold opacity-20">Facilitate discussion</span>
      <span v-click="1" :class="{ 'opacity-20': $clicks > 1 }" class="block mt-2 text-base font-normal">They provide a neutral ground for stakeholders to discuss features and user flows.</span>
    </div>
  </div>
  <div class="flex items-start gap-4">
    <span class="i-ph-arrows-clockwise-duotone inline-block size-10 mt-1"></span>
    <div>
      <span :class="{ 'opacity-100': $clicks == 2 }" class="font-bold opacity-20">Iterate quickly</span>
      <span v-click="2" :class="{ 'opacity-20': $clicks > 2 }" class="block mt-2 text-base font-normal">Easy to change, anyone can try out new ideas and refine concepts early in the process.</span>
    </div>
  </div>
  <div class="flex items-start gap-4">
    <span class="i-ph-handshake-duotone inline-block size-10 mt-1"></span>
    <div>
      <span :class="{ 'opacity-100': $clicks == 3 }" class="font-bold opacity-20">Align teams</span>
      <span v-click="3" :class="{ 'opacity-20': $clicks > 3 }" class="block mt-2 text-base font-normal">They ensure everyone—designers, developers, and stakeholders—shares the same understanding.</span>
    </div>
  </div>
</div>

---
name: design-docs
layout: section
---

<h1 class="text-center font-serif flex items-center justify-center gap-3">
  Design Docs
</h1>

<div class="grid grid-cols-1 gap-8 text-2xl font-medium text-left">
  <div class="flex items-start gap-4">
    <span class="i-ph-arrow-bend-double-up-right-duotone inline-block size-10 mt-1"></span>
    <div>
      <span :class="{ 'opacity-100': $clicks == 1 }" class="font-bold opacity-20">Guide implementation</span>
      <span v-click="1" :class="{ 'opacity-20': $clicks > 1 }" class="block mt-2 text-base font-normal">They serve as a reference for developers, helping ensure the codebase aligns with the intended architecture and decisions.</span>
    </div>
  </div>
  <div class="flex items-start gap-4">
    <span class="i-ph-users-three-duotone inline-block size-10 mt-1"></span>
    <div>
      <span :class="{ 'opacity-100': $clicks == 2 }" class="font-bold opacity-20">Enable collaboration</span>
      <span v-click="2" :class="{ 'opacity-20': $clicks > 2 }" class="block mt-2 text-base font-normal">Design docs provide a shared foundation for discussion, review, and feedback among engineers, architects, and stakeholders.</span>
    </div>
  </div>
  <div class="flex items-start gap-4">
    <span class="i-ph-clock-counter-clockwise-duotone inline-block size-10 mt-1"></span>
    <div>
      <span :class="{ 'opacity-100': $clicks == 3 }" class="font-bold opacity-20">Document decisions</span>
      <span v-click="3" :class="{ 'opacity-20': $clicks > 3 }" class="block mt-2 text-base font-normal">They record the rationale behind architectural choices, making it easier to onboard new team members and revisit decisions later.</span>
    </div>
  </div>
</div>

---
name: design-docs
layout: section
---
<div class="flex flex-col items-center justify-center my-8">
  <video id="design-doc-video" autoplay muted loop playsinline class="max-w-md w-full rounded-xl shadow-lg">
    <source src="/design-doc.mov" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>
<script setup>
import { onMounted } from 'vue'
onMounted(() => {
  const video = document.getElementById('design-doc-video');
  if (video) video.playbackRate = 0.5;
});
</script>

<div class="absolute right-6 bottom-6 flex flex-col gap-4 items-end">
  <span class="text-sm op-40">Example design doc</span>
</div>

---
name: automation
layout: section
---

<h1 class="text-center font-serif flex items-center justify-center gap-3">
  <span class="i-ph-robot-duotone text-3xl" aria-label="Automation Icon" />
  Automation
</h1>

<div class="grid grid-cols-1 gap-8 text-2xl font-medium text-left mt-8">
  <div class="flex items-start gap-4">
    <span class="i-ph-code-duotone inline-block size-10 mt-1"></span>
    <div>
      <span :class="{ 'opacity-100': $clicks == 1 }" class="font-bold opacity-20">OpenAPI-driven automation</span>
      <span v-click="1" :class="{ 'opacity-20': $clicks > 1 }" class="block mt-2 text-base font-normal">Generate client/server code, docs, validation and mocks automatically from OpenAPI specs.</span>
    </div>
  </div>
  <div class="flex items-start gap-4">
    <span class="i-ph-terminal-window-duotone inline-block size-10 mt-1"></span>
    <div>
      <span :class="{ 'opacity-100': $clicks == 2 }" class="font-bold opacity-20">Custom CLIs</span>
      <span v-click="2" :class="{ 'opacity-20': $clicks > 2 }" class="block mt-2 text-base font-normal">Command-line tools to automate code generation, and repetitive workflows.</span>
    </div>
  </div>
  <div class="flex items-start gap-4">
    <span class="i-ph-cube-duotone inline-block size-10 mt-1"></span>
    <div>
  <span :class="{ 'opacity-100': $clicks == 3 }" class="font-bold opacity-20">Custom MCPs</span>
  <span v-click="3" :class="{ 'opacity-20': $clicks > 3 }" class="block mt-2 text-base font-normal">That understand your design system and infrastructure, running locally to perform tasks and also on the server for broader automation.</span>
    </div>
  </div>
  <div class="flex items-start gap-4">
    <span class="i-ph-brain-duotone inline-block size-10 mt-1"></span>
    <div>
      <span :class="{ 'opacity-100': $clicks == 4 }" class="font-bold opacity-20">LLM-powered automation</span>
      <span v-click="4" :class="{ 'opacity-20': $clicks > 4 }" class="block mt-2 text-base font-normal">Use of LLMs to generate code, documentation, and even automate code reviews or refactoring tasks.</span>
    </div>
  </div>
</div>

---
layout: center
---

<div class="flex flex-col items-center justify-center gap-4">
  <img src="/openapi.png" alt="Main Slide Image" class="max-w-lg w-full rounded-xl shadow-lg" style="margin: 0 auto;" />
</div>

<div class="absolute right-6 bottom-6 flex flex-col gap-4 items-end">
  <span class="text-sm op-40">Schema First Design</span>
</div>

---
layout: center
class: relative
glowSeed: 3
---

<h1 text="center" font="serif">Thank you!</h1>

<hr class="bg-white op-20 my-12" />

<Card class="flex flex-col p-6">
  <img src="https://avatars.githubusercontent.com/u/522884?v=4" class="size-32 self-center" style="border-radius: 50%; object-fit: cover; overflow: hidden;"/>

  <span class="mt-6 text-center text-xl font-serif font-medium">
    Cleiton Loiola
  </span>

  <span class="mt-1 text-center text-sm op-60">

    Why do programmers love writing design docs?
    Because it’s the only time their architecture is bug-free!

  </span>
</Card>

---
layout: center
class: relative
glowSeed: 8
---

<h1 text="center" font="serif">Questions?</h1>
