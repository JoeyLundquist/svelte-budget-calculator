<script>
    // Components
    import Navbar from '../../components/Navbar.svelte'
    import ExpenseList from '../../components/ExpenseList.svelte';
    import ExpenseTotal from '../../components/ExpenseTotal.svelte';
</script>
<Navbar />

<main>
    <ExpenseTotal />
    <ExpenseList /> 
</main>
