<script>
    //Data
    import expenses from '../sampleData/sampleExpenses'
    let sum = 0;
    
</script>

<h3>Total Expenses</h3>
<p>${expenses.map(e =>sum += e.amount)}</p>