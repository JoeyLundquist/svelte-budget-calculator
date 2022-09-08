<script>
    // Components
    import Title from '../components/Title.svelte'
    import ExpenseListItem from '../components/ExpenseListItem.svelte';

    //Data
    import expenses from '../sampleData/sampleExpenses'

    // Variable
    let expensesList = [...expenses]
</script>


<Title title="Expenses" />
<ul>
    {#each expensesList as item}
        <ExpenseListItem item={item}/>
    {/each}
</ul>

