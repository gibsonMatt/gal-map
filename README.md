# Interactive map of Galapagos field sites

[Map](https://gibsonmatt.github.io/field_sites.html)


<!DOCTYPE html>
<head>    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    <script>L_PREFER_CANVAS = false; L_NO_TOUCH = false; L_DISABLE_3D = false;</script>
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.2.0/dist/leaflet.js"></script>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.2.0/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://rawgit.com/python-visualization/folium/master/folium/templates/leaflet.awesome.rotate.css"/>
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    
            <style> #map_eed41de566554bc9815575698b9ff224 {
                position : relative;
                width : 100.0%;
                height: 100.0%;
                left: 0.0%;
                top: 0.0%;
                }
            </style>
        
</head>
<body>    
    
            <div class="folium-map" id="map_eed41de566554bc9815575698b9ff224" ></div>
        
</body>
<script>    
    

            
                var bounds = null;
            

            var map_eed41de566554bc9815575698b9ff224 = L.map(
                                  'map_eed41de566554bc9815575698b9ff224',
                                  {center: [-0.556061,-90.473281],
                                  zoom: 9,
                                  maxBounds: bounds,
                                  layers: [],
                                  worldCopyJump: false,
                                  crs: L.CRS.EPSG3857
                                 });
            
        
    
            var tile_layer_47e662b9bb1b42b2abdb87d808b43db6 = L.tileLayer(
                'https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png',
                {
  "attribution": null,
  "detectRetina": false,
  "maxZoom": 18,
  "minZoom": 1,
  "noWrap": false,
  "subdomains": "abc"
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
        
    

            var circle_bff3714845dc46089ec51ea46b0bc4a4 = L.circle(
                [-0.896911,-89.608612],
                {
  "bubblingMouseEvents": true,
  "color": "#f4743b",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#f4743b",
  "fillOpacity": 0.2,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 400,
  "stroke": true,
  "weight": 3
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
            
    
            var popup_e5ef06f4edb24ed7bbcab23c65e4ccf1 = L.popup({maxWidth: '300'});

            
                var html_c319ad0424ab488aaf11deb9b456b2d7 = $('<div id="html_c319ad0424ab488aaf11deb9b456b2d7" style="width: 100.0%; height: 100.0%;">Population: MG101<br> Species: S. lycopersicum<br> Island: SCB<br> Latitude: -0.896911<br> Longitude: -89.608612<br> Local site name: Road to Playa Mann<br> Date sampled: 5/10/2018<br> Population size: 1<br> Sample size: 1</div>')[0];
                popup_e5ef06f4edb24ed7bbcab23c65e4ccf1.setContent(html_c319ad0424ab488aaf11deb9b456b2d7);
            

            circle_bff3714845dc46089ec51ea46b0bc4a4.bindPopup(popup_e5ef06f4edb24ed7bbcab23c65e4ccf1);

            
        
    

            var circle_fced1320e58446d68934956d024c175d = L.circle(
                [-0.896156,-89.60927099999999],
                {
  "bubblingMouseEvents": true,
  "color": "#f4743b",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#f4743b",
  "fillOpacity": 0.2,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 400,
  "stroke": true,
  "weight": 3
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
            
    
            var popup_1dc52d39c9d348019ba701a49308e1a9 = L.popup({maxWidth: '300'});

            
                var html_31c899df8a0e4bd79bcfdd98794faa7c = $('<div id="html_31c899df8a0e4bd79bcfdd98794faa7c" style="width: 100.0%; height: 100.0%;">Population: MG103<br> Species: S. lycopersicum<br> Island: SCB<br> Latitude: -0.896156<br> Longitude: -89.60927099999999<br> Local site name: Playa Mann<br> Date sampled: 5/10/2018<br> Population size: 3<br> Sample size: 2</div>')[0];
                popup_1dc52d39c9d348019ba701a49308e1a9.setContent(html_31c899df8a0e4bd79bcfdd98794faa7c);
            

            circle_fced1320e58446d68934956d024c175d.bindPopup(popup_1dc52d39c9d348019ba701a49308e1a9);

            
        
    

            var circle_1a35e009483e4e40abc74e0b5013d02e = L.circle(
                [-0.9097540000000001,-89.608524],
                {
  "bubblingMouseEvents": true,
  "color": "#f4743b",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#f4743b",
  "fillOpacity": 0.2,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 400,
  "stroke": true,
  "weight": 3
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
            
    
            var popup_f22d9c2fbe634e15a12cd9f65c4b4f74 = L.popup({maxWidth: '300'});

            
                var html_cad2a622ff3e4cb1926dcd35c57f61f6 = $('<div id="html_cad2a622ff3e4cb1926dcd35c57f61f6" style="width: 100.0%; height: 100.0%;">Population: MG104<br> Species: S. lycopersicum<br> Island: SCB<br> Latitude: -0.9097540000000001<br> Longitude: -89.608524<br> Local site name: Puerto Baquerizo<br> Date sampled: 5/11/2018<br> Population size: 1<br> Sample size: 1</div>')[0];
                popup_f22d9c2fbe634e15a12cd9f65c4b4f74.setContent(html_cad2a622ff3e4cb1926dcd35c57f61f6);
            

            circle_1a35e009483e4e40abc74e0b5013d02e.bindPopup(popup_f22d9c2fbe634e15a12cd9f65c4b4f74);

            
        
    

            var circle_7eee7168a3a24475bd372b7ed6a24111 = L.circle(
                [-0.90799,-89.555661],
                {
  "bubblingMouseEvents": true,
  "color": "#f4743b",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#f4743b",
  "fillOpacity": 0.2,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 400,
  "stroke": true,
  "weight": 3
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
            
    
            var popup_ea69a845fe5f42bfb8421ec905c533eb = L.popup({maxWidth: '300'});

            
                var html_17d4ff29deac423d9ff08d8d925a7c2b = $('<div id="html_17d4ff29deac423d9ff08d8d925a7c2b" style="width: 100.0%; height: 100.0%;">Population: MG105<br> Species: S. pimpinellifolium<br> Island: SCB<br> Latitude: -0.90799<br> Longitude: -89.555661<br> Local site name: Progresso<br> Date sampled: 5/11/2018<br> Population size: 10<br> Sample size: 8</div>')[0];
                popup_ea69a845fe5f42bfb8421ec905c533eb.setContent(html_17d4ff29deac423d9ff08d8d925a7c2b);
            

            circle_7eee7168a3a24475bd372b7ed6a24111.bindPopup(popup_ea69a845fe5f42bfb8421ec905c533eb);

            
        
    

            var circle_c5a84758c033461bb71994e4514abc45 = L.circle(
                [-0.9109870000000001,-89.55458],
                {
  "bubblingMouseEvents": true,
  "color": "#f4743b",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#f4743b",
  "fillOpacity": 0.2,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 400,
  "stroke": true,
  "weight": 3
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
            
    
            var popup_c49d1c09e9674415a49b0a95eefe2d3d = L.popup({maxWidth: '300'});

            
                var html_29555feb430d46e0b2841b126ed943a0 = $('<div id="html_29555feb430d46e0b2841b126ed943a0" style="width: 100.0%; height: 100.0%;">Population: MG106<br> Species: S. lycopersicum<br> Island: SCB<br> Latitude: -0.9109870000000001<br> Longitude: -89.55458<br> Local site name: Progresso<br> Date sampled: 5/11/2018<br> Population size: 3<br> Sample size: 3</div>')[0];
                popup_c49d1c09e9674415a49b0a95eefe2d3d.setContent(html_29555feb430d46e0b2841b126ed943a0);
            

            circle_c5a84758c033461bb71994e4514abc45.bindPopup(popup_c49d1c09e9674415a49b0a95eefe2d3d);

            
        
    

            var circle_afe207e6a09a4f36b138afb2e94515b6 = L.circle(
                [-0.8997200000000001,-89.55379599999999],
                {
  "bubblingMouseEvents": true,
  "color": "#f4743b",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#f4743b",
  "fillOpacity": 0.2,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 400,
  "stroke": true,
  "weight": 3
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
            
    
            var popup_cb66f355eb6f42d599625939ec1554e9 = L.popup({maxWidth: '300'});

            
                var html_87c1a59ba6cb41efb97659060cd44056 = $('<div id="html_87c1a59ba6cb41efb97659060cd44056" style="width: 100.0%; height: 100.0%;">Population: MG107<br> Species: S. pimpinellifolium<br> Island: SCB<br> Latitude: -0.8997200000000001<br> Longitude: -89.55379599999999<br> Local site name: Soledad<br> Date sampled: 5/11/2018<br> Population size: 15<br> Sample size: 10</div>')[0];
                popup_cb66f355eb6f42d599625939ec1554e9.setContent(html_87c1a59ba6cb41efb97659060cd44056);
            

            circle_afe207e6a09a4f36b138afb2e94515b6.bindPopup(popup_cb66f355eb6f42d599625939ec1554e9);

            
        
    

            var circle_a13a98be6c4e494ca86f154787c86774 = L.circle(
                [-0.8931180000000001,-89.61075799999999],
                {
  "bubblingMouseEvents": true,
  "color": "#f4743b",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#f4743b",
  "fillOpacity": 0.2,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 400,
  "stroke": true,
  "weight": 3
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
            
    
            var popup_c5946b28622145cc8e90460103d09f48 = L.popup({maxWidth: '300'});

            
                var html_b6851425ba5243b6ae285bef7c28b30f = $('<div id="html_b6851425ba5243b6ae285bef7c28b30f" style="width: 100.0%; height: 100.0%;">Population: MG109<br> Species: S. pimpinellifolium<br> Island: SCB<br> Latitude: -0.8931180000000001<br> Longitude: -89.61075799999999<br> Local site name: Pedrial<br> Date sampled: 5/12/2018<br> Population size: 2<br> Sample size: 2</div>')[0];
                popup_c5946b28622145cc8e90460103d09f48.setContent(html_b6851425ba5243b6ae285bef7c28b30f);
            

            circle_a13a98be6c4e494ca86f154787c86774.bindPopup(popup_c5946b28622145cc8e90460103d09f48);

            
        
    

            var circle_5da890a9921d47bc970184ff83387843 = L.circle(
                [-0.9039889999999999,-89.61304100000001],
                {
  "bubblingMouseEvents": true,
  "color": "#f4743b",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#f4743b",
  "fillOpacity": 0.2,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 400,
  "stroke": true,
  "weight": 3
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
            
    
            var popup_39dac933b19740e79794da1b79b03d1c = L.popup({maxWidth: '300'});

            
                var html_5c932aae7cd84a79a91dd068c647c485 = $('<div id="html_5c932aae7cd84a79a91dd068c647c485" style="width: 100.0%; height: 100.0%;">Population: MG110<br> Species: S. lycopersicum<br> Island: SCB<br> Latitude: -0.9039889999999999<br> Longitude: -89.61304100000001<br> Local site name: Puerto Baquerizo<br> Date sampled: 5/12/2018<br> Population size: 1<br> Sample size: 1</div>')[0];
                popup_39dac933b19740e79794da1b79b03d1c.setContent(html_5c932aae7cd84a79a91dd068c647c485);
            

            circle_5da890a9921d47bc970184ff83387843.bindPopup(popup_39dac933b19740e79794da1b79b03d1c);

            
        
    

            var circle_0dd8ea9106b546218194cf224128d88a = L.circle(
                [-0.9011379999999999,-89.610079],
                {
  "bubblingMouseEvents": true,
  "color": "#f4743b",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#f4743b",
  "fillOpacity": 0.2,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 400,
  "stroke": true,
  "weight": 3
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
            
    
            var popup_a6f6c23fd5034768997a8ca6eb007701 = L.popup({maxWidth: '300'});

            
                var html_e15ac9051d634b1aab627fac9deba8a4 = $('<div id="html_e15ac9051d634b1aab627fac9deba8a4" style="width: 100.0%; height: 100.0%;">Population: MG111<br> Species: lycoXpimp<br> Island: SCB<br> Latitude: -0.9011379999999999<br> Longitude: -89.610079<br> Local site name: Puerto Baquerizo<br> Date sampled: 5/12/2018<br> Population size: 25<br> Sample size: 15</div>')[0];
                popup_a6f6c23fd5034768997a8ca6eb007701.setContent(html_e15ac9051d634b1aab627fac9deba8a4);
            

            circle_0dd8ea9106b546218194cf224128d88a.bindPopup(popup_a6f6c23fd5034768997a8ca6eb007701);

            
        
    

            var circle_4aab88020e4240f6872379982555fe46 = L.circle(
                [-0.684878,-90.327229],
                {
  "bubblingMouseEvents": true,
  "color": "#f4743b",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#f4743b",
  "fillOpacity": 0.2,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 400,
  "stroke": true,
  "weight": 3
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
            
    
            var popup_f64b1b663b4844bbbf0657b69a9cc9ee = L.popup({maxWidth: '300'});

            
                var html_3d71d67b0bc7480bbbe3d2b1a8c14de2 = $('<div id="html_3d71d67b0bc7480bbbe3d2b1a8c14de2" style="width: 100.0%; height: 100.0%;">Population: MG113<br> Species: pimpXcheese<br> Island: SCZ<br> Latitude: -0.684878<br> Longitude: -90.327229<br> Local site name: Café farm in Bellavista<br> Date sampled: 5/18/2018<br> Population size: 400<br> Sample size: 10</div>')[0];
                popup_f64b1b663b4844bbbf0657b69a9cc9ee.setContent(html_3d71d67b0bc7480bbbe3d2b1a8c14de2);
            

            circle_4aab88020e4240f6872379982555fe46.bindPopup(popup_f64b1b663b4844bbbf0657b69a9cc9ee);

            
        
    

            var circle_563b62ca273d4a2d89f393930fdbdf9a = L.circle(
                [-0.61525,-90.36684699999999],
                {
  "bubblingMouseEvents": true,
  "color": "#f4743b",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#f4743b",
  "fillOpacity": 0.2,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 400,
  "stroke": true,
  "weight": 3
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
            
    
            var popup_c7b95f4fa7ad4d5f8c0ac26052d30cb8 = L.popup({maxWidth: '300'});

            
                var html_7b3a3bd4493f4f659a23ccf54e76ab42 = $('<div id="html_7b3a3bd4493f4f659a23ccf54e76ab42" style="width: 100.0%; height: 100.0%;">Population: MG114<br> Species: pimpXcheese<br> Island: SCZ<br> Latitude: -0.61525<br> Longitude: -90.36684699999999<br> Local site name: Mina Roja<br> Date sampled: 5/18/2018<br> Population size: 300<br> Sample size: 15</div>')[0];
                popup_c7b95f4fa7ad4d5f8c0ac26052d30cb8.setContent(html_7b3a3bd4493f4f659a23ccf54e76ab42);
            

            circle_563b62ca273d4a2d89f393930fdbdf9a.bindPopup(popup_c7b95f4fa7ad4d5f8c0ac26052d30cb8);

            
        
    

            var circle_01b6a706ad2d44ac8e5d2e03f034cb5a = L.circle(
                [-0.5600641,-90.332402],
                {
  "bubblingMouseEvents": true,
  "color": "#f4743b",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#f4743b",
  "fillOpacity": 0.2,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 400,
  "stroke": true,
  "weight": 3
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
            
    
            var popup_67a1d04c707f411581e1be6b9cafc97b = L.popup({maxWidth: '300'});

            
                var html_f5851dc691bf4c389d39d3bbc5183c5c = $('<div id="html_f5851dc691bf4c389d39d3bbc5183c5c" style="width: 100.0%; height: 100.0%;">Population: MG115<br> Species: S. cheesmaniae; S. pimpinellifolium; pimpXcheese<br> Island: SCZ<br> Latitude: -0.5600641<br> Longitude: -90.332402<br> Local site name: Baltra Road<br> Date sampled: 5/18/2018<br> Population size: 25<br> Sample size: 20</div>')[0];
                popup_67a1d04c707f411581e1be6b9cafc97b.setContent(html_f5851dc691bf4c389d39d3bbc5183c5c);
            

            circle_01b6a706ad2d44ac8e5d2e03f034cb5a.bindPopup(popup_67a1d04c707f411581e1be6b9cafc97b);

            
        
    

            var circle_ae49f84986f44b86bbe586ea8cccc5af = L.circle(
                [-0.74695,-90.314839],
                {
  "bubblingMouseEvents": true,
  "color": "#f4743b",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#f4743b",
  "fillOpacity": 0.2,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 400,
  "stroke": true,
  "weight": 3
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
            
    
            var popup_01607bc720db4641ac28f804cf23f672 = L.popup({maxWidth: '300'});

            
                var html_30df17c5a9f14b879d714516a6c4858f = $('<div id="html_30df17c5a9f14b879d714516a6c4858f" style="width: 100.0%; height: 100.0%;">Population: MG116<br> Species: S. pimpinellifolium; S. lycopersicum<br> Island: SCZ<br> Latitude: -0.74695<br> Longitude: -90.314839<br> Local site name: Puerto Ayora<br> Date sampled: 5/19/2018<br> Population size: 15<br> Sample size: 12</div>')[0];
                popup_01607bc720db4641ac28f804cf23f672.setContent(html_30df17c5a9f14b879d714516a6c4858f);
            

            circle_ae49f84986f44b86bbe586ea8cccc5af.bindPopup(popup_01607bc720db4641ac28f804cf23f672);

            
        
    

            var circle_9f5353a83a16438680d9342d25c39fec = L.circle(
                [-0.7131350000000001,-90.325503],
                {
  "bubblingMouseEvents": true,
  "color": "#f4743b",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#f4743b",
  "fillOpacity": 0.2,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 400,
  "stroke": true,
  "weight": 3
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
            
    
            var popup_7f19a061e5844e9d980ec988e9396d12 = L.popup({maxWidth: '300'});

            
                var html_22140a5f84494fcfa2b736156cc98a57 = $('<div id="html_22140a5f84494fcfa2b736156cc98a57" style="width: 100.0%; height: 100.0%;">Population: MG117<br> Species: pimpXcheese<br> Island: SCZ<br> Latitude: -0.7131350000000001<br> Longitude: -90.325503<br> Local site name: Thomas Berlanga<br> Date sampled: 5/19/2018<br> Population size: 70<br> Sample size: 12</div>')[0];
                popup_7f19a061e5844e9d980ec988e9396d12.setContent(html_22140a5f84494fcfa2b736156cc98a57);
            

            circle_9f5353a83a16438680d9342d25c39fec.bindPopup(popup_7f19a061e5844e9d980ec988e9396d12);

            
        
    

            var circle_7d2f0d7bb5cd4c2695c18125959d0d1d = L.circle(
                [-0.671528,-90.26289399999999],
                {
  "bubblingMouseEvents": true,
  "color": "#f4743b",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#f4743b",
  "fillOpacity": 0.2,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 400,
  "stroke": true,
  "weight": 3
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
            
    
            var popup_d7f750a58b0c4e308c610c09cf5e39cc = L.popup({maxWidth: '300'});

            
                var html_c5f03609d517477cb0d35dade3e21b0a = $('<div id="html_c5f03609d517477cb0d35dade3e21b0a" style="width: 100.0%; height: 100.0%;">Population: MG118<br> Species: S. lycopersicum; S. pimpinellifolium<br> Island: SCZ<br> Latitude: -0.671528<br> Longitude: -90.26289399999999<br> Local site name: Cascajo<br> Date sampled: 5/21/2018<br> Population size: 50<br> Sample size: 4</div>')[0];
                popup_d7f750a58b0c4e308c610c09cf5e39cc.setContent(html_c5f03609d517477cb0d35dade3e21b0a);
            

            circle_7d2f0d7bb5cd4c2695c18125959d0d1d.bindPopup(popup_d7f750a58b0c4e308c610c09cf5e39cc);

            
        
    

            var circle_c2f37e8819ab4273b4927bd3dcf416f9 = L.circle(
                [-0.733719,-90.31168000000001],
                {
  "bubblingMouseEvents": true,
  "color": "#f4743b",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#f4743b",
  "fillOpacity": 0.2,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 400,
  "stroke": true,
  "weight": 3
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
            
    
            var popup_cb944c6caed04f8ca2eb2891dc62966b = L.popup({maxWidth: '300'});

            
                var html_9ab830641cf34703a0927ff5adb83223 = $('<div id="html_9ab830641cf34703a0927ff5adb83223" style="width: 100.0%; height: 100.0%;">Population: MG119<br> Species: S. lycopersicum<br> Island: SCZ<br> Latitude: -0.733719<br> Longitude: -90.31168000000001<br> Local site name: Puerto Ayora<br> Date sampled: 5/21/2018<br> Population size: 1<br> Sample size: 1</div>')[0];
                popup_cb944c6caed04f8ca2eb2891dc62966b.setContent(html_9ab830641cf34703a0927ff5adb83223);
            

            circle_c2f37e8819ab4273b4927bd3dcf416f9.bindPopup(popup_cb944c6caed04f8ca2eb2891dc62966b);

            
        
    

            var circle_f3c39a7418f0484d957a60c157623248 = L.circle(
                [-0.928464,-90.980253],
                {
  "bubblingMouseEvents": true,
  "color": "#f4743b",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#f4743b",
  "fillOpacity": 0.2,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 400,
  "stroke": true,
  "weight": 3
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
            
    
            var popup_a304c26dee214e25b786c44875a8e3af = L.popup({maxWidth: '300'});

            
                var html_be9e029987f14e16a0170b90a79eab8c = $('<div id="html_be9e029987f14e16a0170b90a79eab8c" style="width: 100.0%; height: 100.0%;">Population: MG120<br> Species: S. galapagense; S. cheesmaniae; galXcheese<br> Island: ISB<br> Latitude: -0.928464<br> Longitude: -90.980253<br> Local site name: El Pozo/Laguna Manzanilla<br> Date sampled: 5/26/2018<br> Population size: 50<br> Sample size: 34</div>')[0];
                popup_a304c26dee214e25b786c44875a8e3af.setContent(html_be9e029987f14e16a0170b90a79eab8c);
            

            circle_f3c39a7418f0484d957a60c157623248.bindPopup(popup_a304c26dee214e25b786c44875a8e3af);

            
        
    

            var circle_bd59faf615bc49a5b7cf10b3f4efef95 = L.circle(
                [-0.9563010000000001,-90.965637],
                {
  "bubblingMouseEvents": true,
  "color": "#f4743b",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#f4743b",
  "fillOpacity": 0.2,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 400,
  "stroke": true,
  "weight": 3
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
            
    
            var popup_131615da9ba74e39974349cf88e620a3 = L.popup({maxWidth: '300'});

            
                var html_f6bd65d6ef8e4cb3999bd4e87624c94a = $('<div id="html_f6bd65d6ef8e4cb3999bd4e87624c94a" style="width: 100.0%; height: 100.0%;">Population: MG121<br> Species: S. lycopersicum<br> Island: ISB<br> Latitude: -0.9563010000000001<br> Longitude: -90.965637<br> Local site name: Puerto Villamill<br> Date sampled: 5/27/2018<br> Population size: 1<br> Sample size: 1</div>')[0];
                popup_131615da9ba74e39974349cf88e620a3.setContent(html_f6bd65d6ef8e4cb3999bd4e87624c94a);
            

            circle_bd59faf615bc49a5b7cf10b3f4efef95.bindPopup(popup_131615da9ba74e39974349cf88e620a3);

            
        
    

            var circle_346677322e764d659f91b2d9c616f760 = L.circle(
                [-0.954225,-90.969003],
                {
  "bubblingMouseEvents": true,
  "color": "#f4743b",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#f4743b",
  "fillOpacity": 0.2,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 400,
  "stroke": true,
  "weight": 3
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
            
    
            var popup_7a756616120a423f92a9760163e084c7 = L.popup({maxWidth: '300'});

            
                var html_c6a059693c4f4f76b1cb7b7ce2031aa2 = $('<div id="html_c6a059693c4f4f76b1cb7b7ce2031aa2" style="width: 100.0%; height: 100.0%;">Population: MG122<br> Species: S. lycopersicum; S. pimpinellifolium<br> Island: ISB<br> Latitude: -0.954225<br> Longitude: -90.969003<br> Local site name: Puerto Villamill<br> Date sampled: 5/27/2018<br> Population size: 2<br> Sample size: 2</div>')[0];
                popup_7a756616120a423f92a9760163e084c7.setContent(html_c6a059693c4f4f76b1cb7b7ce2031aa2);
            

            circle_346677322e764d659f91b2d9c616f760.bindPopup(popup_7a756616120a423f92a9760163e084c7);

            
        
    

            var circle_b57a69540209466b9c7fa8e6fd7e9995 = L.circle(
                [-0.9297979999999999,-90.98678699999999],
                {
  "bubblingMouseEvents": true,
  "color": "#f4743b",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#f4743b",
  "fillOpacity": 0.2,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 400,
  "stroke": true,
  "weight": 3
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
            
    
            var popup_fdfd56827e134eb389ee16a91d2cc051 = L.popup({maxWidth: '300'});

            
                var html_7e681fcab91e4056b3871621aa343990 = $('<div id="html_7e681fcab91e4056b3871621aa343990" style="width: 100.0%; height: 100.0%;">Population: MG124<br> Species: S. galapagense<br> Island: ISB<br> Latitude: -0.9297979999999999<br> Longitude: -90.98678699999999<br> Local site name: Puerto Villamill, across hwy from pozo<br> Date sampled: 5/28/2018<br> Population size: 8<br> Sample size: 4</div>')[0];
                popup_fdfd56827e134eb389ee16a91d2cc051.setContent(html_7e681fcab91e4056b3871621aa343990);
            

            circle_b57a69540209466b9c7fa8e6fd7e9995.bindPopup(popup_fdfd56827e134eb389ee16a91d2cc051);

            
        
    

            var circle_96e995434b1b4b30adf7819f6e9a6f5f = L.circle(
                [-0.877017,-91.00659399999999],
                {
  "bubblingMouseEvents": true,
  "color": "#f4743b",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#f4743b",
  "fillOpacity": 0.2,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 400,
  "stroke": true,
  "weight": 3
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
            
    
            var popup_1a11d16beeab4963a95be51644e3510e = L.popup({maxWidth: '300'});

            
                var html_9974baa781cc4df09ee35a5e51bcc316 = $('<div id="html_9974baa781cc4df09ee35a5e51bcc316" style="width: 100.0%; height: 100.0%;">Population: MG125<br> Species: S. lycopersicum; S. pimpinellifolium<br> Island: ISB<br> Latitude: -0.877017<br> Longitude: -91.00659399999999<br> Local site name: Basudero<br> Date sampled: 5/28/2018<br> Population size: 700<br> Sample size: 10</div>')[0];
                popup_1a11d16beeab4963a95be51644e3510e.setContent(html_9974baa781cc4df09ee35a5e51bcc316);
            

            circle_96e995434b1b4b30adf7819f6e9a6f5f.bindPopup(popup_1a11d16beeab4963a95be51644e3510e);

            
        
    

            var circle_249eed4383c74746bb37e830ed66f09e = L.circle(
                [-0.850137,-91.024555],
                {
  "bubblingMouseEvents": true,
  "color": "#f4743b",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#f4743b",
  "fillOpacity": 0.2,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 400,
  "stroke": true,
  "weight": 3
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
            
    
            var popup_f7cc4389c7d8434688f34af1291a254c = L.popup({maxWidth: '300'});

            
                var html_2c91dcb424464778aca0914ff0a6a2d3 = $('<div id="html_2c91dcb424464778aca0914ff0a6a2d3" style="width: 100.0%; height: 100.0%;">Population: MG126<br> Species: S. lycopersicum<br> Island: ISB<br> Latitude: -0.850137<br> Longitude: -91.024555<br> Local site name: Esperanza<br> Date sampled: 5/28/2018<br> Population size: 500<br> Sample size: 5</div>')[0];
                popup_f7cc4389c7d8434688f34af1291a254c.setContent(html_2c91dcb424464778aca0914ff0a6a2d3);
            

            circle_249eed4383c74746bb37e830ed66f09e.bindPopup(popup_f7cc4389c7d8434688f34af1291a254c);

            
        
    

            var circle_377a63413445414bb8c92543f2fc4f99 = L.circle(
                [-0.923061,-90.989148],
                {
  "bubblingMouseEvents": true,
  "color": "#f4743b",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#f4743b",
  "fillOpacity": 0.2,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 400,
  "stroke": true,
  "weight": 3
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
            
    
            var popup_0cf7cfdd9cf248ae8d95542352ab2c76 = L.popup({maxWidth: '300'});

            
                var html_d1db2e8d6d8449728c40b3e965efa4d0 = $('<div id="html_d1db2e8d6d8449728c40b3e965efa4d0" style="width: 100.0%; height: 100.0%;">Population: MG127<br> Species: S. galapagense<br> Island: ISB<br> Latitude: -0.923061<br> Longitude: -90.989148<br> Local site name: Road to St Tomas<br> Date sampled: 5/29/2018<br> Population size: 6<br> Sample size: 2</div>')[0];
                popup_0cf7cfdd9cf248ae8d95542352ab2c76.setContent(html_d1db2e8d6d8449728c40b3e965efa4d0);
            

            circle_377a63413445414bb8c92543f2fc4f99.bindPopup(popup_0cf7cfdd9cf248ae8d95542352ab2c76);

            
        
    

            var circle_d674cf3208e64e4aa9e6955de1b6d245 = L.circle(
                [-0.9531040000000001,-90.96350799999999],
                {
  "bubblingMouseEvents": true,
  "color": "#f4743b",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#f4743b",
  "fillOpacity": 0.2,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 400,
  "stroke": true,
  "weight": 3
}
                ).addTo(map_eed41de566554bc9815575698b9ff224);
            
    
            var popup_8c2d7a78534f4ebdbeb2050609d4da67 = L.popup({maxWidth: '300'});

            
                var html_fe93606815eb483a964a628ecc244c61 = $('<div id="html_fe93606815eb483a964a628ecc244c61" style="width: 100.0%; height: 100.0%;">Population: MG128<br> Species: lycoXpimp<br> Island: ISB<br> Latitude: -0.9531040000000001<br> Longitude: -90.96350799999999<br> Local site name: Puerto Villamill<br> Date sampled: 5/29/2018<br> Population size: 1<br> Sample size: 1</div>')[0];
                popup_8c2d7a78534f4ebdbeb2050609d4da67.setContent(html_fe93606815eb483a964a628ecc244c61);
            

            circle_d674cf3208e64e4aa9e6955de1b6d245.bindPopup(popup_8c2d7a78534f4ebdbeb2050609d4da67);

            
        
</script>
