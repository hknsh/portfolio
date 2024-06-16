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
  import Vim from '../svg/tech/vim.svelte'
</script>

<div class="flex flex-col space-y-6">
  <p class="text-xl">Technologies that I know how to use:</p>
  <div class="mr-2 space-y-6 rounded-2xl border border-neutral-700 p-2 md:p-4">
    <div class="flex-center flex-row">
      <Vim />
    </div>
    <div id="languages" class="flex-center flex-row space-x-6">
      <Js />
      <Ts />
      <Rust />
    </div>
    <div id="frameworks" class="flex-center flex-row space-x-6">
      <Express />
      <Nest />
      <Astro />
      <Fastify />
    </div>

    <div id="techs" class="flex-center flex-row space-x-6">
      <Docker />
      <Swagger />
      <Git />
      <Jest />
      <Linux />
      <Prisma />
    </div>
    <div class="flex-center">
      <p class="text-neutral-400">And many more...</p>
    </div>
  </div>
</div>
