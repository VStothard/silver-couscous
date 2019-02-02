<template>
  <div class="relative">
    <div class="absolute z-0 flex no-wrap w-full">
      <div class="w-1/2 h-screen bg-slate-500"></div>
      <div class="w-1/2 h-screen bg-peach-500 bg-profile bg-cover"></div>
    </div>
    <PageWrapper class="relative z-10 w-full">
      <div class="flex no-wrap">
        <div class="w-1/2 h-screen flex flex-col justify-center text-white">
          <div>V</div>
          <div>
            <h2>Hey, I’m Verity,</h2>
            <p>Front end developer, online teacher and dog mumma to @alfiemakesfriends. Based in sunny Sydney, Australia.</p>
          </div>
        </div>
        <div class="w-1/2 h-screen"></div>
      </div>
    </PageWrapper>
  </div>
</template>
<script>
export default {};
</script>

<style>
.bg-profile {
  background-image: url("~assets/img/verity-profile.jpg");
}
</style>
