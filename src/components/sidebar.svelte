

<script>
    

    
    export const array = [ {name:'hello' , strength:'take'} ]

   


</script>


<div>
    {#each array as item  }

    <span>{item.name}</span>
    <span>{item.strength}</span>
    

{/each}

</div>







<style>
    /* your styles go here */


</style>
