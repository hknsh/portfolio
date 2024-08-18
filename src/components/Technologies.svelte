<script>
  import Astro from '../svg/frameworks/astro.svelte'
  import Express from '../svg/frameworks/express.svelte'
  import Fastify from '../svg/frameworks/fastify.svelte'
  import Jest from '../svg/frameworks/jest.svelte'
  import Nest from '../svg/frameworks/nest.svelte'
  import Js from '../svg/languages/js.svelte'
  import Rust from '../svg/languages/rust.svelte'
  import Ts from '../svg/languages/ts.svelte'
  import Docker from '../svg/tech/docker.svelte'
  import Git from '../svg/tech/git.svelte'
  import Linux from '../svg/tech/linux.svelte'
  import Prisma from '../svg/tech/prisma.svelte'
  import Swagger from '../svg/tech/swagger.svelte'
</script>

<div class="flex flex-col space-y-6">
  <div class="mr-4 space-y-6 p-2 md:p-4">
    <div id="languages" class="pyramid-rows">
      <div class="tech-box">
        <Js />
        <span class="link">Javascript</span>
      </div>
      <div class="tech-box">
        <Ts />
        <span class="link">Typescript</span>
      </div>
      <div class="tech-box">
        <Rust />
        <span class="link">Rust</span>
      </div>
    </div>
    <div id="frameworks" class="pyramid-rows">
      <div class="tech-box">
        <Express />
        <span class="link">ExpressJS</span>
      </div>
      <div class="tech-box">
        <Nest />
        <span class="link">NestJS</span>
      </div>
      <div class="tech-box">
        <Astro />
        <span class="link">Astro</span>
      </div>
      <div class="tech-box">
        <Fastify />
        <span class="link">Fastify</span>
      </div>
    </div>

    <div id="techs" class="pyramid-rows">
      <div class="tech-box">
        <Docker />
        <span class="link">Docker</span>
      </div>
      <div class="tech-box">
        <Swagger />
        <span class="link">Swagger</span>
      </div>
      <div class="tech-box">
        <Git />
        <span class="link">Git</span>
      </div>
      <div class="tech-box">
        <Jest />
        <span class="link">Jest</span>
      </div>
      <div class="tech-box">
        <Linux />
        <span class="link">Linux</span>
      </div>
      <div class="tech-box">
        <Prisma />
        <span class="link">Prisma</span>
      </div>
    </div>
  </div>
</div>
