<template>
  <h1>Aqui vai ter um compo da minha-biblioteca</h1>

    <MeuCompo />
</template>

<script>
import MeuCompo from "minha-biblioteca";
export default {
    name: "WithCompo",
    components: {
        MeuCompo,
    },
    data() {
        return {
        };
    },
    methods: {
    },

};
</script>
