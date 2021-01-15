<template>
    <mdb-btn color="elegant" :type="type" >
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
