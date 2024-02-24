<script>
  import favicon from '@/public/favicon-colored.svg';

  import lineBlack from '@/public/icons/line-black.svg';
  import areaBlack from '@/public/icons/area-black.svg';
  import bubbleBlack from '@/public/icons/bubble-black.svg';
  import barBlack from '@/public/icons/bar-black.svg';
  import histogramBlack from '@/public/icons/histogram-black.svg';
  import candleBlack from '@/public/icons/candle-black.svg';
  import pieBlack from '@/public/icons/pie-black.svg';
  import doughnutBlack from '@/public/icons/doughnut-black.svg';
  import treemapBlack from '@/public/icons/treemap-black.svg';
  import heatmapBlack from '@/public/icons/heatmap-black.svg';
  import networkBlack from '@/public/icons/network-black.svg';
  import spiderBlack from '@/public/icons/spider-black.svg';

  import lineLight from '@/public/icons/line-light.svg';
  import areaLight from '@/public/icons/area-light.svg';
  import bubbleLight from '@/public/icons/bubble-light.svg';
  import barLight from '@/public/icons/bar-light.svg';
  import histogramLight from '@/public/icons/histogram-light.svg';
  import candleLight from '@/public/icons/candle-light.svg';
  import pieLight from '@/public/icons/pie-light.svg';
  import doughnutLight from '@/public/icons/doughnut-light.svg';
  import treemapLight from '@/public/icons/treemap-light.svg';
  import heatmapLight from '@/public/icons/heatmap-light.svg';
  import networkLight from '@/public/icons/network-light.svg';
  import spiderLight from '@/public/icons/spider-light.svg';

  import lineColored from '@/public/icons/line-colored.svg';
  import areaColored from '@/public/icons/area-colored.svg';
  import bubbleColored from '@/public/icons/bubble-colored.svg';
  import barColored from '@/public/icons/bar-colored.svg';
  import histogramColored from '@/public/icons/histogram-colored.svg';
  import candleColored from '@/public/icons/candle-colored.svg';
  import pieColored from '@/public/icons/pie-colored.svg';
  import doughnutColored from '@/public/icons/doughnut-colored.svg';
  import treemapColored from '@/public/icons/treemap-colored.svg';
  import heatmapColored from '@/public/icons/heatmap-colored.svg';
  import networkColored from '@/public/icons/network-colored.svg';
  import spiderColored from '@/public/icons/spider-colored.svg';

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
      <a href="#" target="_blank">Download</a>
      <a href="https://github.com/slaylines/sparkle-icons" target="_blank">Github</a>
    </nav>
  </header>

  <div class="max-w-[800px] mt-[8.5rem] sm:mt-[4.5rem]">
    <h2 class="w-full text-center mb-2 pt-4 md:pt-8">Basic Icons</h2>
    <div class="flex flex-wrap justify-center">
      {#each basicIcons as icon}
        <div class="w-[100px] h-[100px] flex justify-center items-center m-3 bg-gray-100 rounded">
          <img src={icon} />
        </div>
      {/each}
    </div>
    <h2 class="w-full text-center mt-8 mb-2">Light Icons</h2>
    <div class="flex flex-wrap justify-center">
      {#each lightIcons as icon}
        <div class="w-[100px] h-[100px] flex justify-center items-center m-3 bg-gray-100 rounded">
          <img src={icon} />
        </div>
      {/each}
    </div>
    <h2 class="w-full text-center mt-8 mb-2">Colored Icons</h2>
    <div class="flex flex-wrap justify-center pb-8">
      {#each colorIcons as icon}
        <div class="w-[100px] h-[100px] flex justify-center items-center m-3 bg-gray-100 rounded">
          <img src={icon} />
        </div>
      {/each}
    </div>
  </div>
</main>
