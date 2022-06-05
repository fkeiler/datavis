# Visualização de Crimes em Chicago

<div id="observablehq-buildvis-60b2fcaf"></div>

<script type="module">
import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@4/dist/runtime.js";
import define from "https://api.observablehq.com/@fkeiler/visualizacao-de-crimes-em-chicago.js?v=3";
new Runtime().module(define, name => {
  if (name === "buildvis") return new Inspector(document.querySelector("#observablehq-buildvis-60b2fcaf"));
  return ["map"].includes(name);
});
</script>
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
<link rel="stylesheet" type="text/css" href="https://unpkg.com/dc@4/dist/style/dc.css" />
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.6.0/dist/leaflet.css"
   integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ=="
   crossorigin=""/>
<style>
  #mapid {
    width: 650px;
    height: 480px;
  }
</style>

**Notebook Completo**: <https://observablehq.com/@fkeiler/visualizacao-de-crimes-em-chicago>

**Baseado em**: <https://observablehq.com/@emanueles/visualizacao-de-crimes-em-chicago>
