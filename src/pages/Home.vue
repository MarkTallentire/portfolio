<template>
  <main
    class=" px-10 py-20 text-gray-700 container mx-auto"
  >
    <h1 class="text-5xl font-bold font-sans">Hi, I'm Mark</h1>
    <p class="text-4xl pt-10 pb-1">
      I'm a UI/UX Software Engineer based in Teesside, England. I specialise in
      making minimalistic designs and clean functional interfaces for a better
      World Wide Web utilising the latest Javascript Frameworks/Libraries
    </p>
    <p class="text-lg">
      (Sometimes you'll even catch me writing backend code in C# .NET (Core/6), or playing Anno)

    </p>

    <section class="Portfolio">
      <h2 class="text-5xl pt-20">My Projects</h2>
      <h3 class="text-4xl pt-3 pb-2">Prompt @ npower</h3>
      <p>
        Prompt was a workflow management tool created in house for the now
        defunct energy supplier npower, it utilised .net and SQL in the backend
        and Razor Pages/JQuery in the frontend. Prompt was designed and
        developed by myself and one other developer, it was rolled out in house
        at npower and its offshore partners TCS and Capita in 2018 and achieved
        massive productivity improvements across the business. In 2021, npower
        ceased trading due to a takeover from another energy supplier who
        recognised the massive benefits of our system immediately, initial talks
        were had to bring Prompt over to the new supplier but they ultimately
        collapsed and development has now ceased.
      </p>
      <div class="py-10">
      <h3 class="text-4xl pb-2">vNext @ Exis Technologies (Current Project)</h3>
      <p>
        Exis Technologies mission is the 'Safety of Life and Cargo at Sea' and
        vNext is a product that helps achieve this by providing cargo shipping
        companies across the world with the tools they need to ship dangerous
        goods in a safe manner.
      </p>

        <p>Utilising VueJS, Typescript, Pinia, Vue-Router, Jest and Cypress,
          I am responsible for building the newest iteration of Exis's frontend interfaces to ensure that their mission is successful, 
          vNext is due to launch in 2022 and is expected to significantly improve our customers relationship with our software
          </p>

      </div>
    </section>
     <section class="Portfolio container">
      <h2 class="text-5xl pt-10">Contact Me</h2>
      <a class="text-4xl pt-3 text-blue-600" href="https://www.linkedin.com/in/mark-tallentire-a1331738/">LinkedIn</a>
     
    </section>
  </main>

  <footer class="flex items-center justify-center">
    <img src="/ribbon-black.png" height="70" width="50" alt="Black Ribbon"/>
    <p>Queen Elizabeth II 1926-2022</p>
  </footer>
</template>

<script lang="ts" setup></script>
