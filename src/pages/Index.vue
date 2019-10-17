<template>
  <q-page class="flex flex-center">
    <avatar-uploader/>
  </q-page>
</template>

<script>
import AvatarUploader from 'src/components/AvatarUploader.vue';

export default {
  name: 'PageIndex',
  components: { AvatarUploader },
};
</script>
