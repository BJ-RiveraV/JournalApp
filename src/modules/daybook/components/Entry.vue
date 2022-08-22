<template>
  <div @click="$router.push({ name: 'entry', params: {id:10} })" class="entry-container mb-3 pointer p-2">
     <!-- Titulo -->
     <div class="entry-tittle d-flex">
        <span class="text-success fs-5 fw-bold">15</span>
        <span class="mx-1 fs-5">Julio</span>
        <span class="mx-2 fw-light">2022, jueves</span>
     </div>

    <div class="entry-description">
        Duis qui nisi cupidatat sit esse elit voluptate. Pariatur nisi minim excepteur amet culpa sunt. Quis est excepteur consectetur cillum. Sint veniam dolor ea veniam officia eu sint. Minim aliquip et ullamco ad aliquip dolor qui quis ad. Est tempor dolore quis duis ut ut aliquip laboris mollit est velit dolor veniam.
    </div>

  </div>
</template>

<script>
export default {

}   
</script>

<style lang="scss">
.entry-container{
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;

    &:hover{
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2s all ease-in;
    }
}
.entry-description{
    font-size: 12px;
}
</style>