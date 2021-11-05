<template>
  <section class="bg-gray-100 py-8">
    <div class="container mx-auto flex flex-wrap pt-4 pb-12">
      <h1
        class="w-full my-2 text-5xl font-bold leading-tight text-center text-gray-800 alt-text"
      >
        Built For Any Brand
      </h1>
      <div class="w-full mb-4">
        <div
          class="h-1 mx-auto gradient w-64 opacity-25 my-0 py-0 rounded-t"
        ></div>
      </div>
      <teaser-column :rows="3" action="Action">
        <img
          src="~assets/svg/np_technical-support_4116557_000000.svg"
          alt
          slot="svg"
        />
        <template v-slot:overline>PIM & CMS Integration</template>
        <template v-slot:headline>Automatic Inventory & Pricing</template>
        <template v-slot:content
          >Connect your PIM and CMS, and Poly automates the rest. Create a fully
          managed DTC channel with zero overhead.</template
        >
      </teaser-column>
      <teaser-column :rows="3" action="Action">
        <img src="~assets/svg/np_funnel_4102878_000000.svg" alt slot="svg" />
        <template v-slot:overline>Flexible Analytics</template>
        <template v-slot:headline>Enrich Your Marketing Funnels</template>
        <template v-slot:content
          >Get real conversion data, and augment your existing funnels with
          better insight from what shoppers actually buy.</template
        >
      </teaser-column>
      <teaser-column :rows="3" action="Action">
        <img src="~assets/svg/np_shipping_1968202_000000.svg" alt slot="svg" />
        <template v-slot:overline>No-Hassle Fulfillment</template>
        <template v-slot:headline>We Handle the Shipping Lifecycle</template>
        <template v-slot:content
          >Poly is a fully managed solution that takes care of shipment
          tracking, returns, chargebacks, fraud, and support.</template
        >
      </teaser-column>
    </div>
  </section>
</template>

<script>
import TeaserColumn from '@/components/TeaserColumn'

export default {
  name: 'Teasers',
  components: {
    'teaser-column': TeaserColumn
  }
}
</script>
