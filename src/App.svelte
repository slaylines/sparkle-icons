<script>
</script>

<main class="w-full container mx-auto">
  <header class="fixed top-0 left-0  w-screen h-fit pt-8 pb-4 sm:pt-4
                 bg-white border-b border-gray-200">
    <div class="container mx-auto flex items-center justify-center flex-col
                sm:items-end sm:justify-between sm:flex-row">
    <h1 class="mb-4 sm:mb-2">✨ Sparkle Icons</h1>
    <nav class="flex gap-6 md:gap-8 lg:gap-10 mb-2 text-md">
      <a href="#">How to Use</a>
      <a href="#">Download</a>
      <a href="#">Github</a>
    </nav>
  </header>

  <div class="flex w-full mt-[160px] sm:mt-[120px] -ml-2">
    <div class="flex flex-wrap justify-center md:justify-start w-full md:w-2/3">
      {#each {length: 48} as _, i}
        <div class="w-[180px] h-[180px] m-2 bg-gray-200 rounded" />
      {/each}
    </div>
    <div class="w-full h-fit md:w-1/3 sticky top-[160px] sm:top-[120px] overflow-auto">
      <h2>Settings</h2>
      <div class="mt-4">
        Size: <input type="text" value="32"
          class="w-16 h-8 ml-2 px-2 py-1 text-right rounded border border-gray-400 hover:border-gray-600 outline-none" /> px
      </div>
      <div class="mt-4">
        <div class="mb-2">Colors:</div>
        <span class="inline-block w-12 h-12 mr-2 mb-2 bg-white border border-gray-600 rounded" />
        <span class="inline-block w-12 h-12 mr-2 mb-2 bg-[#333] border border-gray-600 rounded" />
        <span class="inline-block w-12 h-12 mr-2 mb-2 bg-[#4E79A7] border border-gray-600 rounded" />
        <span class="inline-block w-12 h-12 mr-2 mb-2 bg-[#E15759] border border-gray-600 rounded" />
        <span class="inline-block w-12 h-12 mr-2 mb-2 bg-[#F28E2C] border border-gray-600 rounded" />
      </div>
    </div>
  </div>
</main>
