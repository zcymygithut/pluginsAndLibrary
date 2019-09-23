<template>
    <div>
        <router-link to="/echarts/line">折线图</router-link> |
        <router-link to="/echarts/bar">柱形图</router-link>
        <router-view/>
    </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component({
    components: {
       
    }
})
export default class Echarts extends Vue {
    mounted() {
        // console.log(111111)
    }
}
</script>