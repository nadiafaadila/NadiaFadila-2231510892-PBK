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
      <ToolingIcon />
    </template>
    <template #heading>History</template>

    SMAN 1 BANGKINANG KOTA (2019-2022)

    <br />

  </WelcomeItem>


  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact Person</template>

    Email: nadiafadila@student.uir.ac.id <br>
    Instagram : <a href="instagram.com/nadiafaadila">@nadiafaadila</a> <br>
  
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Hobby</template>

    1. Travelling <br>
    2. Singing <br>
    3. Watching Movies
  </WelcomeItem>
</template>