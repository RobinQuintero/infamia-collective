<script>
	import Swipe_right from './buttons/Swipe_right.svelte'
    import Underline_left from './buttons/Underline_left.svelte'
	import Container from './Container.svelte'
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
    <div id="main" class="col s12 m12 l4 push-l4">
        <img id="logo"src="../img/cold.png" alt="" height="300px">
        <h1>INFAMIA</h1>
        <h4>C O L L E C T I V E</h4>
        <p>"Correr hacia el miedo del que huímos".</p>
        <Swipe_right text="Conoce más"/>
    </div>
</Container>
