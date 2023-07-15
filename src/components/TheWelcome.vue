<script setup>
import WelcomeItem from './WelcomeItem.vue'
import VoiceRecognition from './VoiceRecognition.vue';
import CommunityIcon from './icons/IconCommunity.vue'
</script>

<template>
  <div>
    <WelcomeItem>
      <template #icon>
        <CommunityIcon />
      </template>
      <template #heading>Hi eDist, Say something</template>

      <VoiceRecognition />
    </WelcomeItem>
  </div>
</template>
