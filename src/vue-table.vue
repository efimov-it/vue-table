<template>
    <table>
        <tr>
            <th>123</th>
            <th>123</th>
        </tr>
        <tr>
            <td>Lorem ipsum</td>
            <td>Ipsum lorem</td>
        </tr>
    </table>
</template>

<script>
export default {
    
}
</script>

<style lang="less" scoped>
table {
    width: 100%;
    border-radius: 3px;
    border-collapse: collapse;
    border: 1px solid #dedede;;

    th {
        text-align: left;
    }

    th, td {
        padding: 10px;
    }

    th, tr:not(:last-child) {
        border-bottom: 1px solid #dedede;
    }
}
</style>