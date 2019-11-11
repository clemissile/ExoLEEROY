<template>
    <form @submit="subscribe">
        <input type="email" id="email" name="email" v-model="email" />
        <button type="submit">Submit</button>
    </form>
</template>

<script>
export default {
    name: "SubscriptionForm",
    data() {
        return {
            email: ""
        };
    },
    methods: {
        subscribe: function(e) {}
    }
};
</script>

<style lang="scss">
#subscription-form {
    color: red;
}
</style>
