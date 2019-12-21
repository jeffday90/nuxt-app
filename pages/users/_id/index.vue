

<template>
    <div>
        <Header />
        <h1>This is {{ $route.params.id }}</h1>
    </div>
</template>

<script>

export default {
    validate (data){
        console.log(data);
        return /^\d+$/.test(data.params.id);
    },
    layout: 'users',
}
</script>