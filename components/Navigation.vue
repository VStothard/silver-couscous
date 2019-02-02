<template>
  <div :class="`${bgColorClass} w-full border-t-4 border-peach-500`">
    <PageWrapper>
      <ul class="list-reset flex justify-end text-white">
        <li class="p-4">one</li>
        <li class="p-4">two</li>
        <li class="p-4">three</li>
      </ul>
    </PageWrapper>
  </div>
</template>
<script>
export default {
  props: {
    bgColor: {
      type: String,
      default: "peach"
    }
  },
  computed: {
    bgColorClass() {
      switch (this.bgColor) {
        case "slate": {
          return "bg-slate-500";
        }
        case "peach": {
          return "bg-peach-500";
        }
      }
      return bgColor;
    }
  }
};
</script>

