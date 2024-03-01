<script>
  import favicon from '/favicon-colored.svg';

  import lineBlack from '/icons/line-black.svg';
  import areaBlack from '/icons/area-black.svg';
  import bubbleBlack from '/icons/bubble-black.svg';
  import barBlack from '/icons/bar-black.svg';
  import histogramBlack from '/icons/histogram-black.svg';
  import candleBlack from '/icons/candle-black.svg';
  import pieBlack from '/icons/pie-black.svg';
  import doughnutBlack from '/icons/doughnut-black.svg';
  import treemapBlack from '/icons/treemap-black.svg';
  import heatmapBlack from '/icons/heatmap-black.svg';
  import networkBlack from '/icons/network-black.svg';
  import spiderBlack from '/icons/spider-black.svg';

  import lineLight from '/icons/line-light.svg';
  import areaLight from '/icons/area-light.svg';
  import bubbleLight from '/icons/bubble-light.svg';
  import barLight from '/icons/bar-light.svg';
  import histogramLight from '/icons/histogram-light.svg';
  import candleLight from '/icons/candle-light.svg';
  import pieLight from '/icons/pie-light.svg';
  import doughnutLight from '/icons/doughnut-light.svg';
  import treemapLight from '/icons/treemap-light.svg';
  import heatmapLight from '/icons/heatmap-light.svg';
  import networkLight from '/icons/network-light.svg';
  import spiderLight from '/icons/spider-light.svg';

  import lineColored from '/icons/line-colored.svg';
  import areaColored from '/icons/area-colored.svg';
  import bubbleColored from '/icons/bubble-colored.svg';
  import barColored from '/icons/bar-colored.svg';
  import histogramColored from '/icons/histogram-colored.svg';
  import candleColored from '/icons/candle-colored.svg';
  import pieColored from '/icons/pie-colored.svg';
  import doughnutColored from '/icons/doughnut-colored.svg';
  import treemapColored from '/icons/treemap-colored.svg';
  import heatmapColored from '/icons/heatmap-colored.svg';
  import networkColored from '/icons/network-colored.svg';
  import spiderColored from '/icons/spider-colored.svg';

  const basicIcons = [
    lineBlack, areaBlack, bubbleBlack,
    barBlack, histogramBlack, candleBlack,
    pieBlack, doughnutBlack, treemapBlack,
    heatmapBlack, networkBlack, spiderBlack,
  ];
  const lightIcons = [
    lineLight, areaLight, bubbleLight,
    barLight, histogramLight, candleLight,
    pieLight, doughnutLight, treemapLight,
    heatmapLight, networkLight, spiderLight,
  ];
  const colorIcons = [
    lineColored, areaColored, bubbleColored,
    barColored, histogramColored, candleColored,
    pieColored, doughnutColored, treemapColored,
    heatmapColored, networkColored, spiderColored,
  ];
</script>

<main class="flex justify-center container mx-auto px-6 sm:px-8 lg:px-10">
  <header class="fixed top-0 left-0 z-50 w-screen h-fit pb-4 pt-8 sm:pt-4
                 px-6 sm:px-8 lg:px-10 bg-white border-b border-gray-200">
    <div class="container mx-auto flex items-center justify-center flex-col
                sm:items-end sm:justify-between sm:flex-row">
    <h1 class="flex mb-4 sm:mb-2">
      <img class="-mb-2 mr-2" src={favicon} /> Sparkle Icons
    </h1>
    <nav class="flex gap-6 md:gap-8 lg:gap-10 mb-2 text-md">
      <a href="https://github.com/slaylines/sparkle-icons/blob/master/README.md" target="_blank">
        How to Use
      </a>
      <a href="/sparkle-icons.zip" download>Download</a>
      <a href="https://github.com/slaylines/sparkle-icons" target="_blank">Github</a>
    </nav>
  </header>

  <div class="max-w-[800px] mt-[8.5rem] sm:mt-[4.5rem]">
    <h2 class="w-full text-center mb-2 pt-4 md:pt-8">Basic Set</h2>
    <div class="flex flex-wrap justify-center">
      {#each basicIcons as icon}
        <div class="w-[100px] h-[100px] flex justify-center items-center m-3 bg-gray-100 rounded">
          <img src={icon} />
        </div>
      {/each}
    </div>
    <h2 class="w-full text-center mt-8 mb-2">Light Set</h2>
    <div class="flex flex-wrap justify-center">
      {#each lightIcons as icon}
        <div class="w-[100px] h-[100px] flex justify-center items-center m-3 bg-gray-100 rounded">
          <img src={icon} />
        </div>
      {/each}
    </div>
    <h2 class="w-full text-center mt-8 mb-2">Colored Set</h2>
    <div class="flex flex-wrap justify-center pb-8">
      {#each colorIcons as icon}
        <div class="w-[100px] h-[100px] flex justify-center items-center m-3 bg-gray-100 rounded">
          <img src={icon} />
        </div>
      {/each}
    </div>
  </div>
</main>
