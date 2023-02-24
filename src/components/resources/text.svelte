

 
<script lang="js">
  import Textfield from '@smui/textfield';
  import Icon from '@smui/textfield/icon';
  import HelperText from '@smui/textfield/helper-text';
 
  let valueA = '';
  
</script>

<div class="columns margins">
  <div>
    <input variant="outlined" bind:value={valueA} label="" class='search_field' placeholder='Search'/>
    
 
  </div>
  
</div>


<style>

 :global(input){
  height:2vh;
  padding:10px;
  width:450px;
  border-radius:2rem 0 0 2rem;
  background:'none';
 }

</style>