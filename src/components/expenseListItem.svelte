<script>
    //Data
    export let item = {};
    let open = false;

    //Function
    const toggle = () => {
        open = !open
    }

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
    {#if open}<p class="expense-item-amount">${item && item.amount}</p>{/if}
    <button on:click={toggle}>Down Arrow</button>
</div>