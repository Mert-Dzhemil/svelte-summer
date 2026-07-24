<script>
    let count = 0;
    function Increase() {
        count++;  
    }
    $: doubled = count * 2;
    $: isEven = count % 2 === 0;
</script>

<div>
    <button on:click={Increase}>Count: {count}</button>
    <p>{doubled}
    <br>
    {isEven ? 'Even' : 'Odd'}
    </p>
</div>

<style>
    button{
        background-color: transparent;
        border-radius: 5px;
        
    }
</style>