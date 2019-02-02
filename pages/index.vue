<template>
  <div>
    <ColorPanels class="fixed w-full z-0"></ColorPanels>
    <div class="relative z-10">
      <Hero></Hero>
      <Navigation bg-color="slate"></Navigation>
      <IntroBlock></IntroBlock>
      <PageWrapper>
        <div>
          <p>Home page</p>
          <p>home</p>Backrgound panel component (absolute pos)
          page wrapper
          grid col
        </div>
      </PageWrapper>
    </div>
  </div>
</template>

<script>
export default {
  layout: "home"
};
</script>