<script>
export let text
export let link
</script>

<style>
.underline_left {
    width:90px;
    text-align:center;
    display: inline-block;
    vertical-align: middle;
    -webkit-transform: perspective(1px) translateZ(0);
    transform: perspective(1px) translateZ(0);
    box-shadow: 0 0 1px rgba(0, 0, 0, 0);
    overflow: hidden;
}
.underline_left:before {
    text-decoration:none;
    content: "";
    position: absolute;
    z-index: -1;
    left: 0;
    right: 100%;
    bottom: 0;
    background: white;
    height: 3px;
    -webkit-transition-property: right;
    transition-property: right;
    -webkit-transition-duration: 0.3s;
    transition-duration: 0.3s;
    -webkit-transition-timing-function: ease-out;
    transition-timing-function: ease-out;
}
.underline_left:hover:before, .underline_left:focus:before, .underline_left:active:before {
    text-decoration:none;
    right: 0;
}

</style>

<a href={link} class="Cbutton underline_left" >{text}</a>
