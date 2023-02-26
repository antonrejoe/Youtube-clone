
<script>
    
    import history from './resources/sidebar/images/history.svg';
    import home from './resources/sidebar/images/home.svg';
    import search from './resources/sidebar/images/search.svg'
    import shorts from './resources/sidebar/images/shorts.svg'
    import subscriptions from './resources/sidebar/images/subscriptions.svg'
    import video_library from './resources/sidebar/images/video_library.svg'
    import watch_later from './resources/sidebar/images/watch_later.svg'
    import your_Videos from './resources/sidebar/images/your_Videos.svg'
    import freecodecamp from './resources/sidebar/images/freeCodeCamp.jpg'
    import fireship from './resources/sidebar/images/fireship.jpg'
    import cleverProgrammer from './resources/sidebar/images/cleverProgrammer.jpg'
    import feedback from './resources/sidebar/images/feedback.svg'
    import help from './resources/sidebar/images/Help.svg'
    import GODrules from './resources/sidebar/images/godRules.jpg'
    import settings from './resources/sidebar/images/settings.svg'
    import report from './resources/sidebar/images/report.svg'

    

    import './resources/sidebar/js and css/sidebar.css';
   


</script>


<div class='div_sidebar'>
    
    
    <button>
        <img src={home}/> 
        <span>Home</span> 
    </button>
    
    <button>
     <img src={shorts}/> 
     <span>Shorts</span>
    </button>
    
    <button>
        <img src={subscriptions}/>
        <span>Subscriptions</span>
    </button>
   

    <svg class='separator' ></svg>
        
    <button>
        <img src={video_library}/> 
        <span>Library</span> 
    </button>

    <button>
        <img src={history}/> 
        <span>History</span> 
    </button>

    <button>
        <img src={your_Videos}/> 
        <span>Videos</span> 
    </button>
    
    <button>
        <img src={watch_later}/> 
        <span>Watch later</span> 
    </button>

    <h4 class='subscription_heading'> Subscriptions </h4>


    <button>
        <img src={freecodecamp} class='channel_icons'/> 

        <span>freeCodeCamp.org</span> 
    </button>
     <button>
        <img src={fireship} class='channel_icons'/> 

        <span>Fireship</span> 
    </button> 
    
    <button>
        <img src={cleverProgrammer} class='channel_icons'/> 

        <span>cleverProgrammer</span> 
    </button>
    <button>
        <img src={GODrules} class='channel_icons'/> 

        <span>Godrules</span> 
    </button>

    <!-- ? -->


    <svg class='separator' ></svg>

      <button>
        <img src={settings}/> 
        <span>Settings</span> 
    </button>
    
      <button>
        <img src={report} /> 
        <span>Report history</span> 
    </button>

      <button>
        <img src={help}/> 
        <span>Help</span> 
    </button>
      <button>
        <img src={feedback}/> 
        <span>Send feedback</span> 
    </button>
    
    <div class='post_note'>
    <h5>Made with ❤️ by Anton Rejoe</h5>
    <a class='attribution' href="https://www.flaticon.com/free-icons/youtube" title="youtube icons">Youtube icons created by Freepik - Flaticon</a>
    
    </div>

</div>







<style>
    /* your styles go here */


</style>
