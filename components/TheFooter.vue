<template>
  <footer class="bg-white">
    <div class="container mx-auto px-8">
      <div class="w-full flex flex-col md:flex-row py-6">
        <div class="flex-1 mb-6">
          <logo />
        </div>

        <div class="flex-1">
          <p class="uppercase text-gray-500 md:mb-6">Links</p>
          <ul class="list-reset mb-6">
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <a
                href="#"
                class="no-underline hover:underline text-gray-800 hover:text-orange-500"
                onclick="
              Calendly.initPopupWidget({
                url: 'https://calendly.com/buywithpoly/intro'
              })
              return false
            "
                >Schedule a Demo</a
              >
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <a
                href="https://docs.polytopal.ai/"
                class="no-underline hover:underline text-gray-800 hover:text-orange-500"
                >Documentation</a
              >
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <a
                href="mailto:support@polytopal.ai"
                class="no-underline hover:underline text-gray-800 hover:text-orange-500"
                >Support</a
              >
            </li>
          </ul>
        </div>
        <div class="flex-1">
          <p class="uppercase text-gray-500 md:mb-6">Social</p>
          <ul class="list-reset mb-6">
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <a
                href="http://facebook.com/polytopalAI"
                class="no-underline hover:underline text-gray-800 hover:text-orange-500"
                >Facebook</a
              >
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <a
                href="https://www.linkedin.com/company/polytopal"
                class="no-underline hover:underline text-gray-800 hover:text-orange-500"
                >Linkedin</a
              >
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <a
                href="http://twitter.com/polytopal_ai"
                class="no-underline hover:underline text-gray-800 hover:text-orange-500"
                >Twitter</a
              >
            </li>
          </ul>
        </div>
        <div class="flex-1">
          <p class="uppercase text-gray-500 md:mb-6">Company</p>
          <ul class="list-reset mb-6">
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <a
                href="https://polytopal.ai/"
                class="no-underline hover:underline text-gray-800 hover:text-orange-500"
                >Polytopal</a
              >
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <a
                href="mailto:hello@polytopal.ai"
                class="no-underline hover:underline text-gray-800 hover:text-orange-500"
                >Contact Us</a
              >
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
import Logo from '@/components/Logo'

export default {
  name: 'TheFooter',
  components: {
    logo: Logo
  }
}
</script>
