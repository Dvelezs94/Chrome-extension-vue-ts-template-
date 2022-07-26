<script>
import CustomComponent from './components/CustomComponent.vue'

export default ({
    name: 'App',
    data() {
        return {
            title: 'Custom popup'
        }
    },
    components: {
        CustomComponent
    }
})
</script>


<template>
    <h1>{{title}}</h1>
    <CustomComponent />
</template>

