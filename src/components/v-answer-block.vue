<template>
    <div id="v-answer-block">
        <h2>{{ text }}</h2>
    </div>
</template>

<script>
export default {
    name: 'v-answer-block',
    props: {
        text: {
            type: String,
            default() {
                return '';
            },
        },
    },
};
</script>

<style>
#v-answer-block {
    width: 80%;
    border: 5px solid rgb(203, 224, 11);
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 25px;
}

h2 {
    font-size: 38px;
    text-transform: uppercase;
    margin: 5px;
}
</style>
