<script>
    let count = 0;
    function increase() {
        count++;  
    }
    $: doubled = count * 2;
    $: isEven = count % 2 === 0;
</script>

<div>
    <button on:click={increase}>Count: {count}</button>
    <p>Doubled number: {doubled}
    <br>
    The number is: {isEven ? 'Even' : 'Odd'}
    </p>
</div>

<style>
    button{
        background-color: transparent;
        border-radius: 5px;
        
    }
</style>