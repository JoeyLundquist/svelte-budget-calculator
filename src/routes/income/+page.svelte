<script>
    // Components
    import Navbar from "../../components/Navbar.svelte";
    import AvgMonthlyTh from "../../components/income/AvgMonthlyTH.svelte";
    import IncomeInput from "../../components/income/IncomeInput.svelte";
</script>

<Navbar />

<h3>Ideas for this page</h3>

<ul>
    <li>Avg monthly take home</li>
    <li>Gross monthly</li>
    <li>Net Monthly</li>
    <li>Taxes</li>
    <li>Insurance</li>
    <li>retirement</li>
</ul>

<IncomeInput />
<AvgMonthlyTh />  
