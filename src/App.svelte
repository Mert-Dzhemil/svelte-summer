<script>
  import Button from './lib/Button.svelte'
  import Counter from './Counter.svelte'
  import ProfileCard from './ProfileCard.svelte'
</script>

<p id="center">
  <Counter />
  <Button />
  <Button label='Click'/>
  <Button label='Click it' color='red'/>
  <Button disabled={true}/>
  <ProfileCard />
</p>

