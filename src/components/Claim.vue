<template>
    <div class="claimWrapper">
        <h1 class="claim">SPACER</h1>
        <p class="subclaim">Begin your journey. Explore and more</p>
        <p class="subclaim">Type anything space related here.</p>
    </div>
</template>

<script>
export default {
  name: 'Claim',
};
</script>

<style lang="scss" scoped>
    .claimWrapper{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        text-align: center;
    }

    .claim{
        font-size: 50px;
        margin: 0;
    }

    .subclaim {
        font-size: 13px;
        margin: 20px 0 0 0 ;
    }
</style>
