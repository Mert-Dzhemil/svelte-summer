<script>
    export let label = 'Click me';
    export let color = 'purple';
    export let disabled= false;
</script>

<div>
    <button style="background:{color}" disabled={disabled}>{label}</button>
</div>