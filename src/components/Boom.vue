<template>
    <div class="Boom">
        <h1>{{ age }}{{ nickname }}</h1>
    </div>
</template>

<script>
export default {
    name: 'Boom',
    props: {
        age: Number,
        nickname: String
    }
}
</script>