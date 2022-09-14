<script>
    let takeHome = [2232 , 2343, 2343, 2343, 2343]

    const avgTakeHome = (arr) => {
        let sum = 0;
        let takeHomeSum = arr.reduce((acc, value) => acc + value);
        console.log(takeHomeSum)
        return takeHomeSum / arr.length
    }
    console.log(Number(avgTakeHome(takeHome)))
</script>

<div>
    <h3>Avg. Take Home</h3>
    <p>{avgTakeHome(takeHome)}</p>
</div>