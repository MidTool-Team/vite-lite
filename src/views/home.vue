<script setup lang="ts">
  // This starter template is using Vue 3 <script setup> SFCs
  // Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
  import HelloWorld from '@/components/HelloWorld.vue'

  import { Test } from '@/components/test';

  defineOptions({
    name: 'Home'
  })
  </script>
  
  <template>
    <div flex="~ gap-4">
      <a href="https://vitejs.dev" target="_blank">
        <img src="@/assets/vite.svg" class="logo" alt="Vite logo" />
      </a>
      <a href="https://vuejs.org/" target="_blank">
        <img src="@/assets/vue.svg" class="logo vue" alt="Vue logo" />
      </a>
      <a href="https://element-plus.org/zh-CN/" target="_blank">
        <img src="@/assets/element-plus-logo.svg" class="logo" alt="Element-plus logo" />
      </a>
    </div>
    <Test>
      <div>123</div>
    </Test>
    <HelloWorld msg="Vite + Vue + Element-Plus" />
  </template>
  
  <style lang="scss" scoped>
  .logo {
    height: 10em;
    padding: 1.5em;
    will-change: filter;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .logo.vue:hover {
    filter: drop-shadow(0 0 2em #42b883aa);
  }
  </style>
  