<h1>About</h1>

<script>
    import * as THREE from 'three';
    import WAVES from 'vanta/dist/vanta.waves.min';    
    function vanta(node) {
        WAVES({
            el: node,
            THREE: THREE,
            mouseControls: true,
  touchControls: true,
  gyroControls: false,
  minHeight: 200.00,
  minWidth: 200.00,
  scale: 1.00,
  scaleMobile: 1.00
        })
    }

</script>

<div style="height:500px;width:500px;" use:vanta/>