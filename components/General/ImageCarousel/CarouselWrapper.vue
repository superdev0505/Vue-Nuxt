<template>
    <div>
         <image-carousel  :images="images"/>
    </div>
  


</template>

<script>
import ImageCarousel from '@/components/General/ImageCarousel/CarouselFunctions/ImageCarousel';


export default {
    name: 'CarouselWrapper',
    props: {
        images: {
        type: Array
        }
    },
    components: {
        ImageCarousel,
  }
}
</script>

<style>

</style>
