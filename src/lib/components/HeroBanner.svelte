<!-- integrated HeroBanner by Svelte Splide https://splidejs.com/integration/svelte-splide/ -->
<script lang="ts">
    import { Splide, SplideSlide } from '@splidejs/svelte-splide';
    // default theme
    import '@splidejs/svelte-splide/css';
</script>
<Splide class="flex bg-red-600 justify-center rounded-lg" 
  options={ {
    rewind: true,
    rewindByDrag: true,
    width: '80%',
    autoplay: true,
    interval: 7000,
    pauseOnHover: true,
    pagination: false,
    arrows: true,
    heightRatio: 0.6,

  } }
>
    <SplideSlide>
        <img class="w-full h-full rounded-lg" src="image1.png" alt="students in uniform" />
    </SplideSlide>
    <SplideSlide>
        <img class="w-full h-full rounded-lg" src="image 2.png" alt="students in uniform" />
    </SplideSlide>
    <SplideSlide>
        <img class="w-full h-full rounded-lg" src="image 3.png" alt="students in uniform" />
    </SplideSlide>
    <SplideSlide>
        <img class="w-full h-full rounded-lg" src="image 4.png" alt="students in uniform" />
    </SplideSlide>
</Splide>
