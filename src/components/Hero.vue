<template>
    <div class=jumbotron>
        <div class="text">
        <h2>Sono Denis Paul</h2>
        <p>Ed ho appena iniziato a usare Vue CLI</p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Hero'
}
</script>

<style>
    * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
    }
    .jumbotron{
        display: flex;
        justify-content: center;
        align-items: center;
        width: 100%;
        height: 80vh;
        margin-top: 20px;
        background-image: url('../assets/Programmazione.jpg');
        background-position: center;
        background-size: cover;
    }

    .text {
        display: inline-block;
        padding: 20px;
        border-radius: 15px;
        background-color: rgba(0, 0, 0, .5);
        color: white;
    }
</style>