<script>
	import Swipe_right from './buttons/Swipe_right.svelte'
    import Underline_left from './buttons/Underline_left.svelte'
    import Container from './Container.svelte'
    if( /Android|webOS|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent) ) {
        alert('mobile')
    }
</script>

<style>
#main{
    display: block;
    margin-left: auto;
    margin-right: auto;
    position: absolute;
    top: 50%;
    -ms-transform: translateY(-50%);
    transform: translateY(-50%);
    text-align:center; color:white;
    background-color:red;
}
#logo{
    display: block;
    width:200px;
    margin-left: auto;
    margin-right: auto;
}
h1{
    margin-top:25px;
    margin-bottom:0;
    font-size: 50px;
}
h4{
    margin-top:0;
    font-size: 25px;
}
</style>

<Container>
    <div id="main" class="col s12 m12 l2">
        <img id="logo"src="../img/cold.png" alt="">
        <h1>INFAMIA</h1>
        <h4>C O L L E C T I V E</h4>
        <p class="hide-on-large-only">"Correr hacia el miedo del que huímos".</p>
        <Swipe_right text="Conoce más" hide={true}/>
        <ul class=" hide-on-med-and-down" id="mobile-demo">
            <li><Underline_left text="HOME"/></li>
            <li><Underline_left text="INFO"/></li>
            <li><Underline_left text="GALERIA"/></li>
            <li><Underline_left text="TIENDA"/></li>
            
        </ul>
    </div>
</Container>
