<script>
    // Components
    import Navbar from '../components/Navbar.svelte'
    import ExpenseList from '../components/ExpenseList.svelte';
    
    // Data
    import expenseData from '../sampleData/sampleExpenses'

    // Variables
    let expenses = [...expenseData];
</script>
<Navbar />

<main>
<ExpenseList /> 
</main>
