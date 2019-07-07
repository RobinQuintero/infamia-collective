<script>
import Underline_left from './buttons/Underline_left.svelte'
</script>

<style>
.navbar-fixed{
    position:absolute !important;
}
    nav{
        background-color: rgba(0,0,0,0);
        box-shadow: none;
        
    }
</style>

<div class="navbarc navbar-fixed">
    <nav>
        <div class="nav-wrapper">
        <a href="#!" class="brand-logo"><img src="../img/cold.png" alt="" height="60"></a>
            <ul class="right hide-on-med-and-down">
                <li><Underline_left text="HOME"/></li>
                <li><Underline_left text="INFO"/></li>
                <li><Underline_left text="GALERIA"/></li>
                <li><Underline_left text="TIENDA"/></li>
            </ul>
        </div>
    </nav>
</div>