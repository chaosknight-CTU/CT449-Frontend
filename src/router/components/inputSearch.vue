<script>

export default {
    props: {
        modelValue: { type: String, default: ""},
    },
    emits: ["submit", "update:modelValue"],
    methods: {
        updateModelValue(e) {
            this.$emit("update:modelValue", e.target.value);
        },

        submit() {
            this.$emit("submit");
        },
    },
};



</script>

<template>
    <div class="input-group">
        
    </div>

</template>
