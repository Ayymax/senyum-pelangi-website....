<script>
  import { Heading, P, Button } from 'flowbite-svelte';
  import { ArrowRightOutline } from 'flowbite-svelte-icons';
</script>

<div class = "pt-20 md:pt-32 pb-24">
  <div class="flex flex-col-reverse items-center md:flex-row mx-auto container md:space-x-20 pl-10 pr-10 lg:pl-20 lg:pr-20 ">
    <div class="flex flex-col w-full align-center justify-center items-center  md:w-160 lg:w-200 md:items-start">
      <Heading tag="h1" class="mb-4" customSize="text-center md:text-left text-4xl font-extrabold  md:text-5xl lg:text-6xl lg:mb-4">Welcome to Senyum Pelangi</Heading>
      <P class="mb-6 text-center md:text-left text-xl lg:text-2xl dark:text-gray-400 lg:mb-8">Mari mendukung kami dalam perjuangan untuk senyuman anak-anak</P>
      <Button href="https://wa.me/6281222213595" class="w-[10rem]">
        Hubungi kami
        <ArrowRightOutline class="w-3.5 h-3.5 ml-2" />
      </Button>
    </div>
    <img src="/Hero.jpeg" alt="Pelangi-Photo" class="mb-10 h-[14rem] w-[21rem] lg:h-[20rem] lg:w-[30rem]"> 
  </div>
</div>
