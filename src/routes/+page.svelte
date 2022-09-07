<script>
    import Navbar from '../components/Navbar.svelte'
    import expenseData from '../sampleData/sampleExpenses'
    let expenses = [...expenseData];
</script>
<Navbar />

{#each expenses as item}

{/each}