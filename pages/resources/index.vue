<template>
  <AppSectionWrapper>
    <h1
      class="page-heading text-center"
      v-text="'Web Accessibility Resources'"
    />
    <div class="max-w-7xl">
      <div class="flex flex-col items-center mb-8">
        <h2
          class="page-subheading"
          v-text="'Coming soon!'"
        />
        <SvgComingSoon class="w-full h-96 mt-6 mx-auto" />
      </div>
    </div>
  </AppSectionWrapper>
</template>

<script type="text/babel">
import AppSectionWrapper from '@/components/global/AppSectionWrapper'
import SvgComingSoon from '@/components/svg/illustrations/SvgComingSoon'

export default {
  name: 'ResourcesPage',
  components: {
    SvgComingSoon,
    AppSectionWrapper,
  },
  head() {
    return {
      title: 'Resources | Accessibility Reference',
    }
  },
}
</script>
