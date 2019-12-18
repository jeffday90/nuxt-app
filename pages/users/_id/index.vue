

<template>
    <h1>This is {{ $route.params.id }}</h1>
</template>

<script>
export default {
    validate (data){
        console.log(data);
        return /^\d+$/.test(data.params.id);
    }
}
</script>