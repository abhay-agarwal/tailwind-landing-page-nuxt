<template>
  <section class="bg-white border-b py-8">
    <div class="container max-w-5xl mx-auto m-8 z-50">
      <h1
        class="w-full my-2 text-5xl font-bold leading-tight text-center text-gray-800 alt-text alt-text-shadow"
      >
        Create a DTC Channel From Any Inventory
      </h1>
      <div class="w-full mb-4">
        <div
          class="h-1 mx-auto gradient w-64 opacity-25 my-0 py-0 rounded-t"
        ></div>
      </div>
      <feature-right
        headline="Multi-Channel Fulfillment"
        content="Poly lets you take orders online and fulfill from any inventory, including Amazon, retail, and 3PL. Our algorithm automatically selects the best option, maximizing margins and ensuring a happy shopper."
      >
        <img
          src="~assets/img/connected-world.svg"
          alt
          slot="svg"
          style="width:80%;"
        />
      </feature-right>
      <feature-left
        headline="Native Checkout Experience"
        content="Create a fully native checkout experience with apple pay, subscriptions, loyalty, and more. Customers can buy instantly on any device or machine, as if they were on a full e-commerce site."
      >
        <img src="~assets/img/travel-booking.svg" alt slot="svg" />
      </feature-left>
      <feature-right
        headline="Rich Consumer Data"
        content="Understand the full consumer journey, including referrals, conversions, abandoned carts, and social marketing, to checkout and beyond."
      >
        <img
          src="~assets/img/undraw_control_panel_re_y3ar-2.svg"
          alt
          slot="svg"
          style="width:80%;"
        />
      </feature-right>
      <feature-left
        headline="PCI And SOC II Compliance"
        content="Our infrastructure is fully audited, secure, and battle-tested. Don't worry, we know our way around complex enterprise compliance processes."
      >
        <img
          src="~assets/img/undraw_online_payments_re_y8f2.svg"
          alt
          slot="svg"
          style="width:80%;"
        />
      </feature-left>
    </div>
  </section>
</template>

<script>
import FeatureRight from '@/components/FeatureRight'
import FeatureLeft from '@/components/FeatureLeft'

export default {
  name: 'Features',
  components: {
    'feature-right': FeatureRight,
    'feature-left': FeatureLeft
  }
}
</script>
