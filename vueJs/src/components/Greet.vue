<template>
     <h2> Hello {{name}} as {{heroName}}!</h2>
</template>

<script>

    export default{
        name: "Greet",
        props: ["name", "heroName"]
    }

</script>