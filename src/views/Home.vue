<template>
      <div class="mx-auto max-w-7xl pt-10 pb-24 sm:pb-32 lg:grid lg:grid-cols-2 lg:gap-x-8 lg:py-20 lg:px-8">
        <div class="px-6 lg:px-0 lg:pt-4">
          <div class="mx-auto max-w-2xl">
            <div class="max-w-lg">
              <div class="mt-24 sm:mt-32 lg:mt-16">
              </div>
              <h1 class="mt-10 text-4xl font-bold tracking-tight text-gray-900 sm:text-6xl">Supercharge your Online Presence</h1>
              <p class="mt-6 text-lg leading-8 text-gray-600">Welcome to our online digital agency! We specialize in creating and executing innovative digital strategies that help businesses of all sizes reach their full potential online.</p>
              <div class="mt-10 flex items-center gap-x-6">
                <a href="#" class="rounded-md bg-orange-600 px-3.5 py-1.5 text-base font-semibold leading-7 text-white shadow-sm hover:bg-orange-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">Documentation</a>
                <a href="#" class="text-base font-semibold leading-7 text-gray-900">View on GitHub <span aria-hidden="true">→</span></a>
              </div>
            </div>
          </div>
        </div>
        <div class="mt-20 sm:mt-24 md:mx-auto md:max-w-2xl lg:mx-0 lg:mt-0 lg:w-screen">
          <div class="absolute inset-y-0 right-1/2 -z-10 -mr-10 w-[200%] skew-x-[-30deg] bg-white shadow-xl shadow-indigo-600/10 ring-1 ring-indigo-50 md:-mr-20 lg:-mr-36" aria-hidden="true" />
          <div class="shadow-lg md:rounded-3xl">
            <div class="bg-orange-500 [clip-path:inset(0)] md:[clip-path:inset(0_round_theme(borderRadius.3xl))]">
              <div class="absolute -inset-y-px left-1/2 -z-10 ml-10 w-[200%] skew-x-[-30deg] bg-orange-100 opacity-20 ring-1 ring-inset ring-white md:ml-20 lg:ml-36" aria-hidden="true" />
              <div class="relative px-6 pt-8 sm:pt-16 md:pl-16 md:pr-0">
                <div class="mx-auto max-w-2xl md:mx-0 md:max-w-none">
                  <div class="w-screen overflow-hidden rounded-tl-xl bg-gray-900">
                    <div class="flex bg-gray-800/40 ring-1 ring-white/5">
                      <div class="-mb-px flex text-sm font-medium leading-6 text-gray-400">
                        <div class="border-b border-r border-b-white/20 border-r-white/10 bg-white/5 py-2 px-4 text-white">NotificationSetting.jsx</div>
                        <div class="border-r border-gray-600/10 py-2 px-4">App.jsx</div>
                      </div>
                    </div>
                    <div class="px-6 pt-6 pb-14">
                      <!-- Your code example -->
                       Digital marketing is a powerful tool for businesses looking to reach a wider audience and achieve their goals.<br>
                        Whether it's through social media, email campaigns, or SEO, there are many different avenues for promoting your brand online.<br>
                        A successful digital marketing strategy involves creating compelling content, targeting the right audience, and analyzing the results to continually improve.<br>
                        By staying up-to-date with the latest trends and techniques, businesses can stay ahead of the competition and build a strong online presence.<br>
                        With the right approach, digital marketing can be a highly effective way to drive traffic, generate leads, and increase sales.<br>
                        So if you're looking to take your business to the next level, consider investing in a comprehensive digital marketing strategy.<br>

                    </div>
                  </div>
                </div>
                <div class="pointer-events-none absolute inset-0 ring-1 ring-inset ring-black/10 md:rounded-3xl" aria-hidden="true" />
              </div>
            </div>
          </div>
        </div>
      </div>
    
    <feature-section class="-mt-24"/>
    <cta-section/>
</template>

<script>
import featureSection from '../sections/featureSection.vue'
import ctaSection from '../sections/ctaSection.vue'
import bookingModal from '../components/bookingModal.vue'
import LogoCloud from '../sections/logoCloud.vue'


export default {
  components: { 
    featureSection,
    ctaSection, 
    bookingModal,
    LogoCloud,
  },
  data() {
    return {
      isModalVisible: false,
    };
  },
  methods: {
    showModal() {
      this.isModalVisible = true;
    },
    closeModal() {
      this.isModalVisible = false;
    }
  }
  
}
</script>