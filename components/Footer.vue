<template>
<footer class="bg-black text-white pt-12">
  <div class="max-w-6xl mx-auto flex justify-between items-center">
    <div class="w-64">
      <p class="bg-gradient-to-r from-green-300 via-blue-500 to-purple-600 bg-clip-text text-5xl font-extrabold text-transparent">Polkarbon</p><br>
      <p>Polkarbon is an <u>experimental</u> cross-chain dApp created for the <b>Polkadot Hackaton Global Series</b> Europe Edition</p>
    </div>

    <div class="">
      <p>GitHub</p>
      <p>Twitter</p>
    </div>


          <img src="https://www.polkadotglobalseries.com/wp-content/uploads/2022/12/KV-logo.png" class="h-52">

  </div>
  <div class="py-4 mx-auto text-center text-white">
<p class="my-3">handcrafted by <span class="text-green-500 font-bold">@mar1dev</span></p>
  </div>
</footer>

</template>

<script>
export default {
  name: 'FAQ',
  methods: {
    async showMessageFromBackend () {
      try {
        const response = await this.$axios.get('/api/test')
        console.log(response.data)
      } catch (err) {
        console.log(err)
      }
    }
  }
}
</script>
