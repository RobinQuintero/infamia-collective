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
  width:70%;
  position: absolute;
  top: 50%;
  -ms-transform: translateY(-50%);
  transform: translateY(-50%);
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
    font-size: 56px;
}
h4{
    margin-top:0;
    font-size: 28px;
}
</style>

<Container>
    <div id="main" style="text-align:center; color:white">
        <img id="logo"src="../img/cold.png" alt="" height="300px">
        <h1>INFAMIA</h1>
        <h4>C O L L E C T I V E</h4>
        <p>"Correr hacia el miedo del que huímos".</p>
        <Swipe_right text="Conoce más"/>
    </div>
</Container>
