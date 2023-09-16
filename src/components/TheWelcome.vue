<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Catch up with neighbors.</template>

    
    Summer is coming to an end, so let's catch up on what we've all been up to.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Delicious Pour Over Coffee</template>

   Bring your own mugs, and we will keep the coffee flowing.
  </WelcomeItem>
  <!-- <br /> -->

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Croissants</template>

    We have them! Enjoy a light breakfast.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Read the Seattle Times & The Economist</template>

    If you subscribe to any particular magazines, bring them over too!
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Rain or Shine</template>

   Even if it's raining, we will be undeterred - we will either be outside under our maple tree, or bring the party indoors.
  </WelcomeItem>
</template>
