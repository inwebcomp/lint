<template>
    <div>
        <button
            data-attr
            data-another
            class="some"
            @click="() => $emit('click')"
        >
            click
        </button>
    </div>
</template>

<script setup lang="ts">
import {
    defineEmits,
    defineOptions,
    watch,
    ref,
    reactive,
    toRef,
    toRefs,
    toValue,
} from 'vue'

defineOptions({
    name: 'App',
})

defineEmits(['click'])

//

const a = 1

function log(a: number) {
    //
}

if (true) { log(1) }

if (true) { log(1) }

if (true) {
    log(1)
}
</script>