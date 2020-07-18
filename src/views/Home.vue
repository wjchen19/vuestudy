<template>
  <div>
    主页 登录页面
    <div @click='jump'>
      点我
    </div>
    <div>{{moduleName}}</div>
  </div>
</template>
<script>
  import {
    ref,
    reactive
  } from '@vue/composition-api'
  export default {
    name: 'Home',
    components: {},
    setup() {
      const moduleName = ref(null)
      moduleName.value = 'dengsadljgaslfas'
      return {
        moduleName
      }
    },
    methods: {
      jump() {
        console.log('你个憨批')
      }
    }
  }
</script>