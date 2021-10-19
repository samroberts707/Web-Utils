<template>
    <div class="component json-to-csv">
        <div class="header">
            <h1>JSON to CSV</h1>
        </div>
        <div class="">
            <label for="json_input">Paste your JSON here</label>
            <textarea rows="10" id="json_input" name="json_input"></textarea>
            <button class="cyan">Convert</button>
        </div>
    </div>
</template>
<script>
export default {
    name: 'json-to-csv',
    head: {
        title: 'JSON to CSV - Web Utils'
    }
}
</script>
<style lang="scss" scoped>
    
</style>