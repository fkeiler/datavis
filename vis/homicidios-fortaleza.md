# Homicídios em Fortaleza em 2012 por bairro

<div id="observablehq-buildvis-73081f49"></div>

<script type="module">
import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@4/dist/runtime.js";
import define from "https://api.observablehq.com/@fkeiler/homicidios-em-fortaleza-em-2012.js?v=3";
new Runtime().module(define, name => {
  if (name === "buildvis") return new Inspector(document.querySelector("#observablehq-buildvis-73081f49"));
  return ["map","geojson","legend","zoomToFeature","info"].includes(name);
});
</script>
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.6.0/dist/leaflet.css"
   integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ=="
   crossorigin=""/>
<style>
            #mapid {
				width: 750px;
				height: 590px;
			}
			.info {
				padding: 6px 8px;
				font: 14px/16px Arial, Helvetica, sans-serif;
				background: white;
				background: rgba(255,255,255,0.8);
				box-shadow: 0 0 15px rgba(0,0,0,0.2);
				border-radius: 5px;
			}
			.info h4 {
				margin: 0 0 5px;
				color: #777;
			}

    		.legend {
    			text-align: left;
    			line-height: 18px;
    			color: #555;
    		}
    		.legend i {
    			width: 18px;
    			height: 18px;
    			float: left;
    			margin-right: 8px;
    			opacity: 0.7;
    		}

</style>

**Notebook Completo**: <https://observablehq.com/@fkeiler/homicidios-em-fortaleza-em-2012>

**Baseado em**: <https://observablehq.com/@emanueles/homicidios-em-fortaleza-em-2012>
