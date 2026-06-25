<script setup lang="ts">
import DanraKu from './DanraKu.vue'
import GaZou from './GaZou.vue'
</script>

<template>
  <div class="maincontent">
    <div class="subcontent">
        Title
        <DanraKu/>
        <div class="subsubcontent">
            <GaZou color="red"/>
            <GaZou color="lime"/>
            <GaZou color="blue"/>
            
        </div>
    </div>
  </div>
</template>

<style scoped>
.maincontent{
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    border :1px solid blue;
    width: 100%;
}
.subcontent{
    width: 850px;
    height: 400px !important;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    border :1px solid red;
    font-size: 40px;
}

.subsubcontent{
    width: 100%;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}

</style>
