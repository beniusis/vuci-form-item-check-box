<template>
  <vuci-form-item-template v-bind="VuciFormItemTemplateProps">
    <a-checkbox v-model="model"/>
  </vuci-form-item-template>
</template>

<script>
import VuciFormItemMixin from './VuciFormItemMixin'

export default {
  name: 'VuciFormItemCheckBox',
  mixins: [VuciFormItemMixin]
}
</script>
