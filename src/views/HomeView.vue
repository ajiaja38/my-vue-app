<template clas>
  <navbar name="Aji Perdana" />
  <div class="px-4">
    <h1>This is an home page</h1>
    <button
      @click="handleClick"
      class="p-2 bg-green-400 hover:bg-green-300 active:bg-green-200 rounded"
    >
      Klik saya
    </button>
  </div>
</template>

<script>
import NavbarCommonVue from '@/components/navbar/NavbarCommon.vue'

export default {
  components: {
    navbar: NavbarCommonVue
  },
  methods: {
    handleClick() {
      alert('Tombol telah di klik')
    }
  }
}
</script>
