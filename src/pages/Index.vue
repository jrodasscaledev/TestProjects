<template>
  <q-page class="flex flex-center">
    <div class="q-pa-md">
      <div class="row q-pt-md">Phrase for Success: {{ $t('success') }}</div>
      <div class="row q-pt-md">Phrase for Failure: {{ $t('failed') }}</div>
      <div class="row q-pt-md">Current Language: {{ $i18n.locale }}</div>
    </div>
  </q-page>
</template>

<script>
export default {
  name: 'PageIndex'
}
</script>
