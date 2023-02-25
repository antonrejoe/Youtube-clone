

    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" />
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" />
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" />
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" />
<script>


    import './style/scss/style.css';
    import banner from '@smui/banner'
    import Button from '@smui/button';
    import Textfield from '@smui/textfield';
    import TopAppBar from '@smui/top-app-bar'
    import Text from './resources/text.svelte'
    import Hamburger from './resources/hamburger.svelte';
</script>
   
    <div class='parent'>
        
            <Hamburger class='hamburger'/>
            <span class='logo'>
                <img src='src/components/resources/youtube.png' class='youtube_logo' />
                <span class='logo_text'>YouTube</span>
            </span>
            
           <span class='search_bar'>
                <Text/>
            <Button class='search_btn'> 
                <span class="material-symbols-outlined">
                    search

                </span>
            </Button>

           </span> 
        
        <span class='user_side'>
            <Button>
                <span class="material-symbols-outlined">
                        video_call
                </span> 
            </Button>
            <Button>
                <span class="material-symbols-outlined">
                    notifications
                </span>
            
            
            </Button>
             <Button>
                <span class="material-symbols-outlined">
                account_circle
                </span>
             
              </Button>
        
        
        </span>
        
    
    
    </div>

    


    
    
    
    
    <!-- <a href="https://www.flaticon.com/free-icons/youtube" title="youtube icons">Youtube icons created by Freepik - Flaticon</a> -->
<style>

    .text_field{
        height: 5vh;
    }

    :global(body){
        height:12vh
    }


</style>