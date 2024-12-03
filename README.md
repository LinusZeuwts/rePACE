<!DOCTYPE html>
<html>
<head>
    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://netdna.bootstrapcdn.com/bootstrap/3.0.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.2.0/css/all.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/python-visualization/folium/folium/templates/leaflet.awesome.rotate.min.css"/>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_4be3be938716243d410ab569db9a71bf {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
                .leaflet-container { font-size: 1rem; }
            </style>
        
    <script src="https://cdnjs.cloudflare.com/ajax/libs/leaflet.markercluster/1.1.0/leaflet.markercluster.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/leaflet.markercluster/1.1.0/MarkerCluster.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/leaflet.markercluster/1.1.0/MarkerCluster.Default.css"/>
</head>
<body>
    
    
            <div class="folium-map" id="map_4be3be938716243d410ab569db9a71bf" ></div>
        
</body>
<script>
    
    
            var map_4be3be938716243d410ab569db9a71bf = L.map(
                "map_4be3be938716243d410ab569db9a71bf",
                {
                    center: [51.0258761, 4.477536],
                    crs: L.CRS.EPSG3857,
                    zoom: 13,
                    zoomControl: true,
                    preferCanvas: false,
                }
            );

            

        
    
            var tile_layer_963b79af84211a001c28c1941a2efe0a = L.tileLayer(
                "https://tile.openstreetmap.org/{z}/{x}/{y}.png",
                {"attribution": "\u0026copy; \u003ca href=\"https://www.openstreetmap.org/copyright\"\u003eOpenStreetMap\u003c/a\u003e contributors", "detectRetina": false, "maxNativeZoom": 19, "maxZoom": 19, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            );
        
    
            tile_layer_963b79af84211a001c28c1941a2efe0a.addTo(map_4be3be938716243d410ab569db9a71bf);
        
    
            var marker_cluster_fc48d82ffbf9a2cf3ad4c57837871968 = L.markerClusterGroup(
                {}
            );
        
    
            marker_cluster_fc48d82ffbf9a2cf3ad4c57837871968.addTo(map_4be3be938716243d410ab569db9a71bf);
        
    
            var feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c = L.featureGroup(
                {}
            );
        
    
            var marker_eb19a9481913c21370a99278ef3d5400 = L.marker(
                [51.02876966705971, 4.484152385758547],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_c433c85a3b446bafbeddb7904729f261 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_eb19a9481913c21370a99278ef3d5400.setIcon(icon_c433c85a3b446bafbeddb7904729f261);
        
    
        var popup_aa67c996e2aa0da0d195b5546de1e3fe = L.popup({"maxWidth": "100%"});

        
            
                var html_200896190d628162be937c12aa9d4b9d = $(`<div id="html_200896190d628162be937c12aa9d4b9d" style="width: 100.0%; height: 100.0%;">Akira Sushi</div>`)[0];
                popup_aa67c996e2aa0da0d195b5546de1e3fe.setContent(html_200896190d628162be937c12aa9d4b9d);
            
        

        marker_eb19a9481913c21370a99278ef3d5400.bindPopup(popup_aa67c996e2aa0da0d195b5546de1e3fe)
        ;

        
    
    
            var marker_ad5626cee80dfc74b2d39547f62c3111 = L.marker(
                [51.02653123611505, 4.484300312030339],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_405e358f15514882f28604f3778e5e3e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_ad5626cee80dfc74b2d39547f62c3111.setIcon(icon_405e358f15514882f28604f3778e5e3e);
        
    
        var popup_4a958ab296e0cf3d031095f18c77a82f = L.popup({"maxWidth": "100%"});

        
            
                var html_80537973f23769b7a716b44b428ac895 = $(`<div id="html_80537973f23769b7a716b44b428ac895" style="width: 100.0%; height: 100.0%;">Alma Libre</div>`)[0];
                popup_4a958ab296e0cf3d031095f18c77a82f.setContent(html_80537973f23769b7a716b44b428ac895);
            
        

        marker_ad5626cee80dfc74b2d39547f62c3111.bindPopup(popup_4a958ab296e0cf3d031095f18c77a82f)
        ;

        
    
    
            var marker_791c39de90c752e0dadf2e2c36cc14ac = L.marker(
                [51.02666492485496, 4.482427023495477],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_da329719d6d94a226873b4016825be3e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_791c39de90c752e0dadf2e2c36cc14ac.setIcon(icon_da329719d6d94a226873b4016825be3e);
        
    
        var popup_3576d4fce608fccf1df9bef2c05e0823 = L.popup({"maxWidth": "100%"});

        
            
                var html_3d82cf4a4298b9e0790b1963766e8e83 = $(`<div id="html_3d82cf4a4298b9e0790b1963766e8e83" style="width: 100.0%; height: 100.0%;">Arax</div>`)[0];
                popup_3576d4fce608fccf1df9bef2c05e0823.setContent(html_3d82cf4a4298b9e0790b1963766e8e83);
            
        

        marker_791c39de90c752e0dadf2e2c36cc14ac.bindPopup(popup_3576d4fce608fccf1df9bef2c05e0823)
        ;

        
    
    
            var marker_ccdd9d61d702e31570fd218789d9b698 = L.marker(
                [51.03125750806047, 4.475799494916408],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_de73536911802436003c341eeda350d4 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_ccdd9d61d702e31570fd218789d9b698.setIcon(icon_de73536911802436003c341eeda350d4);
        
    
        var popup_44f13936adbc1a6e221620972406cabf = L.popup({"maxWidth": "100%"});

        
            
                var html_5af27aa7eb8fc4d27090c653b6bf4e17 = $(`<div id="html_5af27aa7eb8fc4d27090c653b6bf4e17" style="width: 100.0%; height: 100.0%;">Bakkerij 2800</div>`)[0];
                popup_44f13936adbc1a6e221620972406cabf.setContent(html_5af27aa7eb8fc4d27090c653b6bf4e17);
            
        

        marker_ccdd9d61d702e31570fd218789d9b698.bindPopup(popup_44f13936adbc1a6e221620972406cabf)
        ;

        
    
    
            var marker_f72cf802130a64983acbec98232a2801 = L.marker(
                [51.02706317712473, 4.480784993840994],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_ae741b30222d8083e4bb62e777e1b3e1 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_f72cf802130a64983acbec98232a2801.setIcon(icon_ae741b30222d8083e4bb62e777e1b3e1);
        
    
        var popup_0e18ce8528ea337646cc607aad09db8c = L.popup({"maxWidth": "100%"});

        
            
                var html_54d4e81ebec053ce2d5ced21ae0f32bc = $(`<div id="html_54d4e81ebec053ce2d5ced21ae0f32bc" style="width: 100.0%; height: 100.0%;">Basic Italian</div>`)[0];
                popup_0e18ce8528ea337646cc607aad09db8c.setContent(html_54d4e81ebec053ce2d5ced21ae0f32bc);
            
        

        marker_f72cf802130a64983acbec98232a2801.bindPopup(popup_0e18ce8528ea337646cc607aad09db8c)
        ;

        
    
    
            var marker_60f5e4b41d9a1592b3378daa6e5b9d27 = L.marker(
                [51.02678881440617, 4.48177502331029],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_231004b28287245d093745d4f1c7c1e3 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_60f5e4b41d9a1592b3378daa6e5b9d27.setIcon(icon_231004b28287245d093745d4f1c7c1e3);
        
    
        var popup_1592f79622c0466718279402d930b71b = L.popup({"maxWidth": "100%"});

        
            
                var html_5a96b171460e5e206733b7fe0fd2a488 = $(`<div id="html_5a96b171460e5e206733b7fe0fd2a488" style="width: 100.0%; height: 100.0%;">Belchicken</div>`)[0];
                popup_1592f79622c0466718279402d930b71b.setContent(html_5a96b171460e5e206733b7fe0fd2a488);
            
        

        marker_60f5e4b41d9a1592b3378daa6e5b9d27.bindPopup(popup_1592f79622c0466718279402d930b71b)
        ;

        
    
    
            var marker_56d312493d31c60cc5845b25d74f2868 = L.marker(
                [51.027201387290624, 4.4820863829715805],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_7e3066128c8aefbc1620c015adead8a3 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_56d312493d31c60cc5845b25d74f2868.setIcon(icon_7e3066128c8aefbc1620c015adead8a3);
        
    
        var popup_845eddf1d69f8a3be3c7db0aa6655249 = L.popup({"maxWidth": "100%"});

        
            
                var html_79485238f16742115d1422c1b5fbfacb = $(`<div id="html_79485238f16742115d1422c1b5fbfacb" style="width: 100.0%; height: 100.0%;">Bento</div>`)[0];
                popup_845eddf1d69f8a3be3c7db0aa6655249.setContent(html_79485238f16742115d1422c1b5fbfacb);
            
        

        marker_56d312493d31c60cc5845b25d74f2868.bindPopup(popup_845eddf1d69f8a3be3c7db0aa6655249)
        ;

        
    
    
            var marker_0a0efddcebb0ef25134a8b4411774976 = L.marker(
                [51.029048984316546, 4.488036083334339],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_c315d47051f9d8e11fcccf2787c04019 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_0a0efddcebb0ef25134a8b4411774976.setIcon(icon_c315d47051f9d8e11fcccf2787c04019);
        
    
        var popup_ff28a27c92620d067d7eb12f7765a5f7 = L.popup({"maxWidth": "100%"});

        
            
                var html_3841dc8cb13b45cf805ecffb6ebbf661 = $(`<div id="html_3841dc8cb13b45cf805ecffb6ebbf661" style="width: 100.0%; height: 100.0%;">Cafe Gourmand</div>`)[0];
                popup_ff28a27c92620d067d7eb12f7765a5f7.setContent(html_3841dc8cb13b45cf805ecffb6ebbf661);
            
        

        marker_0a0efddcebb0ef25134a8b4411774976.bindPopup(popup_ff28a27c92620d067d7eb12f7765a5f7)
        ;

        
    
    
            var marker_c9c3cd37035aab038a79e1892a4a401f = L.marker(
                [51.027788116605834, 4.480052542632645],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_39374c314af63ee375efb37a374be263 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_c9c3cd37035aab038a79e1892a4a401f.setIcon(icon_39374c314af63ee375efb37a374be263);
        
    
        var popup_c622c266744b6889531c03124fdc1821 = L.popup({"maxWidth": "100%"});

        
            
                var html_ba650569786914f981c21e1a54ef4876 = $(`<div id="html_ba650569786914f981c21e1a54ef4876" style="width: 100.0%; height: 100.0%;">Carlton</div>`)[0];
                popup_c622c266744b6889531c03124fdc1821.setContent(html_ba650569786914f981c21e1a54ef4876);
            
        

        marker_c9c3cd37035aab038a79e1892a4a401f.bindPopup(popup_c622c266744b6889531c03124fdc1821)
        ;

        
    
    
            var marker_3a03b4f65d4b500ca862641e30d2ec09 = L.marker(
                [51.03030799556643, 4.481969428274164],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_c2c482576cc3aa13a7271d1ac17401ad = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_3a03b4f65d4b500ca862641e30d2ec09.setIcon(icon_c2c482576cc3aa13a7271d1ac17401ad);
        
    
        var popup_206fc5c32da951736b118da0277c14f1 = L.popup({"maxWidth": "100%"});

        
            
                var html_9e6caf5d513c7669f4d738a01ccc3473 = $(`<div id="html_9e6caf5d513c7669f4d738a01ccc3473" style="width: 100.0%; height: 100.0%;">Chick 'n Dip</div>`)[0];
                popup_206fc5c32da951736b118da0277c14f1.setContent(html_9e6caf5d513c7669f4d738a01ccc3473);
            
        

        marker_3a03b4f65d4b500ca862641e30d2ec09.bindPopup(popup_206fc5c32da951736b118da0277c14f1)
        ;

        
    
    
            var marker_8d37eb0647843b589013070608bd2b3f = L.marker(
                [51.027612650201156, 4.4890654636098],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_d18e351fc3674873b51c3b0ee5795842 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_8d37eb0647843b589013070608bd2b3f.setIcon(icon_d18e351fc3674873b51c3b0ee5795842);
        
    
        var popup_793666638743f25b1a3823627b5000a6 = L.popup({"maxWidth": "100%"});

        
            
                var html_f9389e5982f7edfc7837cc6ccd3ea172 = $(`<div id="html_f9389e5982f7edfc7837cc6ccd3ea172" style="width: 100.0%; height: 100.0%;">China Keuken</div>`)[0];
                popup_793666638743f25b1a3823627b5000a6.setContent(html_f9389e5982f7edfc7837cc6ccd3ea172);
            
        

        marker_8d37eb0647843b589013070608bd2b3f.bindPopup(popup_793666638743f25b1a3823627b5000a6)
        ;

        
    
    
            var marker_ab8a4958c318bbfb5a14027364081c51 = L.marker(
                [51.026817443635686, 4.4813501830814175],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_2f6ca2b93044799e8aa70a63f523a5ac = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_ab8a4958c318bbfb5a14027364081c51.setIcon(icon_2f6ca2b93044799e8aa70a63f523a5ac);
        
    
        var popup_951366b732c37e7a271f35559095efa9 = L.popup({"maxWidth": "100%"});

        
            
                var html_afc3b60c9fb65fab3fdd23ade5f9abf6 = $(`<div id="html_afc3b60c9fb65fab3fdd23ade5f9abf6" style="width: 100.0%; height: 100.0%;">Chopsticks Wok Away</div>`)[0];
                popup_951366b732c37e7a271f35559095efa9.setContent(html_afc3b60c9fb65fab3fdd23ade5f9abf6);
            
        

        marker_ab8a4958c318bbfb5a14027364081c51.bindPopup(popup_951366b732c37e7a271f35559095efa9)
        ;

        
    
    
            var marker_237ff9507c3fedabe3c090952cebd09a = L.marker(
                [51.02823431476486, 4.479066830863199],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_5bf77e623583728cc118ea0ffd483523 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_237ff9507c3fedabe3c090952cebd09a.setIcon(icon_5bf77e623583728cc118ea0ffd483523);
        
    
        var popup_9184ff9752b64ea38911c5f48344cdae = L.popup({"maxWidth": "100%"});

        
            
                var html_4393f80d42c79bc2e88363fd212d0fe9 = $(`<div id="html_4393f80d42c79bc2e88363fd212d0fe9" style="width: 100.0%; height: 100.0%;">Coffee & Cake </div>`)[0];
                popup_9184ff9752b64ea38911c5f48344cdae.setContent(html_4393f80d42c79bc2e88363fd212d0fe9);
            
        

        marker_237ff9507c3fedabe3c090952cebd09a.bindPopup(popup_9184ff9752b64ea38911c5f48344cdae)
        ;

        
    
    
            var marker_415ec44eaa7bb369ad15fe043e615ebc = L.marker(
                [51.028067440867446, 4.479722611520775],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_352a73a677f69459e07e2c0714814ccf = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_415ec44eaa7bb369ad15fe043e615ebc.setIcon(icon_352a73a677f69459e07e2c0714814ccf);
        
    
        var popup_dbcfcaf1a77a8b7958e08c0337142f95 = L.popup({"maxWidth": "100%"});

        
            
                var html_18da1b867aa8b6cf2e723e61cae62a03 = $(`<div id="html_18da1b867aa8b6cf2e723e61cae62a03" style="width: 100.0%; height: 100.0%;">Cook Mazi</div>`)[0];
                popup_dbcfcaf1a77a8b7958e08c0337142f95.setContent(html_18da1b867aa8b6cf2e723e61cae62a03);
            
        

        marker_415ec44eaa7bb369ad15fe043e615ebc.bindPopup(popup_dbcfcaf1a77a8b7958e08c0337142f95)
        ;

        
    
    
            var marker_c8344ae69b5a49b28ee357999b94295b = L.marker(
                [51.106561593796705, 4.534846155047411],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_3e43a4fd601dab18bb8b703266d34e6b = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_c8344ae69b5a49b28ee357999b94295b.setIcon(icon_3e43a4fd601dab18bb8b703266d34e6b);
        
    
        var popup_a1e052dff66c79e5166f877d30aa0dda = L.popup({"maxWidth": "100%"});

        
            
                var html_55301be703dff7ed7e9f5a0a8007231a = $(`<div id="html_55301be703dff7ed7e9f5a0a8007231a" style="width: 100.0%; height: 100.0%;">De Kabas</div>`)[0];
                popup_a1e052dff66c79e5166f877d30aa0dda.setContent(html_55301be703dff7ed7e9f5a0a8007231a);
            
        

        marker_c8344ae69b5a49b28ee357999b94295b.bindPopup(popup_a1e052dff66c79e5166f877d30aa0dda)
        ;

        
    
    
            var marker_122e61a992fe675e78b41d35c70a3e1f = L.marker(
                [51.026606195701895, 4.484193921782128],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_e09fd7181d530268354c4a3ccaf6f945 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_122e61a992fe675e78b41d35c70a3e1f.setIcon(icon_e09fd7181d530268354c4a3ccaf6f945);
        
    
        var popup_d2941d971bb7aa162229a4d6d6af99b9 = L.popup({"maxWidth": "100%"});

        
            
                var html_a2054fd09a31d2f4466dbefa39d64099 = $(`<div id="html_a2054fd09a31d2f4466dbefa39d64099" style="width: 100.0%; height: 100.0%;">De Vleeshalle</div>`)[0];
                popup_d2941d971bb7aa162229a4d6d6af99b9.setContent(html_a2054fd09a31d2f4466dbefa39d64099);
            
        

        marker_122e61a992fe675e78b41d35c70a3e1f.bindPopup(popup_d2941d971bb7aa162229a4d6d6af99b9)
        ;

        
    
    
            var marker_9a797fe7882e94de43d64086b14daf70 = L.marker(
                [51.02837348722631, 4.480969858111789],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_e4774fe5a25390048121b2ae1d73005c = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_9a797fe7882e94de43d64086b14daf70.setIcon(icon_e4774fe5a25390048121b2ae1d73005c);
        
    
        var popup_865fdc79246848c3cd22d2d1b83c2d22 = L.popup({"maxWidth": "100%"});

        
            
                var html_2dec679226ec934b2fbf0d0bd2898399 = $(`<div id="html_2dec679226ec934b2fbf0d0bd2898399" style="width: 100.0%; height: 100.0%;">Den Amitie</div>`)[0];
                popup_865fdc79246848c3cd22d2d1b83c2d22.setContent(html_2dec679226ec934b2fbf0d0bd2898399);
            
        

        marker_9a797fe7882e94de43d64086b14daf70.bindPopup(popup_865fdc79246848c3cd22d2d1b83c2d22)
        ;

        
    
    
            var marker_613b16917a9fe0570fd9f70d44917d3e = L.marker(
                [51.028473380611025, 4.483017614481535],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_386ac50bc767a0b8184813c2c00155c8 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_613b16917a9fe0570fd9f70d44917d3e.setIcon(icon_386ac50bc767a0b8184813c2c00155c8);
        
    
        var popup_89638be2c5a6c86043b2a02271c15ad8 = L.popup({"maxWidth": "100%"});

        
            
                var html_f05cfae007e9526cad65c1047c292292 = $(`<div id="html_f05cfae007e9526cad65c1047c292292" style="width: 100.0%; height: 100.0%;">Den Troef</div>`)[0];
                popup_89638be2c5a6c86043b2a02271c15ad8.setContent(html_f05cfae007e9526cad65c1047c292292);
            
        

        marker_613b16917a9fe0570fd9f70d44917d3e.bindPopup(popup_89638be2c5a6c86043b2a02271c15ad8)
        ;

        
    
    
            var marker_b88c55555063b40bec2f65e9c41a5592 = L.marker(
                [51.02846660316853, 4.47824038482074],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_a82d76178443b5a8da130632f52eb163 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_b88c55555063b40bec2f65e9c41a5592.setIcon(icon_a82d76178443b5a8da130632f52eb163);
        
    
        var popup_411f40e813d3bf73be632982c6a9ec2d = L.popup({"maxWidth": "100%"});

        
            
                var html_06c3556e486931473485218e855fd4f2 = $(`<div id="html_06c3556e486931473485218e855fd4f2" style="width: 100.0%; height: 100.0%;">Fast2Go</div>`)[0];
                popup_411f40e813d3bf73be632982c6a9ec2d.setContent(html_06c3556e486931473485218e855fd4f2);
            
        

        marker_b88c55555063b40bec2f65e9c41a5592.bindPopup(popup_411f40e813d3bf73be632982c6a9ec2d)
        ;

        
    
    
            var marker_c882c46c8d39288de1e449b7e160027e = L.marker(
                [51.03024360666302, 4.490886029448086],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_a0c6b6de863dfbf61822f40cdcfd677e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_c882c46c8d39288de1e449b7e160027e.setIcon(icon_a0c6b6de863dfbf61822f40cdcfd677e);
        
    
        var popup_5c8ae873b2bd2eed8c8c27a0a096ae5d = L.popup({"maxWidth": "100%"});

        
            
                var html_fc81aae8a908e42ef81d225a00fb1ec0 = $(`<div id="html_fc81aae8a908e42ef81d225a00fb1ec0" style="width: 100.0%; height: 100.0%;">Friethuis 1958</div>`)[0];
                popup_5c8ae873b2bd2eed8c8c27a0a096ae5d.setContent(html_fc81aae8a908e42ef81d225a00fb1ec0);
            
        

        marker_c882c46c8d39288de1e449b7e160027e.bindPopup(popup_5c8ae873b2bd2eed8c8c27a0a096ae5d)
        ;

        
    
    
            var marker_b2e39de6e5882c2c0def117a90352213 = L.marker(
                [51.028658913125454, 4.4779507062615735],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_02dabbfedff620d08ee0e5f92ccaf2ca = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_b2e39de6e5882c2c0def117a90352213.setIcon(icon_02dabbfedff620d08ee0e5f92ccaf2ca);
        
    
        var popup_49c5afb3c9be29c5f3f6e92b856a8b0e = L.popup({"maxWidth": "100%"});

        
            
                var html_c45413ee2988419187b640cf036416f5 = $(`<div id="html_c45413ee2988419187b640cf036416f5" style="width: 100.0%; height: 100.0%;">Funky Jungle</div>`)[0];
                popup_49c5afb3c9be29c5f3f6e92b856a8b0e.setContent(html_c45413ee2988419187b640cf036416f5);
            
        

        marker_b2e39de6e5882c2c0def117a90352213.bindPopup(popup_49c5afb3c9be29c5f3f6e92b856a8b0e)
        ;

        
    
    
            var marker_5b5c752de82cd86d6c6b3d30728775a0 = L.marker(
                [51.02862201251633, 4.48058127711483],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_cfd7c9e0f8638d6b96d1b3a7665591ad = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_5b5c752de82cd86d6c6b3d30728775a0.setIcon(icon_cfd7c9e0f8638d6b96d1b3a7665591ad);
        
    
        var popup_6853ddf7f8ec4a1e536049af616ef581 = L.popup({"maxWidth": "100%"});

        
            
                var html_19597b022c8c001b339e2fddb5671c87 = $(`<div id="html_19597b022c8c001b339e2fddb5671c87" style="width: 100.0%; height: 100.0%;">Gastrobar Isajé</div>`)[0];
                popup_6853ddf7f8ec4a1e536049af616ef581.setContent(html_19597b022c8c001b339e2fddb5671c87);
            
        

        marker_5b5c752de82cd86d6c6b3d30728775a0.bindPopup(popup_6853ddf7f8ec4a1e536049af616ef581)
        ;

        
    
    
            var marker_2b65ff41124068d16a3dd0e2d52f301e = L.marker(
                [51.027269544535486, 4.48081913278635],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_de0bfc5a96ff28f5060317672e9032fe = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_2b65ff41124068d16a3dd0e2d52f301e.setIcon(icon_de0bfc5a96ff28f5060317672e9032fe);
        
    
        var popup_568b87c2fbc71a303153ac72e073fb78 = L.popup({"maxWidth": "100%"});

        
            
                var html_86dcbdd871a6fa35deab55ded71c4a74 = $(`<div id="html_86dcbdd871a6fa35deab55ded71c4a74" style="width: 100.0%; height: 100.0%;">Hitea</div>`)[0];
                popup_568b87c2fbc71a303153ac72e073fb78.setContent(html_86dcbdd871a6fa35deab55ded71c4a74);
            
        

        marker_2b65ff41124068d16a3dd0e2d52f301e.bindPopup(popup_568b87c2fbc71a303153ac72e073fb78)
        ;

        
    
    
            var marker_fe6a6c3850796cc75eb486e54548a9ee = L.marker(
                [51.029723742089566, 4.479769496175425],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_a492ca1f0750167b636a0b2cf06ccc66 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_fe6a6c3850796cc75eb486e54548a9ee.setIcon(icon_a492ca1f0750167b636a0b2cf06ccc66);
        
    
        var popup_beb87fb45169dd4eb2b3025cad923806 = L.popup({"maxWidth": "100%"});

        
            
                var html_97fc9bf9a49afb5c21cfd75872d6f90e = $(`<div id="html_97fc9bf9a49afb5c21cfd75872d6f90e" style="width: 100.0%; height: 100.0%;">il cardinale</div>`)[0];
                popup_beb87fb45169dd4eb2b3025cad923806.setContent(html_97fc9bf9a49afb5c21cfd75872d6f90e);
            
        

        marker_fe6a6c3850796cc75eb486e54548a9ee.bindPopup(popup_beb87fb45169dd4eb2b3025cad923806)
        ;

        
    
    
            var marker_eae87ac861335ba34bf2ce533a4f4fbe = L.marker(
                [51.02701128690949, 4.480894048806079],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_057a18e2ea2674809a1fbf5343ba629d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_eae87ac861335ba34bf2ce533a4f4fbe.setIcon(icon_057a18e2ea2674809a1fbf5343ba629d);
        
    
        var popup_31386b51dd9da9b70a218ffb146499d7 = L.popup({"maxWidth": "100%"});

        
            
                var html_636780b7d154f3a8b68a5365de94a289 = $(`<div id="html_636780b7d154f3a8b68a5365de94a289" style="width: 100.0%; height: 100.0%;">Izy Coffee Mechelen</div>`)[0];
                popup_31386b51dd9da9b70a218ffb146499d7.setContent(html_636780b7d154f3a8b68a5365de94a289);
            
        

        marker_eae87ac861335ba34bf2ce533a4f4fbe.bindPopup(popup_31386b51dd9da9b70a218ffb146499d7)
        ;

        
    
    
            var marker_d55357e0dcc6a141ed39df1a08c796da = L.marker(
                [51.028681352085094, 4.480456215111046],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_c700664ea5e660f73b9f60e068ec1b56 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_d55357e0dcc6a141ed39df1a08c796da.setIcon(icon_c700664ea5e660f73b9f60e068ec1b56);
        
    
        var popup_56e4addb28655d6b8954f29c14621efd = L.popup({"maxWidth": "100%"});

        
            
                var html_f3bc4843145546aa906010fcfb560e91 = $(`<div id="html_f3bc4843145546aa906010fcfb560e91" style="width: 100.0%; height: 100.0%;">Ka&Do Snack</div>`)[0];
                popup_56e4addb28655d6b8954f29c14621efd.setContent(html_f3bc4843145546aa906010fcfb560e91);
            
        

        marker_d55357e0dcc6a141ed39df1a08c796da.bindPopup(popup_56e4addb28655d6b8954f29c14621efd)
        ;

        
    
    
            var marker_59d749fb60d95d4274899187c1792a4b = L.marker(
                [51.02859821346271, 4.482746711384538],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_fc7e09672031e7cf00087f2dce67762d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_59d749fb60d95d4274899187c1792a4b.setIcon(icon_fc7e09672031e7cf00087f2dce67762d);
        
    
        var popup_7d2e250f17df8cf699cedb08188dc9d0 = L.popup({"maxWidth": "100%"});

        
            
                var html_b7ec571dbaab8e11a724f899d361052d = $(`<div id="html_b7ec571dbaab8e11a724f899d361052d" style="width: 100.0%; height: 100.0%;">Knabbel en Babbel</div>`)[0];
                popup_7d2e250f17df8cf699cedb08188dc9d0.setContent(html_b7ec571dbaab8e11a724f899d361052d);
            
        

        marker_59d749fb60d95d4274899187c1792a4b.bindPopup(popup_7d2e250f17df8cf699cedb08188dc9d0)
        ;

        
    
    
            var marker_bf6d290eb37ff418396e87abbb9cd445 = L.marker(
                [51.02980066709835, 4.477656514637044],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_36339f9fba802d50ff75aaffbf7e6fe9 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_bf6d290eb37ff418396e87abbb9cd445.setIcon(icon_36339f9fba802d50ff75aaffbf7e6fe9);
        
    
        var popup_f2f02c33bac053c3f74e1def571db91e = L.popup({"maxWidth": "100%"});

        
            
                var html_9b839bc8ac65bf68463e8a886ee0486d = $(`<div id="html_9b839bc8ac65bf68463e8a886ee0486d" style="width: 100.0%; height: 100.0%;">Lange Asem</div>`)[0];
                popup_f2f02c33bac053c3f74e1def571db91e.setContent(html_9b839bc8ac65bf68463e8a886ee0486d);
            
        

        marker_bf6d290eb37ff418396e87abbb9cd445.bindPopup(popup_f2f02c33bac053c3f74e1def571db91e)
        ;

        
    
    
            var marker_5980544a84338382496ee020515cea42 = L.marker(
                [51.02810391116244, 4.478049947976537],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_ab95e08c3277fa8742137172bdad03c2 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_5980544a84338382496ee020515cea42.setIcon(icon_ab95e08c3277fa8742137172bdad03c2);
        
    
        var popup_c66d3e3ab9d1a1e8c857e2b0327a0221 = L.popup({"maxWidth": "100%"});

        
            
                var html_2df77e182131eed8654652a3d28ac6dc = $(`<div id="html_2df77e182131eed8654652a3d28ac6dc" style="width: 100.0%; height: 100.0%;">l'Artista</div>`)[0];
                popup_c66d3e3ab9d1a1e8c857e2b0327a0221.setContent(html_2df77e182131eed8654652a3d28ac6dc);
            
        

        marker_5980544a84338382496ee020515cea42.bindPopup(popup_c66d3e3ab9d1a1e8c857e2b0327a0221)
        ;

        
    
    
            var marker_8fb5a6a87fc893d28e369e5fc0f41ed5 = L.marker(
                [51.028328783387046, 4.478763741259628],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_b4b99cada21a3694a43885600c00a8aa = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_8fb5a6a87fc893d28e369e5fc0f41ed5.setIcon(icon_b4b99cada21a3694a43885600c00a8aa);
        
    
        var popup_29d520519a27de7619e1ef59bc820274 = L.popup({"maxWidth": "100%"});

        
            
                var html_e9c53731d9410eb40247a0b6c60900b4 = $(`<div id="html_e9c53731d9410eb40247a0b6c60900b4" style="width: 100.0%; height: 100.0%;">Los Bandidos</div>`)[0];
                popup_29d520519a27de7619e1ef59bc820274.setContent(html_e9c53731d9410eb40247a0b6c60900b4);
            
        

        marker_8fb5a6a87fc893d28e369e5fc0f41ed5.bindPopup(popup_29d520519a27de7619e1ef59bc820274)
        ;

        
    
    
            var marker_e3e69111a832b24569aedc62af3880e1 = L.marker(
                [51.02874351976263, 4.484097400476482],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_36bc662888d3fec7c10a09a7bd2b8337 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_e3e69111a832b24569aedc62af3880e1.setIcon(icon_36bc662888d3fec7c10a09a7bd2b8337);
        
    
        var popup_98ebe416b790f01fae1ea8e88344ca95 = L.popup({"maxWidth": "100%"});

        
            
                var html_65ab2fcfaf77168263d1976a9c24c066 = $(`<div id="html_65ab2fcfaf77168263d1976a9c24c066" style="width: 100.0%; height: 100.0%;">My Kebab</div>`)[0];
                popup_98ebe416b790f01fae1ea8e88344ca95.setContent(html_65ab2fcfaf77168263d1976a9c24c066);
            
        

        marker_e3e69111a832b24569aedc62af3880e1.bindPopup(popup_98ebe416b790f01fae1ea8e88344ca95)
        ;

        
    
    
            var marker_04406811b7a7a9216eaa015761535d6e = L.marker(
                [51.027046363474405, 4.482545988247778],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_e5e0a894db9e880d4e6955da8959cc44 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_04406811b7a7a9216eaa015761535d6e.setIcon(icon_e5e0a894db9e880d4e6955da8959cc44);
        
    
        var popup_22881f1f894b0c5add3dc6aab8816eaa = L.popup({"maxWidth": "100%"});

        
            
                var html_4747bb88129703a3377015bbce5ec59a = $(`<div id="html_4747bb88129703a3377015bbce5ec59a" style="width: 100.0%; height: 100.0%;">Oriental Asian Food</div>`)[0];
                popup_22881f1f894b0c5add3dc6aab8816eaa.setContent(html_4747bb88129703a3377015bbce5ec59a);
            
        

        marker_04406811b7a7a9216eaa015761535d6e.bindPopup(popup_22881f1f894b0c5add3dc6aab8816eaa)
        ;

        
    
    
            var marker_b0ca62fa5aecd7c32fb123828ceb8231 = L.marker(
                [51.02791885563856, 4.479135227195287],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_24ba2d42b2f49102b8685f92ab213088 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_b0ca62fa5aecd7c32fb123828ceb8231.setIcon(icon_24ba2d42b2f49102b8685f92ab213088);
        
    
        var popup_56d4e84a1f6c85f2cc9e4519b7ebe663 = L.popup({"maxWidth": "100%"});

        
            
                var html_c553d98f46d16a073804259db1400dea = $(`<div id="html_c553d98f46d16a073804259db1400dea" style="width: 100.0%; height: 100.0%;">O'Tacos</div>`)[0];
                popup_56d4e84a1f6c85f2cc9e4519b7ebe663.setContent(html_c553d98f46d16a073804259db1400dea);
            
        

        marker_b0ca62fa5aecd7c32fb123828ceb8231.bindPopup(popup_56d4e84a1f6c85f2cc9e4519b7ebe663)
        ;

        
    
    
            var marker_8a1aa4dddc4be7f449bd8ff0d41d9697 = L.marker(
                [51.02653119202592, 4.484707996175252],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_f047495e4571298a104aeabbcdae01e0 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_8a1aa4dddc4be7f449bd8ff0d41d9697.setIcon(icon_f047495e4571298a104aeabbcdae01e0);
        
    
        var popup_e99fb36c579bad46443856fcc59436b6 = L.popup({"maxWidth": "100%"});

        
            
                var html_3deaa841793cdfe83d4959db371756eb = $(`<div id="html_3deaa841793cdfe83d4959db371756eb" style="width: 100.0%; height: 100.0%;">Pizzeria Margherita</div>`)[0];
                popup_e99fb36c579bad46443856fcc59436b6.setContent(html_3deaa841793cdfe83d4959db371756eb);
            
        

        marker_8a1aa4dddc4be7f449bd8ff0d41d9697.bindPopup(popup_e99fb36c579bad46443856fcc59436b6)
        ;

        
    
    
            var marker_3b3b3ec814de73f9f6fff653a595b3f2 = L.marker(
                [51.03117579667119, 4.475893383625842],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_91df24ab1ecb9ddeab6e1f2a97b08033 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_3b3b3ec814de73f9f6fff653a595b3f2.setIcon(icon_91df24ab1ecb9ddeab6e1f2a97b08033);
        
    
        var popup_1319aaf397ccd791f50c2cc9f776377d = L.popup({"maxWidth": "100%"});

        
            
                var html_cd50c61471a914a895012604264ec061 = $(`<div id="html_cd50c61471a914a895012604264ec061" style="width: 100.0%; height: 100.0%;">Pizzeria Sicilia</div>`)[0];
                popup_1319aaf397ccd791f50c2cc9f776377d.setContent(html_cd50c61471a914a895012604264ec061);
            
        

        marker_3b3b3ec814de73f9f6fff653a595b3f2.bindPopup(popup_1319aaf397ccd791f50c2cc9f776377d)
        ;

        
    
    
            var marker_125e488f38e037d351821066405bab51 = L.marker(
                [51.02704602615836, 4.482448089257117],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_d65f5beaca62cd5f066c0350c7c3c48f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_125e488f38e037d351821066405bab51.setIcon(icon_d65f5beaca62cd5f066c0350c7c3c48f);
        
    
        var popup_51bee20c70b66fab6b0a118ccd095cd6 = L.popup({"maxWidth": "100%"});

        
            
                var html_53cf1e1526f0325b1c2511a849443bb4 = $(`<div id="html_53cf1e1526f0325b1c2511a849443bb4" style="width: 100.0%; height: 100.0%;">Pomfritz</div>`)[0];
                popup_51bee20c70b66fab6b0a118ccd095cd6.setContent(html_53cf1e1526f0325b1c2511a849443bb4);
            
        

        marker_125e488f38e037d351821066405bab51.bindPopup(popup_51bee20c70b66fab6b0a118ccd095cd6)
        ;

        
    
    
            var marker_d1ec25c3c0e2efa2ef075c62b8a115c6 = L.marker(
                [51.02772603479155, 4.480072044067321],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_a75cc9142a86e3267c617e67de6e93f5 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_d1ec25c3c0e2efa2ef075c62b8a115c6.setIcon(icon_a75cc9142a86e3267c617e67de6e93f5);
        
    
        var popup_13e81f9430067027bb80c554f41c5e34 = L.popup({"maxWidth": "100%"});

        
            
                var html_189baf2697eaaa0ccb0686c8e87e2a3f = $(`<div id="html_189baf2697eaaa0ccb0686c8e87e2a3f" style="width: 100.0%; height: 100.0%;">Restaurant Den Beer</div>`)[0];
                popup_13e81f9430067027bb80c554f41c5e34.setContent(html_189baf2697eaaa0ccb0686c8e87e2a3f);
            
        

        marker_d1ec25c3c0e2efa2ef075c62b8a115c6.bindPopup(popup_13e81f9430067027bb80c554f41c5e34)
        ;

        
    
    
            var marker_8a71cc79e5aef9f76d7d270f2279ce2a = L.marker(
                [51.02838362436489, 4.482052078706885],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_47c5155b947da371c3dd8a0ea6b0de2c = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_8a71cc79e5aef9f76d7d270f2279ce2a.setIcon(icon_47c5155b947da371c3dd8a0ea6b0de2c);
        
    
        var popup_e8c45cdd2e7c3912efca9456e67eedce = L.popup({"maxWidth": "100%"});

        
            
                var html_dfe7971495eaa54687eccd4856c4548e = $(`<div id="html_dfe7971495eaa54687eccd4856c4548e" style="width: 100.0%; height: 100.0%;">Sandwisjbar aan't stadhuis</div>`)[0];
                popup_e8c45cdd2e7c3912efca9456e67eedce.setContent(html_dfe7971495eaa54687eccd4856c4548e);
            
        

        marker_8a71cc79e5aef9f76d7d270f2279ce2a.bindPopup(popup_e8c45cdd2e7c3912efca9456e67eedce)
        ;

        
    
    
            var marker_ee63302817e3b88709b91cdb1b7167e5 = L.marker(
                [51.02878400589378, 4.484479615242049],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_ecfc963c9dbf07256f9149c24795a863 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_ee63302817e3b88709b91cdb1b7167e5.setIcon(icon_ecfc963c9dbf07256f9149c24795a863);
        
    
        var popup_6181dadc4a403d8acdd527af7034744c = L.popup({"maxWidth": "100%"});

        
            
                var html_0d59d476b0185a7feb98655b2153a078 = $(`<div id="html_0d59d476b0185a7feb98655b2153a078" style="width: 100.0%; height: 100.0%;">Snack Antalya</div>`)[0];
                popup_6181dadc4a403d8acdd527af7034744c.setContent(html_0d59d476b0185a7feb98655b2153a078);
            
        

        marker_ee63302817e3b88709b91cdb1b7167e5.bindPopup(popup_6181dadc4a403d8acdd527af7034744c)
        ;

        
    
    
            var marker_333d647da4a6db55ab4a759224c5264c = L.marker(
                [51.028799187302525, 4.4847730103695165],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_06ab1b2b26cf45629c4cbac3603aafc4 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_333d647da4a6db55ab4a759224c5264c.setIcon(icon_06ab1b2b26cf45629c4cbac3603aafc4);
        
    
        var popup_99024775f7c974ccacba7db8044368aa = L.popup({"maxWidth": "100%"});

        
            
                var html_5728460c5ecb3c63510335acfb78a819 = $(`<div id="html_5728460c5ecb3c63510335acfb78a819" style="width: 100.0%; height: 100.0%;">Supersmos</div>`)[0];
                popup_99024775f7c974ccacba7db8044368aa.setContent(html_5728460c5ecb3c63510335acfb78a819);
            
        

        marker_333d647da4a6db55ab4a759224c5264c.bindPopup(popup_99024775f7c974ccacba7db8044368aa)
        ;

        
    
    
            var marker_82a6b6976cea264a42692c6903692d25 = L.marker(
                [51.028242270254985, 4.482494583749707],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_5b04f204ece49fd44dac9ebdb237c29c = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_82a6b6976cea264a42692c6903692d25.setIcon(icon_5b04f204ece49fd44dac9ebdb237c29c);
        
    
        var popup_0bfa2dc37d706e2a006ba78fa5fb8c60 = L.popup({"maxWidth": "100%"});

        
            
                var html_779b015472c86fe3772c727015ff34c5 = $(`<div id="html_779b015472c86fe3772c727015ff34c5" style="width: 100.0%; height: 100.0%;">Také</div>`)[0];
                popup_0bfa2dc37d706e2a006ba78fa5fb8c60.setContent(html_779b015472c86fe3772c727015ff34c5);
            
        

        marker_82a6b6976cea264a42692c6903692d25.bindPopup(popup_0bfa2dc37d706e2a006ba78fa5fb8c60)
        ;

        
    
    
            var marker_9e498d179a8dbc1ae4edcdb752387355 = L.marker(
                [51.02834008302513, 4.478690995951955],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_31af054ff10d863847c1182b4318647e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_9e498d179a8dbc1ae4edcdb752387355.setIcon(icon_31af054ff10d863847c1182b4318647e);
        
    
        var popup_f12b278852d6fe038d197ebaec44e4dd = L.popup({"maxWidth": "100%"});

        
            
                var html_316d3b261406914d1cd2f233c75384ec = $(`<div id="html_316d3b261406914d1cd2f233c75384ec" style="width: 100.0%; height: 100.0%;">Tangthai</div>`)[0];
                popup_f12b278852d6fe038d197ebaec44e4dd.setContent(html_316d3b261406914d1cd2f233c75384ec);
            
        

        marker_9e498d179a8dbc1ae4edcdb752387355.bindPopup(popup_f12b278852d6fe038d197ebaec44e4dd)
        ;

        
    
    
            var marker_d8a1e59d71fcff3dbd5df878ed0876d6 = L.marker(
                [51.02653119202592, 4.484707996175252],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_6c1a1a8121a7c5de961066072e803c06 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_d8a1e59d71fcff3dbd5df878ed0876d6.setIcon(icon_6c1a1a8121a7c5de961066072e803c06);
        
    
        var popup_82064b2affdcbaa670aa91a5e299a2c3 = L.popup({"maxWidth": "100%"});

        
            
                var html_bb7b00f96d81b9fac2e7cf745a55a6d7 = $(`<div id="html_bb7b00f96d81b9fac2e7cf745a55a6d7" style="width: 100.0%; height: 100.0%;">Tapas La Qia</div>`)[0];
                popup_82064b2affdcbaa670aa91a5e299a2c3.setContent(html_bb7b00f96d81b9fac2e7cf745a55a6d7);
            
        

        marker_d8a1e59d71fcff3dbd5df878ed0876d6.bindPopup(popup_82064b2affdcbaa670aa91a5e299a2c3)
        ;

        
    
    
            var marker_e7a2c2d9041fd740c584a1994f36c9d3 = L.marker(
                [51.02743801194268, 4.481856864770718],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_b32b74751bc1c9d819881cc11087a504 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_e7a2c2d9041fd740c584a1994f36c9d3.setIcon(icon_b32b74751bc1c9d819881cc11087a504);
        
    
        var popup_7bb5891bcd9a97e430ff9d13ecbcdce6 = L.popup({"maxWidth": "100%"});

        
            
                var html_3b142adb359fbfc5920e5439dc734d56 = $(`<div id="html_3b142adb359fbfc5920e5439dc734d56" style="width: 100.0%; height: 100.0%;">Thaison</div>`)[0];
                popup_7bb5891bcd9a97e430ff9d13ecbcdce6.setContent(html_3b142adb359fbfc5920e5439dc734d56);
            
        

        marker_e7a2c2d9041fd740c584a1994f36c9d3.bindPopup(popup_7bb5891bcd9a97e430ff9d13ecbcdce6)
        ;

        
    
    
            var marker_264e00c51d98453e27fcd706c3c05e0a = L.marker(
                [51.02874942399231, 4.484038391881097],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_170d8e40defdc9f74c03b8565ca81fc1 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_264e00c51d98453e27fcd706c3c05e0a.setIcon(icon_170d8e40defdc9f74c03b8565ca81fc1);
        
    
        var popup_131366b0c8c3af8a589816eea0eb9fc6 = L.popup({"maxWidth": "100%"});

        
            
                var html_477d8de596613c25f1243a16181f19fe = $(`<div id="html_477d8de596613c25f1243a16181f19fe" style="width: 100.0%; height: 100.0%;">Trattoria Boretti</div>`)[0];
                popup_131366b0c8c3af8a589816eea0eb9fc6.setContent(html_477d8de596613c25f1243a16181f19fe);
            
        

        marker_264e00c51d98453e27fcd706c3c05e0a.bindPopup(popup_131366b0c8c3af8a589816eea0eb9fc6)
        ;

        
    
    
            var marker_581dbb0195dcc90f9e6453a3fbec37e5 = L.marker(
                [51.02915992742419, 4.480083062361279],
                {}
            ).addTo(feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c);
        
    
            var icon_d761d184d7e4562db876dbda7b1d5391 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_581dbb0195dcc90f9e6453a3fbec37e5.setIcon(icon_d761d184d7e4562db876dbda7b1d5391);
        
    
        var popup_4da4cec8d01eccb76aa0da09e6485aa9 = L.popup({"maxWidth": "100%"});

        
            
                var html_17fa4ada9a8903c8bfd9e06da020c056 = $(`<div id="html_17fa4ada9a8903c8bfd9e06da020c056" style="width: 100.0%; height: 100.0%;">Zorba</div>`)[0];
                popup_4da4cec8d01eccb76aa0da09e6485aa9.setContent(html_17fa4ada9a8903c8bfd9e06da020c056);
            
        

        marker_581dbb0195dcc90f9e6453a3fbec37e5.bindPopup(popup_4da4cec8d01eccb76aa0da09e6485aa9)
        ;

        
    
    
            var feature_group_0af39c2523be50e1713daf93775e0e3b = L.featureGroup(
                {}
            );
        
    
            var marker_ac5bfd58998a766ff225ef2d6f0398dd = L.marker(
                [51.01859441098931, 4.482972661774999],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_c6745151a90c27480f65de8892fda180 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_ac5bfd58998a766ff225ef2d6f0398dd.setIcon(icon_c6745151a90c27480f65de8892fda180);
        
    
        var popup_195dda888d57e8ecd808b6d1793d87cb = L.popup({"maxWidth": "100%"});

        
            
                var html_133bb8dc8215d6f1ced49ad02ca21e8a = $(`<div id="html_133bb8dc8215d6f1ced49ad02ca21e8a" style="width: 100.0%; height: 100.0%;">Ali Baba Mechelen</div>`)[0];
                popup_195dda888d57e8ecd808b6d1793d87cb.setContent(html_133bb8dc8215d6f1ced49ad02ca21e8a);
            
        

        marker_ac5bfd58998a766ff225ef2d6f0398dd.bindPopup(popup_195dda888d57e8ecd808b6d1793d87cb)
        ;

        
    
    
            var marker_3c9d4a01da1f2b3c9d3e8e9cd340b979 = L.marker(
                [51.02563088409474, 4.476900158497686],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_88f870153848a392847ec33b2be1d379 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_3c9d4a01da1f2b3c9d3e8e9cd340b979.setIcon(icon_88f870153848a392847ec33b2be1d379);
        
    
        var popup_7c798482a3cd3467b000675e131a4e58 = L.popup({"maxWidth": "100%"});

        
            
                var html_4e209fb71e6ef5cc2baec0f799c4f25b = $(`<div id="html_4e209fb71e6ef5cc2baec0f799c4f25b" style="width: 100.0%; height: 100.0%;">Bar Bao</div>`)[0];
                popup_7c798482a3cd3467b000675e131a4e58.setContent(html_4e209fb71e6ef5cc2baec0f799c4f25b);
            
        

        marker_3c9d4a01da1f2b3c9d3e8e9cd340b979.bindPopup(popup_7c798482a3cd3467b000675e131a4e58)
        ;

        
    
    
            var marker_61323aa53bb08781f2150fc741b8e323 = L.marker(
                [51.02743638459346, 4.4789635658266915],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_4b0d5ea5665143197887e25557f978a3 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_61323aa53bb08781f2150fc741b8e323.setIcon(icon_4b0d5ea5665143197887e25557f978a3);
        
    
        var popup_f68473fd43e36b70d31064b40d1a8e15 = L.popup({"maxWidth": "100%"});

        
            
                var html_a3608d34f32f943049bd3e5d4a1eda5d = $(`<div id="html_a3608d34f32f943049bd3e5d4a1eda5d" style="width: 100.0%; height: 100.0%;">Bavet</div>`)[0];
                popup_f68473fd43e36b70d31064b40d1a8e15.setContent(html_a3608d34f32f943049bd3e5d4a1eda5d);
            
        

        marker_61323aa53bb08781f2150fc741b8e323.bindPopup(popup_f68473fd43e36b70d31064b40d1a8e15)
        ;

        
    
    
            var marker_f0ce08b6f38aba2153c3cdf4a2c6bd05 = L.marker(
                [51.026677183742976, 4.4787257966502425],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_ae015c66177cf2391c40a8802eac67af = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_f0ce08b6f38aba2153c3cdf4a2c6bd05.setIcon(icon_ae015c66177cf2391c40a8802eac67af);
        
    
        var popup_a7b9406ce9e96cebd19597d4f9a56af0 = L.popup({"maxWidth": "100%"});

        
            
                var html_5d357a7889bd118547b42d91b460a93f = $(`<div id="html_5d357a7889bd118547b42d91b460a93f" style="width: 100.0%; height: 100.0%;">Beans Bar</div>`)[0];
                popup_a7b9406ce9e96cebd19597d4f9a56af0.setContent(html_5d357a7889bd118547b42d91b460a93f);
            
        

        marker_f0ce08b6f38aba2153c3cdf4a2c6bd05.bindPopup(popup_a7b9406ce9e96cebd19597d4f9a56af0)
        ;

        
    
    
            var marker_4ff028605e0047d71250d4f2e1519ada = L.marker(
                [51.026422496621635, 4.478589197210429],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_0808e7c179bea9a66c144e4e5a598250 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_4ff028605e0047d71250d4f2e1519ada.setIcon(icon_0808e7c179bea9a66c144e4e5a598250);
        
    
        var popup_c585f6b735e9662d3eff1ba569a61579 = L.popup({"maxWidth": "100%"});

        
            
                var html_d701d6fd7b3306968025f3862c3a91a1 = $(`<div id="html_d701d6fd7b3306968025f3862c3a91a1" style="width: 100.0%; height: 100.0%;">Beastie Burgers Mechelen</div>`)[0];
                popup_c585f6b735e9662d3eff1ba569a61579.setContent(html_d701d6fd7b3306968025f3862c3a91a1);
            
        

        marker_4ff028605e0047d71250d4f2e1519ada.bindPopup(popup_c585f6b735e9662d3eff1ba569a61579)
        ;

        
    
    
            var marker_2297e4e4c245b775a4088733300ef7a2 = L.marker(
                [51.018777673448184, 4.482378999759968],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_49b363c1f7f7c4ccbf99a21e338098ef = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_2297e4e4c245b775a4088733300ef7a2.setIcon(icon_49b363c1f7f7c4ccbf99a21e338098ef);
        
    
        var popup_4428988a760440e01900acad1d1d9bfa = L.popup({"maxWidth": "100%"});

        
            
                var html_65cb34efca684cc301c6e436644d56be = $(`<div id="html_65cb34efca684cc301c6e436644d56be" style="width: 100.0%; height: 100.0%;">Beirut Palace</div>`)[0];
                popup_4428988a760440e01900acad1d1d9bfa.setContent(html_65cb34efca684cc301c6e436644d56be);
            
        

        marker_2297e4e4c245b775a4088733300ef7a2.bindPopup(popup_4428988a760440e01900acad1d1d9bfa)
        ;

        
    
    
            var marker_77c5b59396c7f38c34affe61f850230a = L.marker(
                [51.022595243297964, 4.482598606535638],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_bc38c03599debd947173f7c038794766 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_77c5b59396c7f38c34affe61f850230a.setIcon(icon_bc38c03599debd947173f7c038794766);
        
    
        var popup_8e1ace8b2bdd8bdd8736d71223a09632 = L.popup({"maxWidth": "100%"});

        
            
                var html_becf68f17c71ff868345116ad05fbc30 = $(`<div id="html_becf68f17c71ff868345116ad05fbc30" style="width: 100.0%; height: 100.0%;">Boho Bar</div>`)[0];
                popup_8e1ace8b2bdd8bdd8736d71223a09632.setContent(html_becf68f17c71ff868345116ad05fbc30);
            
        

        marker_77c5b59396c7f38c34affe61f850230a.bindPopup(popup_8e1ace8b2bdd8bdd8736d71223a09632)
        ;

        
    
    
            var marker_5ef06e61994e494df94c525a262aa65e = L.marker(
                [51.024101542198714, 4.475726158072986],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_25540d05e0fe61af25b315fb59468126 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_5ef06e61994e494df94c525a262aa65e.setIcon(icon_25540d05e0fe61af25b315fb59468126);
        
    
        var popup_7a58c3afd595e99627f308b083b05b9c = L.popup({"maxWidth": "100%"});

        
            
                var html_8a74b76320795915e532a04321541e14 = $(`<div id="html_8a74b76320795915e532a04321541e14" style="width: 100.0%; height: 100.0%;">Bokes & Co</div>`)[0];
                popup_7a58c3afd595e99627f308b083b05b9c.setContent(html_8a74b76320795915e532a04321541e14);
            
        

        marker_5ef06e61994e494df94c525a262aa65e.bindPopup(popup_7a58c3afd595e99627f308b083b05b9c)
        ;

        
    
    
            var marker_861130b716c3596ff11f000045038890 = L.marker(
                [51.02364244064718, 4.4752970804774845],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_fd695f8fd9909573273d9ace8c58e581 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_861130b716c3596ff11f000045038890.setIcon(icon_fd695f8fd9909573273d9ace8c58e581);
        
    
        var popup_fe3c85ff10cc7b3cfce085e9d2e4b639 = L.popup({"maxWidth": "100%"});

        
            
                var html_79cf94b1cc0ae5254ec2986954b31124 = $(`<div id="html_79cf94b1cc0ae5254ec2986954b31124" style="width: 100.0%; height: 100.0%;">Brunchy</div>`)[0];
                popup_fe3c85ff10cc7b3cfce085e9d2e4b639.setContent(html_79cf94b1cc0ae5254ec2986954b31124);
            
        

        marker_861130b716c3596ff11f000045038890.bindPopup(popup_fe3c85ff10cc7b3cfce085e9d2e4b639)
        ;

        
    
    
            var marker_a346f1545d694c369c1788715adf2945 = L.marker(
                [51.020377326130685, 4.471974453050626],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_0d8d1a1e480fb5bd951e6fbee40cd69c = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_a346f1545d694c369c1788715adf2945.setIcon(icon_0d8d1a1e480fb5bd951e6fbee40cd69c);
        
    
        var popup_dcc74ef64293005fdef6614b66aec77f = L.popup({"maxWidth": "100%"});

        
            
                var html_65972768734c5819713023c3df3aa1cd = $(`<div id="html_65972768734c5819713023c3df3aa1cd" style="width: 100.0%; height: 100.0%;">Butterfly</div>`)[0];
                popup_dcc74ef64293005fdef6614b66aec77f.setContent(html_65972768734c5819713023c3df3aa1cd);
            
        

        marker_a346f1545d694c369c1788715adf2945.bindPopup(popup_dcc74ef64293005fdef6614b66aec77f)
        ;

        
    
    
            var marker_283cc06edd8b185e2f75631daad3f8ae = L.marker(
                [51.02473377462019, 4.488178038218441],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_c8c5792decb07377364e3d6df32b5e96 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_283cc06edd8b185e2f75631daad3f8ae.setIcon(icon_c8c5792decb07377364e3d6df32b5e96);
        
    
        var popup_50c8037a031ef3178832053ff2ff2f9e = L.popup({"maxWidth": "100%"});

        
            
                var html_2ba20be637adfb0abe82b501b3886ba1 = $(`<div id="html_2ba20be637adfb0abe82b501b3886ba1" style="width: 100.0%; height: 100.0%;">Café De Planeet</div>`)[0];
                popup_50c8037a031ef3178832053ff2ff2f9e.setContent(html_2ba20be637adfb0abe82b501b3886ba1);
            
        

        marker_283cc06edd8b185e2f75631daad3f8ae.bindPopup(popup_50c8037a031ef3178832053ff2ff2f9e)
        ;

        
    
    
            var marker_311b58fbb44e369f06432ae80e83af7d = L.marker(
                [51.02664379746133, 4.478855341499525],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_026993879d28cacf6f57d911c4ee1925 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_311b58fbb44e369f06432ae80e83af7d.setIcon(icon_026993879d28cacf6f57d911c4ee1925);
        
    
        var popup_522fc1b5cc02106abc9ceaac925eb987 = L.popup({"maxWidth": "100%"});

        
            
                var html_3b5b16cc478ee43b00befed7a18a793c = $(`<div id="html_3b5b16cc478ee43b00befed7a18a793c" style="width: 100.0%; height: 100.0%;">Coffice</div>`)[0];
                popup_522fc1b5cc02106abc9ceaac925eb987.setContent(html_3b5b16cc478ee43b00befed7a18a793c);
            
        

        marker_311b58fbb44e369f06432ae80e83af7d.bindPopup(popup_522fc1b5cc02106abc9ceaac925eb987)
        ;

        
    
    
            var marker_0a3a3cd56552b842e2b10de04145f839 = L.marker(
                [51.02743933793956, 4.479511371047918],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_d064c754c181b11ba9711984cfd451ad = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_0a3a3cd56552b842e2b10de04145f839.setIcon(icon_d064c754c181b11ba9711984cfd451ad);
        
    
        var popup_87974845c4d8a9b94bb0f1355a2777c1 = L.popup({"maxWidth": "100%"});

        
            
                var html_00df290132ba1c310c625d39cd5657a0 = $(`<div id="html_00df290132ba1c310c625d39cd5657a0" style="width: 100.0%; height: 100.0%;">Croque 'n roll</div>`)[0];
                popup_87974845c4d8a9b94bb0f1355a2777c1.setContent(html_00df290132ba1c310c625d39cd5657a0);
            
        

        marker_0a3a3cd56552b842e2b10de04145f839.bindPopup(popup_87974845c4d8a9b94bb0f1355a2777c1)
        ;

        
    
    
            var marker_85595fd27948bfe5d46d76c244c611b1 = L.marker(
                [51.0190900093437, 4.480490576347801],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_0ca13a1bd7cd4d20dffa39dc581175a2 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_85595fd27948bfe5d46d76c244c611b1.setIcon(icon_0ca13a1bd7cd4d20dffa39dc581175a2);
        
    
        var popup_2738e614a4d89cfc12a00e227dbbd267 = L.popup({"maxWidth": "100%"});

        
            
                var html_c1d27dfb95bbb6212d28d68719209fe7 = $(`<div id="html_c1d27dfb95bbb6212d28d68719209fe7" style="width: 100.0%; height: 100.0%;">Dim Sum</div>`)[0];
                popup_2738e614a4d89cfc12a00e227dbbd267.setContent(html_c1d27dfb95bbb6212d28d68719209fe7);
            
        

        marker_85595fd27948bfe5d46d76c244c611b1.bindPopup(popup_2738e614a4d89cfc12a00e227dbbd267)
        ;

        
    
    
            var marker_4fa4192eea70492b12daceff3725c226 = L.marker(
                [51.02375529436572, 4.487502021716919],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_3fc6adf9cff42e7f1baa522f6f99255c = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_4fa4192eea70492b12daceff3725c226.setIcon(icon_3fc6adf9cff42e7f1baa522f6f99255c);
        
    
        var popup_6a43b56a580d99b4820924c48bb1b434 = L.popup({"maxWidth": "100%"});

        
            
                var html_11f8c1f5f46c71a4247c87b590de06a2 = $(`<div id="html_11f8c1f5f46c71a4247c87b590de06a2" style="width: 100.0%; height: 100.0%;">Domino's</div>`)[0];
                popup_6a43b56a580d99b4820924c48bb1b434.setContent(html_11f8c1f5f46c71a4247c87b590de06a2);
            
        

        marker_4fa4192eea70492b12daceff3725c226.bindPopup(popup_6a43b56a580d99b4820924c48bb1b434)
        ;

        
    
    
            var marker_6457880bf5e992beba3338de0a45ca4b = L.marker(
                [51.02272150033957, 4.474558867903261],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_ddb45216c04eb748920696b8efbdbaee = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_6457880bf5e992beba3338de0a45ca4b.setIcon(icon_ddb45216c04eb748920696b8efbdbaee);
        
    
        var popup_09b80323b917be63391ab77e4141f334 = L.popup({"maxWidth": "100%"});

        
            
                var html_157885afecf8cdceb8ed9cc50747fbe8 = $(`<div id="html_157885afecf8cdceb8ed9cc50747fbe8" style="width: 100.0%; height: 100.0%;">Dream Sushi en Wok</div>`)[0];
                popup_09b80323b917be63391ab77e4141f334.setContent(html_157885afecf8cdceb8ed9cc50747fbe8);
            
        

        marker_6457880bf5e992beba3338de0a45ca4b.bindPopup(popup_09b80323b917be63391ab77e4141f334)
        ;

        
    
    
            var marker_7d16b86ae7f7895f1c41a6032afe7f25 = L.marker(
                [51.01840423444439, 4.48294987883931],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_b264584663c022526f870860ea12e30e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_7d16b86ae7f7895f1c41a6032afe7f25.setIcon(icon_b264584663c022526f870860ea12e30e);
        
    
        var popup_b85b5f30bf404f779ddf93ea02c834f9 = L.popup({"maxWidth": "100%"});

        
            
                var html_9daa4df7090a0af4b7e2902dc037eaf7 = $(`<div id="html_9daa4df7090a0af4b7e2902dc037eaf7" style="width: 100.0%; height: 100.0%;">Eetcafe Friends</div>`)[0];
                popup_b85b5f30bf404f779ddf93ea02c834f9.setContent(html_9daa4df7090a0af4b7e2902dc037eaf7);
            
        

        marker_7d16b86ae7f7895f1c41a6032afe7f25.bindPopup(popup_b85b5f30bf404f779ddf93ea02c834f9)
        ;

        
    
    
            var marker_0ea42c40170ea95632cec84771e5bc0a = L.marker(
                [51.02740131922272, 4.479017734628876],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_8e856985f5352f347211cc0ff98f4657 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_0ea42c40170ea95632cec84771e5bc0a.setIcon(icon_8e856985f5352f347211cc0ff98f4657);
        
    
        var popup_87303fbb0753f9a3c6b79871dcdc8092 = L.popup({"maxWidth": "100%"});

        
            
                var html_4246b79924b64cae2fa51c9cc9b608f5 = $(`<div id="html_4246b79924b64cae2fa51c9cc9b608f5" style="width: 100.0%; height: 100.0%;">Ellis Gourmet Burger</div>`)[0];
                popup_87303fbb0753f9a3c6b79871dcdc8092.setContent(html_4246b79924b64cae2fa51c9cc9b608f5);
            
        

        marker_0ea42c40170ea95632cec84771e5bc0a.bindPopup(popup_87303fbb0753f9a3c6b79871dcdc8092)
        ;

        
    
    
            var marker_601599e1c0d9322bafd8e80280d884b0 = L.marker(
                [51.02667555467132, 4.479250562125427],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_3eb3edcee95ed3b8b37f031b113dd7db = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_601599e1c0d9322bafd8e80280d884b0.setIcon(icon_3eb3edcee95ed3b8b37f031b113dd7db);
        
    
        var popup_cce3b9ba1ad878d715fb759f403730b9 = L.popup({"maxWidth": "100%"});

        
            
                var html_6efb66ed399ac6a04da28c59b6a7f71b = $(`<div id="html_6efb66ed399ac6a04da28c59b6a7f71b" style="width: 100.0%; height: 100.0%;">Favoriete</div>`)[0];
                popup_cce3b9ba1ad878d715fb759f403730b9.setContent(html_6efb66ed399ac6a04da28c59b6a7f71b);
            
        

        marker_601599e1c0d9322bafd8e80280d884b0.bindPopup(popup_cce3b9ba1ad878d715fb759f403730b9)
        ;

        
    
    
            var marker_1ac3762d9ced28e54120e8455305c614 = L.marker(
                [51.02333109901301, 4.482670651993287],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_4ba2e5b75a728cb8af715c2ed8a95581 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_1ac3762d9ced28e54120e8455305c614.setIcon(icon_4ba2e5b75a728cb8af715c2ed8a95581);
        
    
        var popup_54fa0643149eb4b20c6629821f8bb0e0 = L.popup({"maxWidth": "100%"});

        
            
                var html_9aaa470e1d1944b11cc5bfd4e03ec364 = $(`<div id="html_9aaa470e1d1944b11cc5bfd4e03ec364" style="width: 100.0%; height: 100.0%;">Frank's Haute Dog</div>`)[0];
                popup_54fa0643149eb4b20c6629821f8bb0e0.setContent(html_9aaa470e1d1944b11cc5bfd4e03ec364);
            
        

        marker_1ac3762d9ced28e54120e8455305c614.bindPopup(popup_54fa0643149eb4b20c6629821f8bb0e0)
        ;

        
    
    
            var marker_eaa9996329ece2c9d9862a6d7e4744aa = L.marker(
                [51.0186803075112, 4.483116036647569],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_76a60ea14a1f5f4ada70ee7951dde56a = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_eaa9996329ece2c9d9862a6d7e4744aa.setIcon(icon_76a60ea14a1f5f4ada70ee7951dde56a);
        
    
        var popup_2ddc82c7a780faa625f69c7c97665280 = L.popup({"maxWidth": "100%"});

        
            
                var html_9ed9566b24145da531a54a12216b261e = $(`<div id="html_9ed9566b24145da531a54a12216b261e" style="width: 100.0%; height: 100.0%;">Friet Van Mechelen</div>`)[0];
                popup_2ddc82c7a780faa625f69c7c97665280.setContent(html_9ed9566b24145da531a54a12216b261e);
            
        

        marker_eaa9996329ece2c9d9862a6d7e4744aa.bindPopup(popup_2ddc82c7a780faa625f69c7c97665280)
        ;

        
    
    
            var marker_865e81aaaf078649582f282eb72fd7b0 = L.marker(
                [51.02171850265919, 4.48536247115077],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_0674fcf17ab7975f5fa7f51352cb2fc9 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_865e81aaaf078649582f282eb72fd7b0.setIcon(icon_0674fcf17ab7975f5fa7f51352cb2fc9);
        
    
        var popup_4518c693cc5a2544f6fb75d6b2078a18 = L.popup({"maxWidth": "100%"});

        
            
                var html_a5b02c16b62282fe37f658e687f3de48 = $(`<div id="html_a5b02c16b62282fe37f658e687f3de48" style="width: 100.0%; height: 100.0%;">Frituur Veemarkt - Koremarkt</div>`)[0];
                popup_4518c693cc5a2544f6fb75d6b2078a18.setContent(html_a5b02c16b62282fe37f658e687f3de48);
            
        

        marker_865e81aaaf078649582f282eb72fd7b0.bindPopup(popup_4518c693cc5a2544f6fb75d6b2078a18)
        ;

        
    
    
            var marker_4c49116c00fe71d242f4f22fe6afa465 = L.marker(
                [51.02487814878816, 4.476659289299109],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_050dd594e299bf90841979459aedc79f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_4c49116c00fe71d242f4f22fe6afa465.setIcon(icon_050dd594e299bf90841979459aedc79f);
        
    
        var popup_71e68dbd4788dcf64722a4370540e57f = L.popup({"maxWidth": "100%"});

        
            
                var html_5af46ab2f0c59803f86fcb96d5c08adc = $(`<div id="html_5af46ab2f0c59803f86fcb96d5c08adc" style="width: 100.0%; height: 100.0%;">Frituur Veemarkt - Koremarkt</div>`)[0];
                popup_71e68dbd4788dcf64722a4370540e57f.setContent(html_5af46ab2f0c59803f86fcb96d5c08adc);
            
        

        marker_4c49116c00fe71d242f4f22fe6afa465.bindPopup(popup_71e68dbd4788dcf64722a4370540e57f)
        ;

        
    
    
            var marker_a6b867e2f559dd3b5315de659948d622 = L.marker(
                [51.024574224085754, 4.4820004739461785],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_ae00f8a5cdb5226241812ee4f826c845 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_a6b867e2f559dd3b5315de659948d622.setIcon(icon_ae00f8a5cdb5226241812ee4f826c845);
        
    
        var popup_4632e085228ec36a1400aba867b60e24 = L.popup({"maxWidth": "100%"});

        
            
                var html_7846237e058f1a40a240a2136a57ecbb = $(`<div id="html_7846237e058f1a40a240a2136a57ecbb" style="width: 100.0%; height: 100.0%;">Frutsi</div>`)[0];
                popup_4632e085228ec36a1400aba867b60e24.setContent(html_7846237e058f1a40a240a2136a57ecbb);
            
        

        marker_a6b867e2f559dd3b5315de659948d622.bindPopup(popup_4632e085228ec36a1400aba867b60e24)
        ;

        
    
    
            var marker_20446e43ba65a872b3b3f4dd808e5883 = L.marker(
                [51.01804868907658, 4.482923326323327],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_73a27fa4887110b4be812548b5fd6070 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_20446e43ba65a872b3b3f4dd808e5883.setIcon(icon_73a27fa4887110b4be812548b5fd6070);
        
    
        var popup_64ad276bfe005ea1ec9a1c4c7070f362 = L.popup({"maxWidth": "100%"});

        
            
                var html_3863782388f5c9101fe013fbb799baad = $(`<div id="html_3863782388f5c9101fe013fbb799baad" style="width: 100.0%; height: 100.0%;">Hamburgers Marc</div>`)[0];
                popup_64ad276bfe005ea1ec9a1c4c7070f362.setContent(html_3863782388f5c9101fe013fbb799baad);
            
        

        marker_20446e43ba65a872b3b3f4dd808e5883.bindPopup(popup_64ad276bfe005ea1ec9a1c4c7070f362)
        ;

        
    
    
            var marker_7e21bb8c897428bd034a2b41c374c997 = L.marker(
                [51.0269402821687, 4.4791282521393345],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_a60ceb23b137361ec5df2999527cbf57 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_7e21bb8c897428bd034a2b41c374c997.setIcon(icon_a60ceb23b137361ec5df2999527cbf57);
        
    
        var popup_215aba4fd7d470f63b4ca4240ebbb2a3 = L.popup({"maxWidth": "100%"});

        
            
                var html_1950ba3e74b5575cc1be303e09e52e50 = $(`<div id="html_1950ba3e74b5575cc1be303e09e52e50" style="width: 100.0%; height: 100.0%;">Hawaiian Poke bowl</div>`)[0];
                popup_215aba4fd7d470f63b4ca4240ebbb2a3.setContent(html_1950ba3e74b5575cc1be303e09e52e50);
            
        

        marker_7e21bb8c897428bd034a2b41c374c997.bindPopup(popup_215aba4fd7d470f63b4ca4240ebbb2a3)
        ;

        
    
    
            var marker_77020e1b9e342bea66122be02462e4b9 = L.marker(
                [51.024715909470196, 4.477087922727095],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_c237ac5448e19dcd815aa8bc844e5c18 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_77020e1b9e342bea66122be02462e4b9.setIcon(icon_c237ac5448e19dcd815aa8bc844e5c18);
        
    
        var popup_60598f7f4e937fed35d864f0eddd15bd = L.popup({"maxWidth": "100%"});

        
            
                var html_bca0d12ae7b7414208aec3431f5d7c9d = $(`<div id="html_bca0d12ae7b7414208aec3431f5d7c9d" style="width: 100.0%; height: 100.0%;">Kaffee-ine</div>`)[0];
                popup_60598f7f4e937fed35d864f0eddd15bd.setContent(html_bca0d12ae7b7414208aec3431f5d7c9d);
            
        

        marker_77020e1b9e342bea66122be02462e4b9.bindPopup(popup_60598f7f4e937fed35d864f0eddd15bd)
        ;

        
    
    
            var marker_181ebe7d0e7a90b6a12807be71e39f34 = L.marker(
                [51.024787485709886, 4.476822397594715],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_5a15adee35038c474937140b135a1e66 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_181ebe7d0e7a90b6a12807be71e39f34.setIcon(icon_5a15adee35038c474937140b135a1e66);
        
    
        var popup_f8c2134efc20c64340f8c4f900174c42 = L.popup({"maxWidth": "100%"});

        
            
                var html_5f621fb6176dabc36a65cc9a1c6eb2c3 = $(`<div id="html_5f621fb6176dabc36a65cc9a1c6eb2c3" style="width: 100.0%; height: 100.0%;">Kato Gateaux</div>`)[0];
                popup_f8c2134efc20c64340f8c4f900174c42.setContent(html_5f621fb6176dabc36a65cc9a1c6eb2c3);
            
        

        marker_181ebe7d0e7a90b6a12807be71e39f34.bindPopup(popup_f8c2134efc20c64340f8c4f900174c42)
        ;

        
    
    
            var marker_a8995ec63d58fb93113c1bc0cab00f5d = L.marker(
                [51.01804749596126, 4.481707600519736],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_5f43fced60daf6ed858af000d29ae11a = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_a8995ec63d58fb93113c1bc0cab00f5d.setIcon(icon_5f43fced60daf6ed858af000d29ae11a);
        
    
        var popup_116c98428ac812afe23002f3e53924ab = L.popup({"maxWidth": "100%"});

        
            
                var html_41a03fcde64675c423965a6bdae3f68c = $(`<div id="html_41a03fcde64675c423965a6bdae3f68c" style="width: 100.0%; height: 100.0%;">King Kebab</div>`)[0];
                popup_116c98428ac812afe23002f3e53924ab.setContent(html_41a03fcde64675c423965a6bdae3f68c);
            
        

        marker_a8995ec63d58fb93113c1bc0cab00f5d.bindPopup(popup_116c98428ac812afe23002f3e53924ab)
        ;

        
    
    
            var marker_84967a8cbf92f63b2e795a903b870c74 = L.marker(
                [51.0232378353916, 4.477759322005339],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_4301621c8b3ad3b1d2fd4786758390d8 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_84967a8cbf92f63b2e795a903b870c74.setIcon(icon_4301621c8b3ad3b1d2fd4786758390d8);
        
    
        var popup_cf94d012ddb9e519d6de47d39a90b564 = L.popup({"maxWidth": "100%"});

        
            
                var html_7a0669cd375bbc5f4f8edf3b83dae093 = $(`<div id="html_7a0669cd375bbc5f4f8edf3b83dae093" style="width: 100.0%; height: 100.0%;">La Boya</div>`)[0];
                popup_cf94d012ddb9e519d6de47d39a90b564.setContent(html_7a0669cd375bbc5f4f8edf3b83dae093);
            
        

        marker_84967a8cbf92f63b2e795a903b870c74.bindPopup(popup_cf94d012ddb9e519d6de47d39a90b564)
        ;

        
    
    
            var marker_23cb494b1038a63c649da6d2f5ef0e0b = L.marker(
                [51.024521841379986, 4.482200351993386],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_c7f21434e479fad40c78430462eab6a9 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_23cb494b1038a63c649da6d2f5ef0e0b.setIcon(icon_c7f21434e479fad40c78430462eab6a9);
        
    
        var popup_a2d6efc5e817201006b541db4d1ed15d = L.popup({"maxWidth": "100%"});

        
            
                var html_e60c19a27ea0c37caac5e7b1985e6ee8 = $(`<div id="html_e60c19a27ea0c37caac5e7b1985e6ee8" style="width: 100.0%; height: 100.0%;">La Delice</div>`)[0];
                popup_a2d6efc5e817201006b541db4d1ed15d.setContent(html_e60c19a27ea0c37caac5e7b1985e6ee8);
            
        

        marker_23cb494b1038a63c649da6d2f5ef0e0b.bindPopup(popup_a2d6efc5e817201006b541db4d1ed15d)
        ;

        
    
    
            var marker_99b1a52429f346e13f61645d07b62260 = L.marker(
                [51.02640394717079, 4.480033767176964],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_40c7e64e5e50b9da6c775c99ee60fc95 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_99b1a52429f346e13f61645d07b62260.setIcon(icon_40c7e64e5e50b9da6c775c99ee60fc95);
        
    
        var popup_e911d243941e657e7a57a5c6411df7b9 = L.popup({"maxWidth": "100%"});

        
            
                var html_562eed2e271ac62dd42ea291a307abbf = $(`<div id="html_562eed2e271ac62dd42ea291a307abbf" style="width: 100.0%; height: 100.0%;">La Sora</div>`)[0];
                popup_e911d243941e657e7a57a5c6411df7b9.setContent(html_562eed2e271ac62dd42ea291a307abbf);
            
        

        marker_99b1a52429f346e13f61645d07b62260.bindPopup(popup_e911d243941e657e7a57a5c6411df7b9)
        ;

        
    
    
            var marker_8ab9b3ed1bb2e48039dc9acd335c0282 = L.marker(
                [51.02660723119665, 4.4788361608532865],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_1ecb881e3e8271dc070923449fb0713d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_8ab9b3ed1bb2e48039dc9acd335c0282.setIcon(icon_1ecb881e3e8271dc070923449fb0713d);
        
    
        var popup_2fe21afafd5170aa2c6fcea5c08df7cb = L.popup({"maxWidth": "100%"});

        
            
                var html_4decd98e9330e45526b377aef143e9c4 = $(`<div id="html_4decd98e9330e45526b377aef143e9c4" style="width: 100.0%; height: 100.0%;">Le pain quotidien</div>`)[0];
                popup_2fe21afafd5170aa2c6fcea5c08df7cb.setContent(html_4decd98e9330e45526b377aef143e9c4);
            
        

        marker_8ab9b3ed1bb2e48039dc9acd335c0282.bindPopup(popup_2fe21afafd5170aa2c6fcea5c08df7cb)
        ;

        
    
    
            var marker_0581aeb3f04e0ab4801c0e05068764f5 = L.marker(
                [51.022227443873994, 4.482316974603116],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_1f9dbcffe82725ce312dc8615a5fbfee = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_0581aeb3f04e0ab4801c0e05068764f5.setIcon(icon_1f9dbcffe82725ce312dc8615a5fbfee);
        
    
        var popup_df02bc190c4f9f07787a5989bdcf47e3 = L.popup({"maxWidth": "100%"});

        
            
                var html_9619b598fee01b86ef7d32e681852f13 = $(`<div id="html_9619b598fee01b86ef7d32e681852f13" style="width: 100.0%; height: 100.0%;">Lief</div>`)[0];
                popup_df02bc190c4f9f07787a5989bdcf47e3.setContent(html_9619b598fee01b86ef7d32e681852f13);
            
        

        marker_0581aeb3f04e0ab4801c0e05068764f5.bindPopup(popup_df02bc190c4f9f07787a5989bdcf47e3)
        ;

        
    
    
            var marker_da180f9390711a7ebac7ab13db3331c6 = L.marker(
                [51.02696403046062, 4.479844671440611],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_8027e99f10458b76a4f2ec1372df3b3c = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_da180f9390711a7ebac7ab13db3331c6.setIcon(icon_8027e99f10458b76a4f2ec1372df3b3c);
        
    
        var popup_0168b47f6267802a893f5b1d85b5f654 = L.popup({"maxWidth": "100%"});

        
            
                var html_ea74f1f057bb47555a4c3634564d5538 = $(`<div id="html_ea74f1f057bb47555a4c3634564d5538" style="width: 100.0%; height: 100.0%;">Lunchroom</div>`)[0];
                popup_0168b47f6267802a893f5b1d85b5f654.setContent(html_ea74f1f057bb47555a4c3634564d5538);
            
        

        marker_da180f9390711a7ebac7ab13db3331c6.bindPopup(popup_0168b47f6267802a893f5b1d85b5f654)
        ;

        
    
    
            var marker_2dff7d86b913ff7614bb7b11dac884d0 = L.marker(
                [51.02365210295402, 4.487410036224629],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_529d7176dbb15ddc392ed2f814bf5f45 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_2dff7d86b913ff7614bb7b11dac884d0.setIcon(icon_529d7176dbb15ddc392ed2f814bf5f45);
        
    
        var popup_4497200819600ed29513febaea4b298d = L.popup({"maxWidth": "100%"});

        
            
                var html_d102f5518b3c98d75d68430ad4dd7402 = $(`<div id="html_d102f5518b3c98d75d68430ad4dd7402" style="width: 100.0%; height: 100.0%;">Mechelburger</div>`)[0];
                popup_4497200819600ed29513febaea4b298d.setContent(html_d102f5518b3c98d75d68430ad4dd7402);
            
        

        marker_2dff7d86b913ff7614bb7b11dac884d0.bindPopup(popup_4497200819600ed29513febaea4b298d)
        ;

        
    
    
            var marker_2a2ab3bf58faab8ecf88c2a014815411 = L.marker(
                [51.02630368311457, 4.477224478484213],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_ade28a97114a242c6845c5709789b0bc = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_2a2ab3bf58faab8ecf88c2a014815411.setIcon(icon_ade28a97114a242c6845c5709789b0bc);
        
    
        var popup_cf941aa4251dfee2ebe4f73c2951483b = L.popup({"maxWidth": "100%"});

        
            
                var html_e1c5a590d040a6f708cdcbe0a4dc59b2 = $(`<div id="html_e1c5a590d040a6f708cdcbe0a4dc59b2" style="width: 100.0%; height: 100.0%;">Merad Restaurant</div>`)[0];
                popup_cf941aa4251dfee2ebe4f73c2951483b.setContent(html_e1c5a590d040a6f708cdcbe0a4dc59b2);
            
        

        marker_2a2ab3bf58faab8ecf88c2a014815411.bindPopup(popup_cf941aa4251dfee2ebe4f73c2951483b)
        ;

        
    
    
            var marker_291225492d85073cbfc298d30dd29371 = L.marker(
                [51.01958830526458, 4.482490017593297],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_d1876dadfad2c998743f9ce3cd91ca13 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_291225492d85073cbfc298d30dd29371.setIcon(icon_d1876dadfad2c998743f9ce3cd91ca13);
        
    
        var popup_c5aac2367e831bf45a28d454ee5c195f = L.popup({"maxWidth": "100%"});

        
            
                var html_01af14c393b4ba88ea3654924a6c1f37 = $(`<div id="html_01af14c393b4ba88ea3654924a6c1f37" style="width: 100.0%; height: 100.0%;">Munis Restaurant</div>`)[0];
                popup_c5aac2367e831bf45a28d454ee5c195f.setContent(html_01af14c393b4ba88ea3654924a6c1f37);
            
        

        marker_291225492d85073cbfc298d30dd29371.bindPopup(popup_c5aac2367e831bf45a28d454ee5c195f)
        ;

        
    
    
            var marker_92367ba3e171c66c2f5e8bf50f0e0871 = L.marker(
                [51.01928354130624, 4.48218933892616],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_6a2d8be38f6809e2259a6291c2953e86 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_92367ba3e171c66c2f5e8bf50f0e0871.setIcon(icon_6a2d8be38f6809e2259a6291c2953e86);
        
    
        var popup_bfc16a7366d93e195697c2f132db5728 = L.popup({"maxWidth": "100%"});

        
            
                var html_45fff0bc5e40956968dae61b2812756c = $(`<div id="html_45fff0bc5e40956968dae61b2812756c" style="width: 100.0%; height: 100.0%;">New Shanghai</div>`)[0];
                popup_bfc16a7366d93e195697c2f132db5728.setContent(html_45fff0bc5e40956968dae61b2812756c);
            
        

        marker_92367ba3e171c66c2f5e8bf50f0e0871.bindPopup(popup_bfc16a7366d93e195697c2f132db5728)
        ;

        
    
    
            var marker_d49868952b16db9404dee3cce4e8cfb3 = L.marker(
                [51.02034725231323, 4.472296685094349],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_e4858606f9ce9cb80018abf144bb8bac = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_d49868952b16db9404dee3cce4e8cfb3.setIcon(icon_e4858606f9ce9cb80018abf144bb8bac);
        
    
        var popup_2ee68ac596a77f33ef6f44353d92a028 = L.popup({"maxWidth": "100%"});

        
            
                var html_b0725101fc5402a6232478054fdb4338 = $(`<div id="html_b0725101fc5402a6232478054fdb4338" style="width: 100.0%; height: 100.0%;">Ni Hao - Moshi Moshi</div>`)[0];
                popup_2ee68ac596a77f33ef6f44353d92a028.setContent(html_b0725101fc5402a6232478054fdb4338);
            
        

        marker_d49868952b16db9404dee3cce4e8cfb3.bindPopup(popup_2ee68ac596a77f33ef6f44353d92a028)
        ;

        
    
    
            var marker_3342d6cbe21ffed2dba7121e655bd2c9 = L.marker(
                [51.02551755705944, 4.477093612522705],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_32deec15da5c0aa0961ce6bedda28d65 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_3342d6cbe21ffed2dba7121e655bd2c9.setIcon(icon_32deec15da5c0aa0961ce6bedda28d65);
        
    
        var popup_67e2200ae5edd5fcb94c84b1d697a4e7 = L.popup({"maxWidth": "100%"});

        
            
                var html_3a9fea64259057da7e364b42cdcc907c = $(`<div id="html_3a9fea64259057da7e364b42cdcc907c" style="width: 100.0%; height: 100.0%;">Niki's Bakery</div>`)[0];
                popup_67e2200ae5edd5fcb94c84b1d697a4e7.setContent(html_3a9fea64259057da7e364b42cdcc907c);
            
        

        marker_3342d6cbe21ffed2dba7121e655bd2c9.bindPopup(popup_67e2200ae5edd5fcb94c84b1d697a4e7)
        ;

        
    
    
            var marker_d18428f05315e68346a1078e6bc81d12 = L.marker(
                [51.0222875780895, 4.474406173829901],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_806d11bbe0ac90db90e38ea072a52cfa = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_d18428f05315e68346a1078e6bc81d12.setIcon(icon_806d11bbe0ac90db90e38ea072a52cfa);
        
    
        var popup_456c4fe850f69ac56a231e4c958afdda = L.popup({"maxWidth": "100%"});

        
            
                var html_fad578f0a342417bb3816003d57d2c75 = $(`<div id="html_fad578f0a342417bb3816003d57d2c75" style="width: 100.0%; height: 100.0%;">Non Stop bvba</div>`)[0];
                popup_456c4fe850f69ac56a231e4c958afdda.setContent(html_fad578f0a342417bb3816003d57d2c75);
            
        

        marker_d18428f05315e68346a1078e6bc81d12.bindPopup(popup_456c4fe850f69ac56a231e4c958afdda)
        ;

        
    
    
            var marker_90d936058f3060de0cfd111e8b63fa85 = L.marker(
                [51.02473171618452, 4.488113593474612],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_b8f52e34732537fe10a0741b7d1ed542 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_90d936058f3060de0cfd111e8b63fa85.setIcon(icon_b8f52e34732537fe10a0741b7d1ed542);
        
    
        var popup_757def7dda7eddd4a2d06bc7f813733d = L.popup({"maxWidth": "100%"});

        
            
                var html_69938635e3f010f002118248dcce8265 = $(`<div id="html_69938635e3f010f002118248dcce8265" style="width: 100.0%; height: 100.0%;">Nrneni</div>`)[0];
                popup_757def7dda7eddd4a2d06bc7f813733d.setContent(html_69938635e3f010f002118248dcce8265);
            
        

        marker_90d936058f3060de0cfd111e8b63fa85.bindPopup(popup_757def7dda7eddd4a2d06bc7f813733d)
        ;

        
    
    
            var marker_d94ad66ce49bea1bdef1154c8018461d = L.marker(
                [51.026425034766206, 4.479941230970565],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_75b7374579a3ddd2f2effbd291ea217f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_d94ad66ce49bea1bdef1154c8018461d.setIcon(icon_75b7374579a3ddd2f2effbd291ea217f);
        
    
        var popup_0cb59965badbd5ae1b9a18267da5ce7f = L.popup({"maxWidth": "100%"});

        
            
                var html_e8eefcf30c32d320d65b2f25dcc0939d = $(`<div id="html_e8eefcf30c32d320d65b2f25dcc0939d" style="width: 100.0%; height: 100.0%;">Nul 10 Kitchen</div>`)[0];
                popup_0cb59965badbd5ae1b9a18267da5ce7f.setContent(html_e8eefcf30c32d320d65b2f25dcc0939d);
            
        

        marker_d94ad66ce49bea1bdef1154c8018461d.bindPopup(popup_0cb59965badbd5ae1b9a18267da5ce7f)
        ;

        
    
    
            var marker_6ef168ea0ba4ff281bd723b320cce696 = L.marker(
                [51.02648495771531, 4.476940472817002],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_b7cc746cc65267e8251e9bc8adca5f35 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_6ef168ea0ba4ff281bd723b320cce696.setIcon(icon_b7cc746cc65267e8251e9bc8adca5f35);
        
    
        var popup_d11f7bdea9d7bac44988649f5c810645 = L.popup({"maxWidth": "100%"});

        
            
                var html_b96971403bae326ed86c644a6c09c988 = $(`<div id="html_b96971403bae326ed86c644a6c09c988" style="width: 100.0%; height: 100.0%;">Otomat</div>`)[0];
                popup_d11f7bdea9d7bac44988649f5c810645.setContent(html_b96971403bae326ed86c644a6c09c988);
            
        

        marker_6ef168ea0ba4ff281bd723b320cce696.bindPopup(popup_d11f7bdea9d7bac44988649f5c810645)
        ;

        
    
    
            var marker_133ac2f7fdd0bc0d5f8b42365456252a = L.marker(
                [51.024367570184225, 4.47771949323662],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_76624f9e47fc06e56458a0e2593d2fe3 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_133ac2f7fdd0bc0d5f8b42365456252a.setIcon(icon_76624f9e47fc06e56458a0e2593d2fe3);
        
    
        var popup_d4e46355b3a61bbd6d7c90fbbef859a6 = L.popup({"maxWidth": "100%"});

        
            
                var html_af55aebbe28ccfd78e1dafe62fb1f51b = $(`<div id="html_af55aebbe28ccfd78e1dafe62fb1f51b" style="width: 100.0%; height: 100.0%;">Pitawan</div>`)[0];
                popup_d4e46355b3a61bbd6d7c90fbbef859a6.setContent(html_af55aebbe28ccfd78e1dafe62fb1f51b);
            
        

        marker_133ac2f7fdd0bc0d5f8b42365456252a.bindPopup(popup_d4e46355b3a61bbd6d7c90fbbef859a6)
        ;

        
    
    
            var marker_cb655e4d69a3354a2001b7ad6ca7cad5 = L.marker(
                [51.02195589940619, 4.4735703482842535],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_cb558b3d16464fe443d5c7cfc62115c3 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_cb655e4d69a3354a2001b7ad6ca7cad5.setIcon(icon_cb558b3d16464fe443d5c7cfc62115c3);
        
    
        var popup_212e7603519745b4c7393293630d864e = L.popup({"maxWidth": "100%"});

        
            
                var html_bf6b235186e1a0fc338145230fbb7b5b = $(`<div id="html_bf6b235186e1a0fc338145230fbb7b5b" style="width: 100.0%; height: 100.0%;">Pizza Hut Delivery</div>`)[0];
                popup_212e7603519745b4c7393293630d864e.setContent(html_bf6b235186e1a0fc338145230fbb7b5b);
            
        

        marker_cb655e4d69a3354a2001b7ad6ca7cad5.bindPopup(popup_212e7603519745b4c7393293630d864e)
        ;

        
    
    
            var marker_acfa0cc7ca7ad6f293e604fc546f3a67 = L.marker(
                [51.01837791139886, 4.482125020792508],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_6d51d33cf4dc6b896853782b9b6483c1 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_acfa0cc7ca7ad6f293e604fc546f3a67.setIcon(icon_6d51d33cf4dc6b896853782b9b6483c1);
        
    
        var popup_fb8b79645e6e0548e17c511d86a7b129 = L.popup({"maxWidth": "100%"});

        
            
                var html_30902519a081bbd98451312c6e1334d1 = $(`<div id="html_30902519a081bbd98451312c6e1334d1" style="width: 100.0%; height: 100.0%;">Pizza Pasta Nr 1</div>`)[0];
                popup_fb8b79645e6e0548e17c511d86a7b129.setContent(html_30902519a081bbd98451312c6e1334d1);
            
        

        marker_acfa0cc7ca7ad6f293e604fc546f3a67.bindPopup(popup_fb8b79645e6e0548e17c511d86a7b129)
        ;

        
    
    
            var marker_15444e77bc4f1cf267e2d26e26aefdff = L.marker(
                [51.02032483190556, 4.472600333719808],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_07da5559a4bf633f7da6c835bf4549f5 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_15444e77bc4f1cf267e2d26e26aefdff.setIcon(icon_07da5559a4bf633f7da6c835bf4549f5);
        
    
        var popup_9f2c0be7465cc56e4fd1ebb0daaf14ef = L.popup({"maxWidth": "100%"});

        
            
                var html_39f9959d35f6a9b09fc47b89b40bf899 = $(`<div id="html_39f9959d35f6a9b09fc47b89b40bf899" style="width: 100.0%; height: 100.0%;">Plaisanca</div>`)[0];
                popup_9f2c0be7465cc56e4fd1ebb0daaf14ef.setContent(html_39f9959d35f6a9b09fc47b89b40bf899);
            
        

        marker_15444e77bc4f1cf267e2d26e26aefdff.bindPopup(popup_9f2c0be7465cc56e4fd1ebb0daaf14ef)
        ;

        
    
    
            var marker_3b86b02d4c1b03714f4e6c46ddf13451 = L.marker(
                [51.02677930494033, 4.478479427072092],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_a94aef55635e70ce26353f3eb660a0c8 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_3b86b02d4c1b03714f4e6c46ddf13451.setIcon(icon_a94aef55635e70ce26353f3eb660a0c8);
        
    
        var popup_2235ce965fd286749cc020da0a35fa84 = L.popup({"maxWidth": "100%"});

        
            
                var html_902c5bdae4e3692a682c3554fe9d6578 = $(`<div id="html_902c5bdae4e3692a682c3554fe9d6578" style="width: 100.0%; height: 100.0%;">Poule & Poulette</div>`)[0];
                popup_2235ce965fd286749cc020da0a35fa84.setContent(html_902c5bdae4e3692a682c3554fe9d6578);
            
        

        marker_3b86b02d4c1b03714f4e6c46ddf13451.bindPopup(popup_2235ce965fd286749cc020da0a35fa84)
        ;

        
    
    
            var marker_2890e02105139c54a3edcb492a073a08 = L.marker(
                [51.02726431328904, 4.479442340111979],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_fd488f3a1f9d958ca27ab36e6769fedb = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_2890e02105139c54a3edcb492a073a08.setIcon(icon_fd488f3a1f9d958ca27ab36e6769fedb);
        
    
        var popup_49539b4653e1238697a82e2aa85a504d = L.popup({"maxWidth": "100%"});

        
            
                var html_6cbbf7b348ed2de74f95dcbe9b6963ee = $(`<div id="html_6cbbf7b348ed2de74f95dcbe9b6963ee" style="width: 100.0%; height: 100.0%;">Rice Paper</div>`)[0];
                popup_49539b4653e1238697a82e2aa85a504d.setContent(html_6cbbf7b348ed2de74f95dcbe9b6963ee);
            
        

        marker_2890e02105139c54a3edcb492a073a08.bindPopup(popup_49539b4653e1238697a82e2aa85a504d)
        ;

        
    
    
            var marker_47c2cc55c061c7bb75d843c73099a536 = L.marker(
                [51.01921911505886, 4.479236320004818],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_cad8932cc04eac52756fa5e2db144d5b = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_47c2cc55c061c7bb75d843c73099a536.setIcon(icon_cad8932cc04eac52756fa5e2db144d5b);
        
    
        var popup_3d6adb2c002a8862110f9684d159904a = L.popup({"maxWidth": "100%"});

        
            
                var html_3748db5b12a81044d345830a760f8d10 = $(`<div id="html_3748db5b12a81044d345830a760f8d10" style="width: 100.0%; height: 100.0%;">Sfanje</div>`)[0];
                popup_3d6adb2c002a8862110f9684d159904a.setContent(html_3748db5b12a81044d345830a760f8d10);
            
        

        marker_47c2cc55c061c7bb75d843c73099a536.bindPopup(popup_3d6adb2c002a8862110f9684d159904a)
        ;

        
    
    
            var marker_56ecc87d92c820a038795b165e301e09 = L.marker(
                [51.02366189208262, 4.4819196120301354],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_ca7fdfbd2eee0dc6c1f25dd57d06f6b3 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_56ecc87d92c820a038795b165e301e09.setIcon(icon_ca7fdfbd2eee0dc6c1f25dd57d06f6b3);
        
    
        var popup_167a0449086e9a53990129b1f516eedc = L.popup({"maxWidth": "100%"});

        
            
                var html_3449a754478fa716f3e70ffa539b0a9f = $(`<div id="html_3449a754478fa716f3e70ffa539b0a9f" style="width: 100.0%; height: 100.0%;">Sham Nuts</div>`)[0];
                popup_167a0449086e9a53990129b1f516eedc.setContent(html_3449a754478fa716f3e70ffa539b0a9f);
            
        

        marker_56ecc87d92c820a038795b165e301e09.bindPopup(popup_167a0449086e9a53990129b1f516eedc)
        ;

        
    
    
            var marker_d03c64f5f51618e25f031026e7f22bae = L.marker(
                [51.01881979188837, 4.483474558562524],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_dc6f1a92b8b3fb58a6865353e709c2d7 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_d03c64f5f51618e25f031026e7f22bae.setIcon(icon_dc6f1a92b8b3fb58a6865353e709c2d7);
        
    
        var popup_6db9e417ffcfbcaf0929ae0c5ff8834f = L.popup({"maxWidth": "100%"});

        
            
                var html_3c0dff5ca96c8b3bf456bc0c7d04598b = $(`<div id="html_3c0dff5ca96c8b3bf456bc0c7d04598b" style="width: 100.0%; height: 100.0%;">Sultan</div>`)[0];
                popup_6db9e417ffcfbcaf0929ae0c5ff8834f.setContent(html_3c0dff5ca96c8b3bf456bc0c7d04598b);
            
        

        marker_d03c64f5f51618e25f031026e7f22bae.bindPopup(popup_6db9e417ffcfbcaf0929ae0c5ff8834f)
        ;

        
    
    
            var marker_dddafa9665022725c73199dab3b53d38 = L.marker(
                [51.0238792864279, 4.487683523748133],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_6f186e97e3cb450b1c1d0ce1242a6af5 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_dddafa9665022725c73199dab3b53d38.setIcon(icon_6f186e97e3cb450b1c1d0ce1242a6af5);
        
    
        var popup_4766ab215d06d35eac4a48451a54e797 = L.popup({"maxWidth": "100%"});

        
            
                var html_1f8827eba91256cce428496a27393491 = $(`<div id="html_1f8827eba91256cce428496a27393491" style="width: 100.0%; height: 100.0%;">Sushi Star</div>`)[0];
                popup_4766ab215d06d35eac4a48451a54e797.setContent(html_1f8827eba91256cce428496a27393491);
            
        

        marker_dddafa9665022725c73199dab3b53d38.bindPopup(popup_4766ab215d06d35eac4a48451a54e797)
        ;

        
    
    
            var marker_32a288ad55ac54c9a7ce396d2f83b6a5 = L.marker(
                [51.02346684093183, 4.475123082198011],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_2078671d63116ec6f3592b5cc3e1842d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_32a288ad55ac54c9a7ce396d2f83b6a5.setIcon(icon_2078671d63116ec6f3592b5cc3e1842d);
        
    
        var popup_227712f94029ae5a3b00afee76573b47 = L.popup({"maxWidth": "100%"});

        
            
                var html_52e21171515b898402af1a5ed844d240 = $(`<div id="html_52e21171515b898402af1a5ed844d240" style="width: 100.0%; height: 100.0%;">Taste King Pizza</div>`)[0];
                popup_227712f94029ae5a3b00afee76573b47.setContent(html_52e21171515b898402af1a5ed844d240);
            
        

        marker_32a288ad55ac54c9a7ce396d2f83b6a5.bindPopup(popup_227712f94029ae5a3b00afee76573b47)
        ;

        
    
    
            var marker_8f1f3ea9468cb5ad874c66ccaf95e9b2 = L.marker(
                [51.027217921406454, 4.47877849341389],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_3df767c06f0df5385a6af22cec247891 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_8f1f3ea9468cb5ad874c66ccaf95e9b2.setIcon(icon_3df767c06f0df5385a6af22cec247891);
        
    
        var popup_e538fa37cbb8ac846c614b6bcd2d5bc1 = L.popup({"maxWidth": "100%"});

        
            
                var html_31f0e38c67569900aa59251fcbfcab42 = $(`<div id="html_31f0e38c67569900aa59251fcbfcab42" style="width: 100.0%; height: 100.0%;">Thai cafe</div>`)[0];
                popup_e538fa37cbb8ac846c614b6bcd2d5bc1.setContent(html_31f0e38c67569900aa59251fcbfcab42);
            
        

        marker_8f1f3ea9468cb5ad874c66ccaf95e9b2.bindPopup(popup_e538fa37cbb8ac846c614b6bcd2d5bc1)
        ;

        
    
    
            var marker_fa3873c0b6aa79ffbe016836a9269659 = L.marker(
                [51.024731385714965, 4.476976153774588],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_b307f838054e9bc8ac6abe2276a9ae89 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_fa3873c0b6aa79ffbe016836a9269659.setIcon(icon_b307f838054e9bc8ac6abe2276a9ae89);
        
    
        var popup_436b756851f359b0519306081de96678 = L.popup({"maxWidth": "100%"});

        
            
                var html_d630b2b649f552b0554eca9149955713 = $(`<div id="html_d630b2b649f552b0554eca9149955713" style="width: 100.0%; height: 100.0%;">Thé Cacao Project</div>`)[0];
                popup_436b756851f359b0519306081de96678.setContent(html_d630b2b649f552b0554eca9149955713);
            
        

        marker_fa3873c0b6aa79ffbe016836a9269659.bindPopup(popup_436b756851f359b0519306081de96678)
        ;

        
    
    
            var marker_f70985051af61359d06ea31b79ab8eda = L.marker(
                [51.02183814327699, 4.474336669702702],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_2e2da73c5311d2f280a518db5f51b892 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_f70985051af61359d06ea31b79ab8eda.setIcon(icon_2e2da73c5311d2f280a518db5f51b892);
        
    
        var popup_5096fbc6c3ff92f5ef025da3591bf926 = L.popup({"maxWidth": "100%"});

        
            
                var html_05125c7340537fae17821200ea07cbce = $(`<div id="html_05125c7340537fae17821200ea07cbce" style="width: 100.0%; height: 100.0%;">Verace</div>`)[0];
                popup_5096fbc6c3ff92f5ef025da3591bf926.setContent(html_05125c7340537fae17821200ea07cbce);
            
        

        marker_f70985051af61359d06ea31b79ab8eda.bindPopup(popup_5096fbc6c3ff92f5ef025da3591bf926)
        ;

        
    
    
            var marker_f3717c38b4e6c391d15653f30cebde21 = L.marker(
                [51.02304858875265, 4.487371764288548],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_10eb08066af60b7c77043341eec5d8d2 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_f3717c38b4e6c391d15653f30cebde21.setIcon(icon_10eb08066af60b7c77043341eec5d8d2);
        
    
        var popup_e446e2dc0dd1876fbdccf7d1c95dd287 = L.popup({"maxWidth": "100%"});

        
            
                var html_4d327e51a210e3a46b4ebb44c6159d17 = $(`<div id="html_4d327e51a210e3a46b4ebb44c6159d17" style="width: 100.0%; height: 100.0%;">Via Via</div>`)[0];
                popup_e446e2dc0dd1876fbdccf7d1c95dd287.setContent(html_4d327e51a210e3a46b4ebb44c6159d17);
            
        

        marker_f3717c38b4e6c391d15653f30cebde21.bindPopup(popup_e446e2dc0dd1876fbdccf7d1c95dd287)
        ;

        
    
    
            var marker_5f98f45d16ce5f62135b4ab0345088e9 = L.marker(
                [51.02706394925471, 4.47923204222291],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_9e0fcd72eb4c9dcb0711d256f5bc5758 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_5f98f45d16ce5f62135b4ab0345088e9.setIcon(icon_9e0fcd72eb4c9dcb0711d256f5bc5758);
        
    
        var popup_3390d0be77c7aa906e347d3e2a369cb9 = L.popup({"maxWidth": "100%"});

        
            
                var html_b7f5b7881b0cd7af8dc20a330d804bae = $(`<div id="html_b7f5b7881b0cd7af8dc20a330d804bae" style="width: 100.0%; height: 100.0%;">Wasbar</div>`)[0];
                popup_3390d0be77c7aa906e347d3e2a369cb9.setContent(html_b7f5b7881b0cd7af8dc20a330d804bae);
            
        

        marker_5f98f45d16ce5f62135b4ab0345088e9.bindPopup(popup_3390d0be77c7aa906e347d3e2a369cb9)
        ;

        
    
    
            var marker_a68af1fcfca38c9c690358d7240dd3cf = L.marker(
                [51.01912128240872, 4.482248133776901],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_ee2db28c6a0c9e7f0bfe1946ef0a8027 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_a68af1fcfca38c9c690358d7240dd3cf.setIcon(icon_ee2db28c6a0c9e7f0bfe1946ef0a8027);
        
    
        var popup_88722e32c14ec46a23d22f0f99a1d032 = L.popup({"maxWidth": "100%"});

        
            
                var html_39d565eec86802b2a2530c36fed15fed = $(`<div id="html_39d565eec86802b2a2530c36fed15fed" style="width: 100.0%; height: 100.0%;">Ying Bing</div>`)[0];
                popup_88722e32c14ec46a23d22f0f99a1d032.setContent(html_39d565eec86802b2a2530c36fed15fed);
            
        

        marker_a68af1fcfca38c9c690358d7240dd3cf.bindPopup(popup_88722e32c14ec46a23d22f0f99a1d032)
        ;

        
    
    
            var marker_14cbfee7005d0208f0918270072b520f = L.marker(
                [51.023013959582016, 4.474728704586039],
                {}
            ).addTo(feature_group_0af39c2523be50e1713daf93775e0e3b);
        
    
            var icon_daabe53467ed9ffad4450951a64fd8ad = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_14cbfee7005d0208f0918270072b520f.setIcon(icon_daabe53467ed9ffad4450951a64fd8ad);
        
    
        var popup_8ff5a81693ce15ed72d68197fd79cd4f = L.popup({"maxWidth": "100%"});

        
            
                var html_7a888b073fdb6f9162259ad689a922c4 = $(`<div id="html_7a888b073fdb6f9162259ad689a922c4" style="width: 100.0%; height: 100.0%;">Bakkerij Badr</div>`)[0];
                popup_8ff5a81693ce15ed72d68197fd79cd4f.setContent(html_7a888b073fdb6f9162259ad689a922c4);
            
        

        marker_14cbfee7005d0208f0918270072b520f.bindPopup(popup_8ff5a81693ce15ed72d68197fd79cd4f)
        ;

        
    
    
            var layer_control_ef733a636d9a7078ce04c89186f638ac_layers = {
                base_layers : {
                    "openstreetmap" : tile_layer_963b79af84211a001c28c1941a2efe0a,
                },
                overlays :  {
                    "macro_element_fc48d82ffbf9a2cf3ad4c57837871968" : marker_cluster_fc48d82ffbf9a2cf3ad4c57837871968,
                    "restaurants groep 1" : feature_group_8fb885e02de6f0bc0d1ebbf2b776d17c,
                    "restaurants groep 2" : feature_group_0af39c2523be50e1713daf93775e0e3b,
                },
            };
            let layer_control_ef733a636d9a7078ce04c89186f638ac = L.control.layers(
                layer_control_ef733a636d9a7078ce04c89186f638ac_layers.base_layers,
                layer_control_ef733a636d9a7078ce04c89186f638ac_layers.overlays,
                {"autoZIndex": true, "collapsed": true, "position": "topright"}
            ).addTo(map_4be3be938716243d410ab569db9a71bf);

        
    
            tile_layer_963b79af84211a001c28c1941a2efe0a.addTo(map_4be3be938716243d410ab569db9a71bf);
        
    
            marker_cluster_fc48d82ffbf9a2cf3ad4c57837871968.addTo(map_4be3be938716243d410ab569db9a71bf);
        
    
            tile_layer_963b79af84211a001c28c1941a2efe0a.addTo(map_4be3be938716243d410ab569db9a71bf);
        
    
            marker_cluster_fc48d82ffbf9a2cf3ad4c57837871968.addTo(map_4be3be938716243d410ab569db9a71bf);
        
</script>
</html>
