<script>
export default {
    props: ['hero'],
    components: {
    },
    data() {
    },
    methods: {
    },
    computed: {
    },
    mounted() {
    }
}
</script>

<template>
    <h2>
        {{ hero.name }}
    </h2>
    <dl>
        <dt>Health</dt>
        <dd>{{ hero.health }}</dd>
        <dt>Attack</dt>
        <dd>{{ hero.attack }}</dd>
        <dt>Defense</dt>
        <dd>{{ hero.defense }}</dd>
        <dt>Evasion</dt>
        <dd>{{ hero.evasion }}</dd>
    </dl>
</template>