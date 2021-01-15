<template>
    <mdb-btn color="deep-orange" :type="type" >
        <slot></slot>
    </mdb-btn>
</template>

<script>
    export default {
        props: {
            type: {
                type: String,
                default: 'submit',
            },
        }
    }
</script>
