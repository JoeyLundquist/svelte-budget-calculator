<script>
    //Data
    import expenses from '../sampleData/sampleExpenses'
    let sum = 0;
    expenses.map(e =>sum += e.amount)
</script>
<style>
    .total-expense-amount{
        color: green;
    }
</style>

<h3>Total Expenses</h3>
<p class="total-expense-amount">${sum}</p>