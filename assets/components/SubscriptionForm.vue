<template>
    <form @submit.prevent="subscribe">
        <input class="m-0 p-2" type="email" id="email" name="email" v-model="email" placeholder="Votre Courriel" />
        <button class="p-2" type="submit">S'inscrire <i class="fas fa-plus"></i></button>
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
            subscribe: function(e) {
                (this.email) ? console.log("Inscprition réussie ! Email : ", this.email) : "";
            }
        }
    };
</script>

<style lang="scss">
    @import '../style.scss';

    #subscription-form {
        color: red;
    }

    button {
        margin-left: -0.5em;
        background: {
            color: $berry;
        };
        border: {
            style: none;
        };
        color: #ffffff;
     }

    input {
        /*display: inline-block;*/
        border: {
            style: none;
        };
    }
</style>
