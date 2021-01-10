<template>
    <div class="boom">
        <h1>{{ age }}{{ int }}</h1>
    </div>
</template>

<script>
export default {
    name: "boom",
    props: {
        age: int,
        nickname: String
    }
}
</script>