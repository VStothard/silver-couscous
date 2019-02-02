<template>
  <div>
    <ColorPanels class="fixed w-full z-0"></ColorPanels>
    <div class="relative z-10">
      <Hero></Hero>
      <Navigation></Navigation>
      <IntroBlock></IntroBlock>
      <FullWidthBanner></FullWidthBanner>
    </div>
  </div>
</template>

<script>
export default {
  layout: "home"
};
</script>