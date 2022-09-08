<script>
    
    //Data
    export let item = {};
</script>

<style>
    .expense-list-item{
        border:1px solid black;
        padding: 5px 5px 5px 50px;
        width: 75%;
        margin: 0 auto;
    }
</style>

<div class="expense-list-item">
    <h3>{item && item.name}</h3>
    <p>{item && item.amount}</p>
</div>