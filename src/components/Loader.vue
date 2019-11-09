<template>
    <div class="lds-dual-ring"></div>
</template>

<script>
	export default {
		name: "Loader"
	}
</script>

<style scoped>
    .lds-dual-ring {
        display: inline-block;
        width: 64px;
        height: 64px;
    }
    .lds-dual-ring:after {
        content: " ";
        display: block;
        width: 46px;
        height: 46px;
        margin: 1px;
        border-radius: 50%;
        border: 5px solid #cef;
        border-color: #cef transparent #cef transparent;
        animation: lds-dual-ring 1.2s linear infinite;
    }
</style>
