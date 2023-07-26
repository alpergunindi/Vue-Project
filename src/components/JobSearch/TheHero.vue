<template>
  <main>
    <section class="flex h-screen flex-col pb-20 pt-10">
      <div class="grid grid-cols-12">
        <div class="col-span-1 col-start-1"></div>

        <div class="col-span-5 col-start-2"><the-headline /><job-search-form /></div>

        <div class="self-center- col-span-5 col-start-7 justify-self-center">
          <img
            class="border- rounded-s-full border-r-8 border-brand-blue-2"
            src="https://fjwp.s3.amazonaws.com/blog/wp-content/uploads/2021/04/29101948/change-careers-1024x512.png"
          />
        </div>

        <div class="col-span-1 col-start-12"></div>
      </div>
    </section>
  </main>
</template>

<script>
import TheHeadline from '@/components/JobSearch/TheHeadline.vue'
import JobSearchForm from '@/components/JobSearch/JobSearchForm.vue'

export default {
  name: 'TheHero',
  components: {
    TheHeadline,
    JobSearchForm
  }
}
</script>
