# community-partners-map
'''html
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
    <link rel="stylesheet" href="https://netdna.bootstrapcdn.com/bootstrap/3.0.0/css/bootstrap-glyphicons.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.2.0/css/all.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/python-visualization/folium/folium/templates/leaflet.awesome.rotate.min.css"/>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_0645f74934c2e18d754fe391c86431ae {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
                .leaflet-container { font-size: 1rem; }
            </style>
        
</head>
<body>
    
    
            <div class="folium-map" id="map_0645f74934c2e18d754fe391c86431ae" ></div>
        
</body>
<script>
    
    
            var map_0645f74934c2e18d754fe391c86431ae = L.map(
                "map_0645f74934c2e18d754fe391c86431ae",
                {
                    center: [41.8781, -87.6298],
                    crs: L.CRS.EPSG3857,
                    zoom: 10,
                    zoomControl: true,
                    preferCanvas: false,
                }
            );

            

        
    
            var tile_layer_b75ca1bb8163d27069684952ee70a580 = L.tileLayer(
                "https://tile.openstreetmap.org/{z}/{x}/{y}.png",
                {"attribution": "\u0026copy; \u003ca href=\"https://www.openstreetmap.org/copyright\"\u003eOpenStreetMap\u003c/a\u003e contributors", "detectRetina": false, "maxNativeZoom": 19, "maxZoom": 19, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            );
        
    
            tile_layer_b75ca1bb8163d27069684952ee70a580.addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var marker_d3107f149be46c1a29fb5f4c7d4b871a = L.marker(
                [32.105017, 76.477064],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_b70cc785950ecad5c00939af00ed17ef = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_d3107f149be46c1a29fb5f4c7d4b871a.setIcon(icon_b70cc785950ecad5c00939af00ed17ef);
        
    
        var popup_e746cce3a14ef873fcbce39644469b14 = L.popup({"maxWidth": "100%"});

        
            
                var html_6922f9311cfe729baad985cacc6e8701 = $(`<div id="html_6922f9311cfe729baad985cacc6e8701" style="width: 100.0%; height: 100.0%;">USWA Schools  (Addressing Social Issues)</div>`)[0];
                popup_e746cce3a14ef873fcbce39644469b14.setContent(html_6922f9311cfe729baad985cacc6e8701);
            
        

        marker_d3107f149be46c1a29fb5f4c7d4b871a.bindPopup(popup_e746cce3a14ef873fcbce39644469b14)
        ;

        
    
    
            var marker_dd335b74ec48ce192f763629915880f9 = L.marker(
                [41.87874, -87.639004],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_52bdc135afad9549af02b55dfc2f8f17 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_dd335b74ec48ce192f763629915880f9.setIcon(icon_52bdc135afad9549af02b55dfc2f8f17);
        
    
        var popup_649a36decdf753f158efc943a0650df3 = L.popup({"maxWidth": "100%"});

        
            
                var html_f649a0bb8860fa0be69eff51117aa900 = $(`<div id="html_f649a0bb8860fa0be69eff51117aa900" style="width: 100.0%; height: 100.0%;">The Preservation Compact (Addressing Social Issues)</div>`)[0];
                popup_649a36decdf753f158efc943a0650df3.setContent(html_f649a0bb8860fa0be69eff51117aa900);
            
        

        marker_dd335b74ec48ce192f763629915880f9.bindPopup(popup_649a36decdf753f158efc943a0650df3)
        ;

        
    
    
            var marker_fcb4f84a9c26e0ec04e28fa8cc5b9d0b = L.marker(
                [42.03758, -87.724598],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_9102617015beff83e19b23f716fd15f3 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_fcb4f84a9c26e0ec04e28fa8cc5b9d0b.setIcon(icon_9102617015beff83e19b23f716fd15f3);
        
    
        var popup_aee6fbb0af2338c3c371d5bd7a708288 = L.popup({"maxWidth": "100%"});

        
            
                var html_1636d75b1c2348039046df63d20f8b8b = $(`<div id="html_1636d75b1c2348039046df63d20f8b8b" style="width: 100.0%; height: 100.0%;">Z Center (Addressing Social Issues)</div>`)[0];
                popup_aee6fbb0af2338c3c371d5bd7a708288.setContent(html_1636d75b1c2348039046df63d20f8b8b);
            
        

        marker_fcb4f84a9c26e0ec04e28fa8cc5b9d0b.bindPopup(popup_aee6fbb0af2338c3c371d5bd7a708288)
        ;

        
    
    
            var marker_9b0059679a808e2882570c6896905413 = L.marker(
                [41.878245, -87.643703],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_fbe4509ee254474531c9a2168bf0499e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_9b0059679a808e2882570c6896905413.setIcon(icon_fbe4509ee254474531c9a2168bf0499e);
        
    
        var popup_87e0f5a224cb04dea68789e346514622 = L.popup({"maxWidth": "100%"});

        
            
                var html_ed233bb93582e35b4dd6f7711b5240ea = $(`<div id="html_ed233bb93582e35b4dd6f7711b5240ea" style="width: 100.0%; height: 100.0%;">Cara Chicago (Addressing Social Issues)</div>`)[0];
                popup_87e0f5a224cb04dea68789e346514622.setContent(html_ed233bb93582e35b4dd6f7711b5240ea);
            
        

        marker_9b0059679a808e2882570c6896905413.bindPopup(popup_87e0f5a224cb04dea68789e346514622)
        ;

        
    
    
            var marker_71a9da4f4f287cd489e85f95ceb687d9 = L.marker(
                [41.80388, -87.6132],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_7eec94ca5bfbeb03efee909d6761642b = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_71a9da4f4f287cd489e85f95ceb687d9.setIcon(icon_7eec94ca5bfbeb03efee909d6761642b);
        
    
        var popup_c7ddc7b1618c6f318bcab695d4e2fb94 = L.popup({"maxWidth": "100%"});

        
            
                var html_49c3d391b51b191d8ce697c295d64cb6 = $(`<div id="html_49c3d391b51b191d8ce697c295d64cb6" style="width: 100.0%; height: 100.0%;">Chicago Commons (Addressing Social Issues)</div>`)[0];
                popup_c7ddc7b1618c6f318bcab695d4e2fb94.setContent(html_49c3d391b51b191d8ce697c295d64cb6);
            
        

        marker_71a9da4f4f287cd489e85f95ceb687d9.bindPopup(popup_c7ddc7b1618c6f318bcab695d4e2fb94)
        ;

        
    
    
            var marker_0c6b81f39bda578db4f8d588ca353318 = L.marker(
                [41.87851, -87.627079],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_af553c5e082fb7442c823af7d360ae00 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_0c6b81f39bda578db4f8d588ca353318.setIcon(icon_af553c5e082fb7442c823af7d360ae00);
        
    
        var popup_b517bf8f8fe371fd7d0c460a325fa513 = L.popup({"maxWidth": "100%"});

        
            
                var html_4a4e25f4115ce1f7bc218492990bfbce = $(`<div id="html_4a4e25f4115ce1f7bc218492990bfbce" style="width: 100.0%; height: 100.0%;">DePaul USA (Addressing Social Issues)</div>`)[0];
                popup_b517bf8f8fe371fd7d0c460a325fa513.setContent(html_4a4e25f4115ce1f7bc218492990bfbce);
            
        

        marker_0c6b81f39bda578db4f8d588ca353318.bindPopup(popup_b517bf8f8fe371fd7d0c460a325fa513)
        ;

        
    
    
            var marker_2c6cfe11061ec9e940a7778297b23137 = L.marker(
                [41.90481, -87.66921],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_0aa106ca199b18e8cb455833f899bc2a = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_2c6cfe11061ec9e940a7778297b23137.setIcon(icon_0aa106ca199b18e8cb455833f899bc2a);
        
    
        var popup_77b269bbb51f279a08a109068035fa9c = L.popup({"maxWidth": "100%"});

        
            
                var html_e0fa02cd83fbbfebdb3dd3cb09b21c4d = $(`<div id="html_e0fa02cd83fbbfebdb3dd3cb09b21c4d" style="width: 100.0%; height: 100.0%;">826Chi (Addressing Social Issues)</div>`)[0];
                popup_77b269bbb51f279a08a109068035fa9c.setContent(html_e0fa02cd83fbbfebdb3dd3cb09b21c4d);
            
        

        marker_2c6cfe11061ec9e940a7778297b23137.bindPopup(popup_77b269bbb51f279a08a109068035fa9c)
        ;

        
    
    
            var marker_448c5e9232c5f43041aece582d264a9b = L.marker(
                [41.893164, -87.661408],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_c71e341b36cdf5573cd3e3f8a0456184 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_448c5e9232c5f43041aece582d264a9b.setIcon(icon_c71e341b36cdf5573cd3e3f8a0456184);
        
    
        var popup_f44e4106e653df7ebbb3cd3c97a56cd3 = L.popup({"maxWidth": "100%"});

        
            
                var html_38a547e631ce36ddb3ae3f44a02877f6 = $(`<div id="html_38a547e631ce36ddb3ae3f44a02877f6" style="width: 100.0%; height: 100.0%;">Erie Neighborhood House (Addressing Social Issues)</div>`)[0];
                popup_f44e4106e653df7ebbb3cd3c97a56cd3.setContent(html_38a547e631ce36ddb3ae3f44a02877f6);
            
        

        marker_448c5e9232c5f43041aece582d264a9b.bindPopup(popup_f44e4106e653df7ebbb3cd3c97a56cd3)
        ;

        
    
    
            var marker_e985857f5d25db7b21280585651e14d6 = L.marker(
                [41.93115, -87.757779],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_edcffdfd744c21a9b2f3a754df4f81c7 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_e985857f5d25db7b21280585651e14d6.setIcon(icon_edcffdfd744c21a9b2f3a754df4f81c7);
        
    
        var popup_c5850073b42201b6068d3cbb628308d5 = L.popup({"maxWidth": "100%"});

        
            
                var html_d2ab255727b7b6b8702849f4dfef4ebc = $(`<div id="html_d2ab255727b7b6b8702849f4dfef4ebc" style="width: 100.0%; height: 100.0%;">Northwest Side Housing Center (Addressing Social Issues)</div>`)[0];
                popup_c5850073b42201b6068d3cbb628308d5.setContent(html_d2ab255727b7b6b8702849f4dfef4ebc);
            
        

        marker_e985857f5d25db7b21280585651e14d6.bindPopup(popup_c5850073b42201b6068d3cbb628308d5)
        ;

        
    
    
            var marker_26475d9d801e298d1f3aadd58ae36f85 = L.marker(
                [41.968805, -87.659198],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_59ae7ed53343c46df39fc9091fd6389f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_26475d9d801e298d1f3aadd58ae36f85.setIcon(icon_59ae7ed53343c46df39fc9091fd6389f);
        
    
        var popup_1c0b9926db96cbe968b5f430d1103d90 = L.popup({"maxWidth": "100%"});

        
            
                var html_cb07f566d0c79ca6caa7f78e8a4a178c = $(`<div id="html_cb07f566d0c79ca6caa7f78e8a4a178c" style="width: 100.0%; height: 100.0%;">RefugeeOne (Addressing Social Issues)</div>`)[0];
                popup_1c0b9926db96cbe968b5f430d1103d90.setContent(html_cb07f566d0c79ca6caa7f78e8a4a178c);
            
        

        marker_26475d9d801e298d1f3aadd58ae36f85.bindPopup(popup_1c0b9926db96cbe968b5f430d1103d90)
        ;

        
    
    
            var marker_67bd214ab0b3abee18f91850154a2c78 = L.marker(
                [41.848969, -87.696476],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_c97381bebc2c3dc1b85af4e4e2edc5ea = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_67bd214ab0b3abee18f91850154a2c78.setIcon(icon_c97381bebc2c3dc1b85af4e4e2edc5ea);
        
    
        var popup_ece671841006a2280bd367cb9922f67c = L.popup({"maxWidth": "100%"});

        
            
                var html_a68de373b6317f05240f47890a68ed7c = $(`<div id="html_a68de373b6317f05240f47890a68ed7c" style="width: 100.0%; height: 100.0%;">Telpochcali Community Education Project (Addressing Social Issues)</div>`)[0];
                popup_ece671841006a2280bd367cb9922f67c.setContent(html_a68de373b6317f05240f47890a68ed7c);
            
        

        marker_67bd214ab0b3abee18f91850154a2c78.bindPopup(popup_ece671841006a2280bd367cb9922f67c)
        ;

        
    
    
            var marker_fabbb39331b1eb00df8ab0c7407fafb9 = L.marker(
                [41.97953, -87.65438],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_dbba0fc063c88a9837a9efea1e890dbf = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_fabbb39331b1eb00df8ab0c7407fafb9.setIcon(icon_dbba0fc063c88a9837a9efea1e890dbf);
        
    
        var popup_31f2e5a56e387a03b3bd306dbf0c4919 = L.popup({"maxWidth": "100%"});

        
            
                var html_d83fe62399c6c9b55b58f0d2b23123b8 = $(`<div id="html_d83fe62399c6c9b55b58f0d2b23123b8" style="width: 100.0%; height: 100.0%;">Care For Real (Addressing Social Issues)</div>`)[0];
                popup_31f2e5a56e387a03b3bd306dbf0c4919.setContent(html_d83fe62399c6c9b55b58f0d2b23123b8);
            
        

        marker_fabbb39331b1eb00df8ab0c7407fafb9.bindPopup(popup_31f2e5a56e387a03b3bd306dbf0c4919)
        ;

        
    
    
            var marker_9646616c140d01d38a63efe178e9a731 = L.marker(
                [42.020287, -87.673301],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_64aa35a8e39a8b1bb068171a0e10a9bb = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_9646616c140d01d38a63efe178e9a731.setIcon(icon_64aa35a8e39a8b1bb068171a0e10a9bb);
        
    
        var popup_c671cb9cb6956dadea22678ac0312046 = L.popup({"maxWidth": "100%"});

        
            
                var html_c9278735691f9b53f85694042aacfced = $(`<div id="html_c9278735691f9b53f85694042aacfced" style="width: 100.0%; height: 100.0%;">The Recyclery Collective (Addressing Social Issues)</div>`)[0];
                popup_c671cb9cb6956dadea22678ac0312046.setContent(html_c9278735691f9b53f85694042aacfced);
            
        

        marker_9646616c140d01d38a63efe178e9a731.bindPopup(popup_c671cb9cb6956dadea22678ac0312046)
        ;

        
    
    
            var marker_1e5aab3b2081c9cf19cac377d197c5ec = L.marker(
                [41.906022, -87.670191],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_6e4e1c8d998137ed64ebff37d2478849 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_1e5aab3b2081c9cf19cac377d197c5ec.setIcon(icon_6e4e1c8d998137ed64ebff37d2478849);
        
    
        var popup_c77c9fba996acd2b1f1feb66c1b641ae = L.popup({"maxWidth": "100%"});

        
            
                var html_732ec4e9f3d3c0e7405e8f6276fad0bb = $(`<div id="html_732ec4e9f3d3c0e7405e8f6276fad0bb" style="width: 100.0%; height: 100.0%;">Midwest Books to Prisoners (Addressing Social Issues)</div>`)[0];
                popup_c77c9fba996acd2b1f1feb66c1b641ae.setContent(html_732ec4e9f3d3c0e7405e8f6276fad0bb);
            
        

        marker_1e5aab3b2081c9cf19cac377d197c5ec.bindPopup(popup_c77c9fba996acd2b1f1feb66c1b641ae)
        ;

        
    
    
            var marker_59e332bcda3218b64d02aef8768a2d41 = L.marker(
                [39.381266, -97.922211],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_3dbbb188801468740b0bd62ebdc9237a = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_59e332bcda3218b64d02aef8768a2d41.setIcon(icon_3dbbb188801468740b0bd62ebdc9237a);
        
    
        var popup_05e70d924549dfed87b7977c6b84d829 = L.popup({"maxWidth": "100%"});

        
            
                var html_73fe4080899ec308d79c091c1db62ecd = $(`<div id="html_73fe4080899ec308d79c091c1db62ecd" style="width: 100.0%; height: 100.0%;">Arts of Life, Introspect Youth Services, Living Works After School Program, Telpochcali Community Education Project, Mujeres Latinas En Accion, Erie Neighborhood House, Chicago Lights, Cornerstone Community Outreach, All Stars Project of Chicago (Addressing Social Issues)</div>`)[0];
                popup_05e70d924549dfed87b7977c6b84d829.setContent(html_73fe4080899ec308d79c091c1db62ecd);
            
        

        marker_59e332bcda3218b64d02aef8768a2d41.bindPopup(popup_05e70d924549dfed87b7977c6b84d829)
        ;

        
    
    
            var marker_8480576fcf2c2a1f5b0c9252573bd240 = L.marker(
                [41.750907, -87.570751],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_18436fa058d31f0163a3e5f6da7864d3 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_8480576fcf2c2a1f5b0c9252573bd240.setIcon(icon_18436fa058d31f0163a3e5f6da7864d3);
        
    
        var popup_b8ff79a0a541ae539dbfe33dbad626dc = L.popup({"maxWidth": "100%"});

        
            
                var html_afb085536aa3a28d89f03c09c1c5caea = $(`<div id="html_afb085536aa3a28d89f03c09c1c5caea" style="width: 100.0%; height: 100.0%;">Project I Am (Addressing Social Issues)</div>`)[0];
                popup_b8ff79a0a541ae539dbfe33dbad626dc.setContent(html_afb085536aa3a28d89f03c09c1c5caea);
            
        

        marker_8480576fcf2c2a1f5b0c9252573bd240.bindPopup(popup_b8ff79a0a541ae539dbfe33dbad626dc)
        ;

        
    
    
            var marker_cec127493b2b0740ec21fc2e26b1534a = L.marker(
                [41.96665, -87.65899],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_3356ed591714070794fba0858e365b0b = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_cec127493b2b0740ec21fc2e26b1534a.setIcon(icon_3356ed591714070794fba0858e365b0b);
        
    
        var popup_31ea493e97e26dfd9d6a17863b3de9c9 = L.popup({"maxWidth": "100%"});

        
            
                var html_cd6856a34e89e15c3d0b85fef87a0b0c = $(`<div id="html_cd6856a34e89e15c3d0b85fef87a0b0c" style="width: 100.0%; height: 100.0%;">Cornerstone Community Outreach (Addressing Social Issues)</div>`)[0];
                popup_31ea493e97e26dfd9d6a17863b3de9c9.setContent(html_cd6856a34e89e15c3d0b85fef87a0b0c);
            
        

        marker_cec127493b2b0740ec21fc2e26b1534a.bindPopup(popup_31ea493e97e26dfd9d6a17863b3de9c9)
        ;

        
    
    
            var marker_3863950c1218ed69623889b319b79eac = L.marker(
                [39.381266, -97.922211],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_8e4596c3ef0355de9e975cb1f6a292d9 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_3863950c1218ed69623889b319b79eac.setIcon(icon_8e4596c3ef0355de9e975cb1f6a292d9);
        
    
        var popup_7debb729f355e5bcbb68e14381c80b7e = L.popup({"maxWidth": "100%"});

        
            
                var html_321d208b98f258647167da8017227def = $(`<div id="html_321d208b98f258647167da8017227def" style="width: 100.0%; height: 100.0%;">Muslim Education Center, Iraqi Mutual Aid Society, Orland Park Prayer Center, Precious Blood Ministry (Addressing Social Issues)</div>`)[0];
                popup_7debb729f355e5bcbb68e14381c80b7e.setContent(html_321d208b98f258647167da8017227def);
            
        

        marker_3863950c1218ed69623889b319b79eac.bindPopup(popup_7debb729f355e5bcbb68e14381c80b7e)
        ;

        
    
    
            var marker_0f32ff9f3707d0b971ca9e48b176344e = L.marker(
                [41.80356, -87.667643],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_609e1d9954a4009a36c033b966e566af = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_0f32ff9f3707d0b971ca9e48b176344e.setIcon(icon_609e1d9954a4009a36c033b966e566af);
        
    
        var popup_a09c19625aabfb787bdaa5f21a2acf6a = L.popup({"maxWidth": "100%"});

        
            
                var html_088493fe69fe9912f6903036c05b26a7 = $(`<div id="html_088493fe69fe9912f6903036c05b26a7" style="width: 100.0%; height: 100.0%;">Peace and Education Coalition of the Back of the Yards (Addressing Social Issues)</div>`)[0];
                popup_a09c19625aabfb787bdaa5f21a2acf6a.setContent(html_088493fe69fe9912f6903036c05b26a7);
            
        

        marker_0f32ff9f3707d0b971ca9e48b176344e.bindPopup(popup_a09c19625aabfb787bdaa5f21a2acf6a)
        ;

        
    
    
            var marker_f09fa0a7ae7b31118aca8f5485320289 = L.marker(
                [41.987199, -87.845914],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_e43018be2f9c5ffad0ce9e9d27c83849 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_f09fa0a7ae7b31118aca8f5485320289.setIcon(icon_e43018be2f9c5ffad0ce9e9d27c83849);
        
    
        var popup_2115d5765e6d1a55e02a4e4e4287cc39 = L.popup({"maxWidth": "100%"});

        
            
                var html_7ea2e2e0d5de8267b7568255baee6c37 = $(`<div id="html_7ea2e2e0d5de8267b7568255baee6c37" style="width: 100.0%; height: 100.0%;">Kids Above All (Addressing Social Issues)</div>`)[0];
                popup_2115d5765e6d1a55e02a4e4e4287cc39.setContent(html_7ea2e2e0d5de8267b7568255baee6c37);
            
        

        marker_f09fa0a7ae7b31118aca8f5485320289.bindPopup(popup_2115d5765e6d1a55e02a4e4e4287cc39)
        ;

        
    
    
            var marker_1d0ce8fc83a4e737fb698579176260b5 = L.marker(
                [41.96877, -87.659187],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_080f9f0a4b4150571a9b57b4ed8d57a5 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_1d0ce8fc83a4e737fb698579176260b5.setIcon(icon_080f9f0a4b4150571a9b57b4ed8d57a5);
        
    
        var popup_4411fb74549f69cfe0ae7290e018858b = L.popup({"maxWidth": "100%"});

        
            
                var html_0e0cf9747d0563afd36c334b73f61eb1 = $(`<div id="html_0e0cf9747d0563afd36c334b73f61eb1" style="width: 100.0%; height: 100.0%;">RefugeeOne (Addressing Social Issues)</div>`)[0];
                popup_4411fb74549f69cfe0ae7290e018858b.setContent(html_0e0cf9747d0563afd36c334b73f61eb1);
            
        

        marker_1d0ce8fc83a4e737fb698579176260b5.bindPopup(popup_4411fb74549f69cfe0ae7290e018858b)
        ;

        
    
    
            var marker_0b9ed93a67b2e4ce1d6ffbde30a9b026 = L.marker(
                [41.92393, -87.653182],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_7d289b5364f7ee4902c47029916391eb = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_0b9ed93a67b2e4ce1d6ffbde30a9b026.setIcon(icon_7d289b5364f7ee4902c47029916391eb);
        
    
        var popup_15877ba3cb6222665c743b1b078ddd20 = L.popup({"maxWidth": "100%"});

        
            
                var html_84b85fd1047a022053fb07c4b1139e13 = $(`<div id="html_84b85fd1047a022053fb07c4b1139e13" style="width: 100.0%; height: 100.0%;">Cradles to Crayons (Addressing Social Issues)</div>`)[0];
                popup_15877ba3cb6222665c743b1b078ddd20.setContent(html_84b85fd1047a022053fb07c4b1139e13);
            
        

        marker_0b9ed93a67b2e4ce1d6ffbde30a9b026.bindPopup(popup_15877ba3cb6222665c743b1b078ddd20)
        ;

        
    
    
            var marker_9d6f5a5f08d91822d9b910eccbe3a0aa = L.marker(
                [41.878523, -87.625588],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_a498c141a77bd486b1b07f7c0d3d54eb = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_9d6f5a5f08d91822d9b910eccbe3a0aa.setIcon(icon_a498c141a77bd486b1b07f7c0d3d54eb);
        
    
        var popup_78a05551df9904760168f951d17e0270 = L.popup({"maxWidth": "100%"});

        
            
                var html_b9504b18c6e9607829bf7c9c8b6cd41d = $(`<div id="html_b9504b18c6e9607829bf7c9c8b6cd41d" style="width: 100.0%; height: 100.0%;">Chicago Housing Authority (Addressing Social Issues)</div>`)[0];
                popup_78a05551df9904760168f951d17e0270.setContent(html_b9504b18c6e9607829bf7c9c8b6cd41d);
            
        

        marker_9d6f5a5f08d91822d9b910eccbe3a0aa.bindPopup(popup_78a05551df9904760168f951d17e0270)
        ;

        
    
    
            var marker_28868ac34dc85f7670b73e1f4d68938f = L.marker(
                [42.038474, -87.84737],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_31366847a9bfe8ce50459429b59aa6c1 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_28868ac34dc85f7670b73e1f4d68938f.setIcon(icon_31366847a9bfe8ce50459429b59aa6c1);
        
    
        var popup_243c8a83ac2e1d77a0f22eb9dd82f787 = L.popup({"maxWidth": "100%"});

        
            
                var html_fb7f4f5e28b2092b177a013b1f148f73 = $(`<div id="html_fb7f4f5e28b2092b177a013b1f148f73" style="width: 100.0%; height: 100.0%;">Advocate Aurora Health - Advocate Lutheran General Hospital & Advocate Condell Medical Center (Addressing Social Issues)</div>`)[0];
                popup_243c8a83ac2e1d77a0f22eb9dd82f787.setContent(html_fb7f4f5e28b2092b177a013b1f148f73);
            
        

        marker_28868ac34dc85f7670b73e1f4d68938f.bindPopup(popup_243c8a83ac2e1d77a0f22eb9dd82f787)
        ;

        
    
    
            var marker_ae3c09a205cae01fc912aef94e1c381b = L.marker(
                [41.96877, -87.659187],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_4ff2a64050739933fb05ce18ede74049 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_ae3c09a205cae01fc912aef94e1c381b.setIcon(icon_4ff2a64050739933fb05ce18ede74049);
        
    
        var popup_30d239682740a4e860cb80d93194486f = L.popup({"maxWidth": "100%"});

        
            
                var html_83ca56befe39de44bea1f832ab3deb2b = $(`<div id="html_83ca56befe39de44bea1f832ab3deb2b" style="width: 100.0%; height: 100.0%;">RefugeeOne (Addressing Social Issues)</div>`)[0];
                popup_30d239682740a4e860cb80d93194486f.setContent(html_83ca56befe39de44bea1f832ab3deb2b);
            
        

        marker_ae3c09a205cae01fc912aef94e1c381b.bindPopup(popup_30d239682740a4e860cb80d93194486f)
        ;

        
    
    
            var marker_084df35bdf7bb9d50761272d143f84ea = L.marker(
                [41.86295, -87.71418],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_c6ef2a428f63cd0885b89b4f1dcca867 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_084df35bdf7bb9d50761272d143f84ea.setIcon(icon_c6ef2a428f63cd0885b89b4f1dcca867);
        
    
        var popup_637eb968bc1770faa756a9fae7fed947 = L.popup({"maxWidth": "100%"});

        
            
                var html_fe4123ca67b042506a76fce6c2bf694c = $(`<div id="html_fe4123ca67b042506a76fce6c2bf694c" style="width: 100.0%; height: 100.0%;">Lawndale Elementary Community Academy , Chicago Public Schools (Addressing Social Issues)</div>`)[0];
                popup_637eb968bc1770faa756a9fae7fed947.setContent(html_fe4123ca67b042506a76fce6c2bf694c);
            
        

        marker_084df35bdf7bb9d50761272d143f84ea.bindPopup(popup_637eb968bc1770faa756a9fae7fed947)
        ;

        
    
    
            var marker_1813cec276c58f090e037f4563a4ae87 = L.marker(
                [41.86295, -87.71418],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_d595b0a7dedfeb610cca2c1e28b9a854 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_1813cec276c58f090e037f4563a4ae87.setIcon(icon_d595b0a7dedfeb610cca2c1e28b9a854);
        
    
        var popup_773cd3a58641256870b76ebf58d5141e = L.popup({"maxWidth": "100%"});

        
            
                var html_a0befc59000b1b6ffa018105679f536e = $(`<div id="html_a0befc59000b1b6ffa018105679f536e" style="width: 100.0%; height: 100.0%;">Lawndale Elementary Community Academy , UCAN, Chicago Public Schools, I Am Able Center (Addressing Social Issues)</div>`)[0];
                popup_773cd3a58641256870b76ebf58d5141e.setContent(html_a0befc59000b1b6ffa018105679f536e);
            
        

        marker_1813cec276c58f090e037f4563a4ae87.bindPopup(popup_773cd3a58641256870b76ebf58d5141e)
        ;

        
    
    
            var marker_4e559539331a9b52126c8d5df418c26f = L.marker(
                [41.85091, -87.701903],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_8c943c4d44b4d1a87b17cdb599d76b79 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_4e559539331a9b52126c8d5df418c26f.setIcon(icon_8c943c4d44b4d1a87b17cdb599d76b79);
        
    
        var popup_445a82e527b7e5cd6509b0a288c4e86b = L.popup({"maxWidth": "100%"});

        
            
                var html_63ea74d7b3b99b5bc1b8125ae4abc881 = $(`<div id="html_63ea74d7b3b99b5bc1b8125ae4abc881" style="width: 100.0%; height: 100.0%;">Our Lady of Tepeyac, Archdiocese of Chicago (Addressing Social Issues)</div>`)[0];
                popup_445a82e527b7e5cd6509b0a288c4e86b.setContent(html_63ea74d7b3b99b5bc1b8125ae4abc881);
            
        

        marker_4e559539331a9b52126c8d5df418c26f.bindPopup(popup_445a82e527b7e5cd6509b0a288c4e86b)
        ;

        
    
    
            var marker_3320eccb71fc9de4df6659856fd8bf54 = L.marker(
                [41.86326, -87.713375],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_d4d8a3de24b6e8d8c2d6fe505418fdd0 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_3320eccb71fc9de4df6659856fd8bf54.setIcon(icon_d4d8a3de24b6e8d8c2d6fe505418fdd0);
        
    
        var popup_7fdadd43a67414c2185f10c81ced57e2 = L.popup({"maxWidth": "100%"});

        
            
                var html_4053a09126dcee636d3b252481b20250 = $(`<div id="html_4053a09126dcee636d3b252481b20250" style="width: 100.0%; height: 100.0%;">Lawndale Elementary Community Academy  (Addressing Social Issues)</div>`)[0];
                popup_7fdadd43a67414c2185f10c81ced57e2.setContent(html_4053a09126dcee636d3b252481b20250);
            
        

        marker_3320eccb71fc9de4df6659856fd8bf54.bindPopup(popup_7fdadd43a67414c2185f10c81ced57e2)
        ;

        
    
    
            var marker_ef07bccfd7746561ad5199fcbd7983b8 = L.marker(
                [41.817325, -87.607114],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_9fdbd227e47fb99a6347cbb4a1c0e6ac = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_ef07bccfd7746561ad5199fcbd7983b8.setIcon(icon_9fdbd227e47fb99a6347cbb4a1c0e6ac);
        
    
        var popup_9853a92467628a769fdbb87b3819997a = L.popup({"maxWidth": "100%"});

        
            
                var html_b62d8c7a86aad0f7d0eaf2ce75993e94 = $(`<div id="html_b62d8c7a86aad0f7d0eaf2ce75993e94" style="width: 100.0%; height: 100.0%;">Community Justice for Youth Institute (Addressing Social Issues)</div>`)[0];
                popup_9853a92467628a769fdbb87b3819997a.setContent(html_b62d8c7a86aad0f7d0eaf2ce75993e94);
            
        

        marker_ef07bccfd7746561ad5199fcbd7983b8.bindPopup(popup_9853a92467628a769fdbb87b3819997a)
        ;

        
    
    
            var marker_44c6da162ea5bcb8fe72ed111bb38143 = L.marker(
                [41.88101, -87.63431],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_7e23608f5289f1cfefc72bef64a9b7c7 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_44c6da162ea5bcb8fe72ed111bb38143.setIcon(icon_7e23608f5289f1cfefc72bef64a9b7c7);
        
    
        var popup_f37f428db91c04176723442e16ff63cd = L.popup({"maxWidth": "100%"});

        
            
                var html_d4165b5a82bd6d019f1122bd87d92206 = $(`<div id="html_d4165b5a82bd6d019f1122bd87d92206" style="width: 100.0%; height: 100.0%;">AIDS Foundation of Chicago (Addressing Social Issues)</div>`)[0];
                popup_f37f428db91c04176723442e16ff63cd.setContent(html_d4165b5a82bd6d019f1122bd87d92206);
            
        

        marker_44c6da162ea5bcb8fe72ed111bb38143.bindPopup(popup_f37f428db91c04176723442e16ff63cd)
        ;

        
    
    
            var marker_84092ee6514ec8e011fe6ac5d2509b6b = L.marker(
                [41.92586, -87.64423],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_41cf5bdd88921eef632d9b90086922c4 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_84092ee6514ec8e011fe6ac5d2509b6b.setIcon(icon_41cf5bdd88921eef632d9b90086922c4);
        
    
        var popup_51035c8efbbabbaeba60eab614072a35 = L.popup({"maxWidth": "100%"});

        
            
                var html_39b8d38609ff0ed34a1a412c54df8240 = $(`<div id="html_39b8d38609ff0ed34a1a412c54df8240" style="width: 100.0%; height: 100.0%;">Lincoln Park Community Services (Addressing Social Issues)</div>`)[0];
                popup_51035c8efbbabbaeba60eab614072a35.setContent(html_39b8d38609ff0ed34a1a412c54df8240);
            
        

        marker_84092ee6514ec8e011fe6ac5d2509b6b.bindPopup(popup_51035c8efbbabbaeba60eab614072a35)
        ;

        
    
    
            var marker_987026a5d6d58a9d7076e20d16307cb2 = L.marker(
                [42.34444, -87.84312],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_41369169e3b4c55dde0847372479a311 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_987026a5d6d58a9d7076e20d16307cb2.setIcon(icon_41369169e3b4c55dde0847372479a311);
        
    
        var popup_2464240f668fb548a9f0cec772865f6e = L.popup({"maxWidth": "100%"});

        
            
                var html_7614d33b4262d6cc263b21f41978764a = $(`<div id="html_7614d33b4262d6cc263b21f41978764a" style="width: 100.0%; height: 100.0%;">Roberti Community House, Universidad Popular (Addressing Social Issues)</div>`)[0];
                popup_2464240f668fb548a9f0cec772865f6e.setContent(html_7614d33b4262d6cc263b21f41978764a);
            
        

        marker_987026a5d6d58a9d7076e20d16307cb2.bindPopup(popup_2464240f668fb548a9f0cec772865f6e)
        ;

        
    
    
            var marker_48c0003ad9f200267847798dc992ff35 = L.marker(
                [41.76406, -87.602442],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_62e870b91283c2186606d76f165e0a27 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_48c0003ad9f200267847798dc992ff35.setIcon(icon_62e870b91283c2186606d76f165e0a27);
        
    
        var popup_7ee1ed1910c3230eb8f6e218153d6acc = L.popup({"maxWidth": "100%"});

        
            
                var html_ae0e6833a976a984f0be421cecc9ab5b = $(`<div id="html_ae0e6833a976a984f0be421cecc9ab5b" style="width: 100.0%; height: 100.0%;">Gary Comer Youth Center (Addressing Social Issues)</div>`)[0];
                popup_7ee1ed1910c3230eb8f6e218153d6acc.setContent(html_ae0e6833a976a984f0be421cecc9ab5b);
            
        

        marker_48c0003ad9f200267847798dc992ff35.bindPopup(popup_7ee1ed1910c3230eb8f6e218153d6acc)
        ;

        
    
    
            var marker_c89d56ceb1482b9c3620d7a552817e8b = L.marker(
                [41.87556, -87.71649],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_17fb649359b2eec32df887c9ea08ad8e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_c89d56ceb1482b9c3620d7a552817e8b.setIcon(icon_17fb649359b2eec32df887c9ea08ad8e);
        
    
        var popup_63d7ac1bab1738c5774b8cf0edea34a4 = L.popup({"maxWidth": "100%"});

        
            
                var html_d872fd53b4a4fbfd2fff3614050c8483 = $(`<div id="html_d872fd53b4a4fbfd2fff3614050c8483" style="width: 100.0%; height: 100.0%;">Leif Ericson Elementary, Chicago Public Schools (Addressing Social Issues)</div>`)[0];
                popup_63d7ac1bab1738c5774b8cf0edea34a4.setContent(html_d872fd53b4a4fbfd2fff3614050c8483);
            
        

        marker_c89d56ceb1482b9c3620d7a552817e8b.bindPopup(popup_63d7ac1bab1738c5774b8cf0edea34a4)
        ;

        
    
    
            var marker_14c44cca7538171ad35e0c2fa8644462 = L.marker(
                [41.956985, -87.656555],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_a6eda21b6d0ca8923296e5910674ac36 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_14c44cca7538171ad35e0c2fa8644462.setIcon(icon_a6eda21b6d0ca8923296e5910674ac36);
        
    
        var popup_f7093587827335c82d3a91646cba402f = L.popup({"maxWidth": "100%"});

        
            
                var html_6a615cf78f909db631e1c9ad295bbaa7 = $(`<div id="html_6a615cf78f909db631e1c9ad295bbaa7" style="width: 100.0%; height: 100.0%;">The Evolved Network (Addressing Social Issues)</div>`)[0];
                popup_f7093587827335c82d3a91646cba402f.setContent(html_6a615cf78f909db631e1c9ad295bbaa7);
            
        

        marker_14c44cca7538171ad35e0c2fa8644462.bindPopup(popup_f7093587827335c82d3a91646cba402f)
        ;

        
    
    
            var marker_9a0abb70225342c179af971e369ed675 = L.marker(
                [41.923226, -87.654307],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_fc965dddcd32c1752dfabc5d0e832d64 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_9a0abb70225342c179af971e369ed675.setIcon(icon_fc965dddcd32c1752dfabc5d0e832d64);
        
    
        var popup_0348f44a39a45701bd988d8e1b2b693c = L.popup({"maxWidth": "100%"});

        
            
                var html_f8bc382c1b4435b6d56b8cbb60213285 = $(`<div id="html_f8bc382c1b4435b6d56b8cbb60213285" style="width: 100.0%; height: 100.0%;">Ministry Against the Death Penalty (MADP), AIDS Foundation of Chicago, Prison + Neighborhood Art and Education Project, Safer Foundation (Addressing Social Issues)</div>`)[0];
                popup_0348f44a39a45701bd988d8e1b2b693c.setContent(html_f8bc382c1b4435b6d56b8cbb60213285);
            
        

        marker_9a0abb70225342c179af971e369ed675.bindPopup(popup_0348f44a39a45701bd988d8e1b2b693c)
        ;

        
    
    
            var marker_acebb408aff35ef0461eebca6ac73881 = L.marker(
                [42.020717, -87.671438],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_c8d4444e9ea79ff57836898f189ea56c = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_acebb408aff35ef0461eebca6ac73881.setIcon(icon_c8d4444e9ea79ff57836898f189ea56c);
        
    
        var popup_3998b3505d0dc7ed7119de8e0be1130e = L.popup({"maxWidth": "100%"});

        
            
                var html_45cec23ccd3f296ec500f4968c1c729a = $(`<div id="html_45cec23ccd3f296ec500f4968c1c729a" style="width: 100.0%; height: 100.0%;">Roots For Life, GALE, Chicago Public Schools (Addressing Social Issues)</div>`)[0];
                popup_3998b3505d0dc7ed7119de8e0be1130e.setContent(html_45cec23ccd3f296ec500f4968c1c729a);
            
        

        marker_acebb408aff35ef0461eebca6ac73881.bindPopup(popup_3998b3505d0dc7ed7119de8e0be1130e)
        ;

        
    
    
            var marker_facbd33bdd02924395e8189039c3fcfb = L.marker(
                [42.02073, -87.67149],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_77c2de7ad0a03229ca463e7506bc66e9 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_facbd33bdd02924395e8189039c3fcfb.setIcon(icon_77c2de7ad0a03229ca463e7506bc66e9);
        
    
        var popup_210b661ad7b18d29208384b2a5b6d789 = L.popup({"maxWidth": "100%"});

        
            
                var html_044c19d4a0fbdcec3ca1c226defc10be = $(`<div id="html_044c19d4a0fbdcec3ca1c226defc10be" style="width: 100.0%; height: 100.0%;">GALE (Addressing Social Issues)</div>`)[0];
                popup_210b661ad7b18d29208384b2a5b6d789.setContent(html_044c19d4a0fbdcec3ca1c226defc10be);
            
        

        marker_facbd33bdd02924395e8189039c3fcfb.bindPopup(popup_210b661ad7b18d29208384b2a5b6d789)
        ;

        
    
    
            var marker_38e0e64f0480173ded0487a174aea89f = L.marker(
                [41.75151, -87.65349],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_635f91746755bd4ec972f2710ab866cf = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_38e0e64f0480173ded0487a174aea89f.setIcon(icon_635f91746755bd4ec972f2710ab866cf);
        
    
        var popup_5e045c3002d78893cac2921bc5965296 = L.popup({"maxWidth": "100%"});

        
            
                var html_3f12bc3344e0e94324ab471176b7bcd1 = $(`<div id="html_3f12bc3344e0e94324ab471176b7bcd1" style="width: 100.0%; height: 100.0%;">Stein Learning Gardens (Addressing Social Issues)</div>`)[0];
                popup_5e045c3002d78893cac2921bc5965296.setContent(html_3f12bc3344e0e94324ab471176b7bcd1);
            
        

        marker_38e0e64f0480173ded0487a174aea89f.bindPopup(popup_5e045c3002d78893cac2921bc5965296)
        ;

        
    
    
            var marker_d37af0d0c607297be926bde9b3c5625f = L.marker(
                [41.919522, -87.731169],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_04458407327d716d516e0bc1eabfc6b0 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_d37af0d0c607297be926bde9b3c5625f.setIcon(icon_04458407327d716d516e0bc1eabfc6b0);
        
    
        var popup_c7cd2f8bdaa7dc8495be8d2510b09fa9 = L.popup({"maxWidth": "100%"});

        
            
                var html_d820234a196eb074f62c4a86564e5426 = $(`<div id="html_d820234a196eb074f62c4a86564e5426" style="width: 100.0%; height: 100.0%;">NIXON, Chicago Public Schools, Girls In Power (Addressing Social Issues)</div>`)[0];
                popup_c7cd2f8bdaa7dc8495be8d2510b09fa9.setContent(html_d820234a196eb074f62c4a86564e5426);
            
        

        marker_d37af0d0c607297be926bde9b3c5625f.bindPopup(popup_c7cd2f8bdaa7dc8495be8d2510b09fa9)
        ;

        
    
    
            var marker_87d790a8dd96226bca0dcd20291725d3 = L.marker(
                [41.86295, -87.71418],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_4dbe605e6debbf72ab8f431b829f83f9 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_87d790a8dd96226bca0dcd20291725d3.setIcon(icon_4dbe605e6debbf72ab8f431b829f83f9);
        
    
        var popup_96e37c588183e96e2f0ef7abbe446c8f = L.popup({"maxWidth": "100%"});

        
            
                var html_6755d7ac293e7473a520a73385524fe4 = $(`<div id="html_6755d7ac293e7473a520a73385524fe4" style="width: 100.0%; height: 100.0%;">Lawndale Elementary Community Academy , Chicago Public Schools (Addressing Social Issues)</div>`)[0];
                popup_96e37c588183e96e2f0ef7abbe446c8f.setContent(html_6755d7ac293e7473a520a73385524fe4);
            
        

        marker_87d790a8dd96226bca0dcd20291725d3.bindPopup(popup_96e37c588183e96e2f0ef7abbe446c8f)
        ;

        
    
    
            var marker_cd62b62d67d2198c4ab67430292ecdc4 = L.marker(
                [41.92451, -87.65975],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_b255edf72d50730d78b9dd6ec6f0d8ba = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_cd62b62d67d2198c4ab67430292ecdc4.setIcon(icon_b255edf72d50730d78b9dd6ec6f0d8ba);
        
    
        var popup_918ef6e0223fa3a31b91646c0b9bc0b9 = L.popup({"maxWidth": "100%"});

        
            
                var html_7138334220f9c8649e0f87bf6978041d = $(`<div id="html_7138334220f9c8649e0f87bf6978041d" style="width: 100.0%; height: 100.0%;">Interfaith Community for Detained Immigrants (ICDI) Post-Detention, Compassionate Care Network, Little Sisters of the Poor, Care For Real, The Evolved Network (Addressing Social Issues)</div>`)[0];
                popup_918ef6e0223fa3a31b91646c0b9bc0b9.setContent(html_7138334220f9c8649e0f87bf6978041d);
            
        

        marker_cd62b62d67d2198c4ab67430292ecdc4.bindPopup(popup_918ef6e0223fa3a31b91646c0b9bc0b9)
        ;

        
    
    
            var marker_d8a59406d13deb267bb8aee51a8fffc0 = L.marker(
                [41.98712, -87.84592],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_79faa2560069c88ae7718f8dc06aff14 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_d8a59406d13deb267bb8aee51a8fffc0.setIcon(icon_79faa2560069c88ae7718f8dc06aff14);
        
    
        var popup_b026735730ce8137e75b071620e0ea96 = L.popup({"maxWidth": "100%"});

        
            
                var html_52bf920bfd11909ac12de74d3e9293cb = $(`<div id="html_52bf920bfd11909ac12de74d3e9293cb" style="width: 100.0%; height: 100.0%;">Kids Above All (Addressing Social Issues)</div>`)[0];
                popup_b026735730ce8137e75b071620e0ea96.setContent(html_52bf920bfd11909ac12de74d3e9293cb);
            
        

        marker_d8a59406d13deb267bb8aee51a8fffc0.bindPopup(popup_b026735730ce8137e75b071620e0ea96)
        ;

        
    
    
            var marker_21703951ef8384da459142b3cda2c852 = L.marker(
                [41.78042, -87.60518],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_c2c5797e9405b25a6bda2a83053d3841 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_21703951ef8384da459142b3cda2c852.setIcon(icon_c2c5797e9405b25a6bda2a83053d3841);
        
    
        var popup_54a24c1480b399ee7768bc5b97464a08 = L.popup({"maxWidth": "100%"});

        
            
                var html_3454a5bf78cade1f7b99243f5cc9fdb0 = $(`<div id="html_3454a5bf78cade1f7b99243f5cc9fdb0" style="width: 100.0%; height: 100.0%;">Interfaith Community for Detained Immigrants (ICDI) Post-Detention (Addressing Social Issues)</div>`)[0];
                popup_54a24c1480b399ee7768bc5b97464a08.setContent(html_3454a5bf78cade1f7b99243f5cc9fdb0);
            
        

        marker_21703951ef8384da459142b3cda2c852.bindPopup(popup_54a24c1480b399ee7768bc5b97464a08)
        ;

        
    
    
            var marker_30f3513be0f9e0a5d441d140e8713b83 = L.marker(
                [41.88189, -87.62488],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_b0c3800cc001c4d48054e17f6a2dee93 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_30f3513be0f9e0a5d441d140e8713b83.setIcon(icon_b0c3800cc001c4d48054e17f6a2dee93);
        
    
        var popup_16f400787167678a0c695df23574385f = L.popup({"maxWidth": "100%"});

        
            
                var html_8952964644c59c6efbd3dcdcc5eb5045 = $(`<div id="html_8952964644c59c6efbd3dcdcc5eb5045" style="width: 100.0%; height: 100.0%;">Envision Unlimited, KEEN Chicago (Addressing Social Issues)</div>`)[0];
                popup_16f400787167678a0c695df23574385f.setContent(html_8952964644c59c6efbd3dcdcc5eb5045);
            
        

        marker_30f3513be0f9e0a5d441d140e8713b83.bindPopup(popup_16f400787167678a0c695df23574385f)
        ;

        
    
    
            var marker_bc2b924762b0a64b12ca75067fc48a0b = L.marker(
                [41.888, -87.66693],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_f7c4db7b414a8711a05e0aca80f6108d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_bc2b924762b0a64b12ca75067fc48a0b.setIcon(icon_f7c4db7b414a8711a05e0aca80f6108d);
        
    
        var popup_d3294ce7148e841f89d02074677a2523 = L.popup({"maxWidth": "100%"});

        
            
                var html_d3bee74ac526958d8b354ca15388aab5 = $(`<div id="html_d3bee74ac526958d8b354ca15388aab5" style="width: 100.0%; height: 100.0%;">Little Brothers Friends of the Elderly, Park Place Waukegan, Jugan Terrace, Little Sisters of the Poor (Addressing Social Issues)</div>`)[0];
                popup_d3294ce7148e841f89d02074677a2523.setContent(html_d3bee74ac526958d8b354ca15388aab5);
            
        

        marker_bc2b924762b0a64b12ca75067fc48a0b.bindPopup(popup_d3294ce7148e841f89d02074677a2523)
        ;

        
    
    
            var marker_f9a2b5c7db31194e43a8b6f719bc4efa = L.marker(
                [41.931194, -87.757779],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_93249b0d17d7db1cdc15e6b2349d5ec6 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_f9a2b5c7db31194e43a8b6f719bc4efa.setIcon(icon_93249b0d17d7db1cdc15e6b2349d5ec6);
        
    
        var popup_4fb16b60f58652fd8745fe299bf2ad22 = L.popup({"maxWidth": "100%"});

        
            
                var html_12020fd1c5d21c94a0264899f853d116 = $(`<div id="html_12020fd1c5d21c94a0264899f853d116" style="width: 100.0%; height: 100.0%;">RRF Foundation for Aging, Northwest Side Housing Center (Addressing Social Issues)</div>`)[0];
                popup_4fb16b60f58652fd8745fe299bf2ad22.setContent(html_12020fd1c5d21c94a0264899f853d116);
            
        

        marker_f9a2b5c7db31194e43a8b6f719bc4efa.bindPopup(popup_4fb16b60f58652fd8745fe299bf2ad22)
        ;

        
    
    
            var marker_546bfe9b163b88f969435e131b149db3 = L.marker(
                [41.86298, -87.62393],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_909c0563a601764a369e4d47b44ba083 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_546bfe9b163b88f969435e131b149db3.setIcon(icon_909c0563a601764a369e4d47b44ba083);
        
    
        var popup_6717d692241b89b7de8e4576ae73c8a4 = L.popup({"maxWidth": "100%"});

        
            
                var html_eed3d9db7441de2d3654f7d24a240ecf = $(`<div id="html_eed3d9db7441de2d3654f7d24a240ecf" style="width: 100.0%; height: 100.0%;">Emmett Till Interpretive Center, Kenwood Oakland Community Organization, Black Researchers Collective (Addressing Social Issues)</div>`)[0];
                popup_6717d692241b89b7de8e4576ae73c8a4.setContent(html_eed3d9db7441de2d3654f7d24a240ecf);
            
        

        marker_546bfe9b163b88f969435e131b149db3.bindPopup(popup_6717d692241b89b7de8e4576ae73c8a4)
        ;

        
    
    
            var marker_22d4eb78eb1f87098bb88666a03f4d87 = L.marker(
                [41.86298, -87.62393],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_b86b86d76d4955bae7ef58ef50262c89 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_22d4eb78eb1f87098bb88666a03f4d87.setIcon(icon_b86b86d76d4955bae7ef58ef50262c89);
        
    
        var popup_aaa3b5daadb83fdc08f40ab02f9a4d6c = L.popup({"maxWidth": "100%"});

        
            
                var html_40fb5bc528d84f82c6eab671c31ef9b8 = $(`<div id="html_40fb5bc528d84f82c6eab671c31ef9b8" style="width: 100.0%; height: 100.0%;">Emmett Till Interpretive Center, Black Researchers Collective (Addressing Social Issues)</div>`)[0];
                popup_aaa3b5daadb83fdc08f40ab02f9a4d6c.setContent(html_40fb5bc528d84f82c6eab671c31ef9b8);
            
        

        marker_22d4eb78eb1f87098bb88666a03f4d87.bindPopup(popup_aaa3b5daadb83fdc08f40ab02f9a4d6c)
        ;

        
    
    
            var marker_5e18599834a980e4d3fcd778c8b654b4 = L.marker(
                [41.922592, -87.654359],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_683fac08b14fac6acc3b3ea70bb6cb05 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_5e18599834a980e4d3fcd778c8b654b4.setIcon(icon_683fac08b14fac6acc3b3ea70bb6cb05);
        
    
        var popup_e73a0e175b8059dd4a0864d8e7013d2e = L.popup({"maxWidth": "100%"});

        
            
                var html_44d83e75c2a868de90d36e431384ec83 = $(`<div id="html_44d83e75c2a868de90d36e431384ec83" style="width: 100.0%; height: 100.0%;">Cook County Sheriff's Office, Illinois Department of Corrections (Addressing Social Issues)</div>`)[0];
                popup_e73a0e175b8059dd4a0864d8e7013d2e.setContent(html_44d83e75c2a868de90d36e431384ec83);
            
        

        marker_5e18599834a980e4d3fcd778c8b654b4.bindPopup(popup_e73a0e175b8059dd4a0864d8e7013d2e)
        ;

        
    
    
            var marker_925fae59f514b91f2a30053dec8bc719 = L.marker(
                [41.92265, -87.65364],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_4af0240555a705f2bdbf2416d3e1f89b = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_925fae59f514b91f2a30053dec8bc719.setIcon(icon_4af0240555a705f2bdbf2416d3e1f89b);
        
    
        var popup_a31363f035cd5a70bf091d32448639ce = L.popup({"maxWidth": "100%"});

        
            
                var html_4adfaf7e802fa2ace7df84987c6df3b2 = $(`<div id="html_4adfaf7e802fa2ace7df84987c6df3b2" style="width: 100.0%; height: 100.0%;">Lawndale Elementary Community Academy , St. Pius V School, GALE (Addressing Social Issues)</div>`)[0];
                popup_a31363f035cd5a70bf091d32448639ce.setContent(html_4adfaf7e802fa2ace7df84987c6df3b2);
            
        

        marker_925fae59f514b91f2a30053dec8bc719.bindPopup(popup_a31363f035cd5a70bf091d32448639ce)
        ;

        
    
    
            var marker_3eab3536d86feab101263889a1ba949c = L.marker(
                [41.863256, -87.713373],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_fcee4a90ef2c381ba10ed93282e5b9bd = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_3eab3536d86feab101263889a1ba949c.setIcon(icon_fcee4a90ef2c381ba10ed93282e5b9bd);
        
    
        var popup_84ffb592cd6ebad29ac89de1ef2b4d83 = L.popup({"maxWidth": "100%"});

        
            
                var html_42527c2964c64cc4705a02f46ba692a5 = $(`<div id="html_42527c2964c64cc4705a02f46ba692a5" style="width: 100.0%; height: 100.0%;">Lawndale Elementary Community Academy , Big Green Chicago, Pitch-In Wood Family Foundation, Chicago Public Schools (Addressing Social Issues)</div>`)[0];
                popup_84ffb592cd6ebad29ac89de1ef2b4d83.setContent(html_42527c2964c64cc4705a02f46ba692a5);
            
        

        marker_3eab3536d86feab101263889a1ba949c.bindPopup(popup_84ffb592cd6ebad29ac89de1ef2b4d83)
        ;

        
    
    
            var marker_f7764075b42fc67a94c699be26aa4b7b = L.marker(
                [41.86295, -87.71418],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_ce5348ac2cf1b1d19b9a1d617b1d1b0c = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_f7764075b42fc67a94c699be26aa4b7b.setIcon(icon_ce5348ac2cf1b1d19b9a1d617b1d1b0c);
        
    
        var popup_6faa1818d808eb635f950b72f8c90a84 = L.popup({"maxWidth": "100%"});

        
            
                var html_03409d2757f68622b2e62b3006674e9d = $(`<div id="html_03409d2757f68622b2e62b3006674e9d" style="width: 100.0%; height: 100.0%;">Lawndale Elementary Community Academy , Chicago Public Schools (Addressing Social Issues)</div>`)[0];
                popup_6faa1818d808eb635f950b72f8c90a84.setContent(html_03409d2757f68622b2e62b3006674e9d);
            
        

        marker_f7764075b42fc67a94c699be26aa4b7b.bindPopup(popup_6faa1818d808eb635f950b72f8c90a84)
        ;

        
    
    
            var marker_5cd777c4b000c87172bf4e0e7fb91992 = L.marker(
                [41.922595, -87.654355],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_c40f9e6ad05bf390192f2994794a8742 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_5cd777c4b000c87172bf4e0e7fb91992.setIcon(icon_c40f9e6ad05bf390192f2994794a8742);
        
    
        var popup_243b03c559b366a8943dfa7fffef9352 = L.popup({"maxWidth": "100%"});

        
            
                var html_43f85394b70278e2b40674b7754fa939 = $(`<div id="html_43f85394b70278e2b40674b7754fa939" style="width: 100.0%; height: 100.0%;">Lawndale Elementary Community Academy , Chicago Public Schools (Addressing Social Issues)</div>`)[0];
                popup_243b03c559b366a8943dfa7fffef9352.setContent(html_43f85394b70278e2b40674b7754fa939);
            
        

        marker_5cd777c4b000c87172bf4e0e7fb91992.bindPopup(popup_243b03c559b366a8943dfa7fffef9352)
        ;

        
    
    
            var marker_471d63beef206d7a31f9937afb34ff41 = L.marker(
                [41.925654, -87.655072],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_fdeaaacafdb05e6e7477635f14d09595 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_471d63beef206d7a31f9937afb34ff41.setIcon(icon_fdeaaacafdb05e6e7477635f14d09595);
        
    
        var popup_b285e4f74da52495e1f6c43254441838 = L.popup({"maxWidth": "100%"});

        
            
                var html_faa2e958ccc58b130eea0c4404208504 = $(`<div id="html_faa2e958ccc58b130eea0c4404208504" style="width: 100.0%; height: 100.0%;">Chicago Public Schools (Addressing Social Issues)</div>`)[0];
                popup_b285e4f74da52495e1f6c43254441838.setContent(html_faa2e958ccc58b130eea0c4404208504);
            
        

        marker_471d63beef206d7a31f9937afb34ff41.bindPopup(popup_b285e4f74da52495e1f6c43254441838)
        ;

        
    
    
            var marker_2ff4fae96c3e8b9a2859f48891b44e79 = L.marker(
                [41.93678, -87.6509],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_34d89d164d4cfaf5001d3467a6428a86 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_2ff4fae96c3e8b9a2859f48891b44e79.setIcon(icon_34d89d164d4cfaf5001d3467a6428a86);
        
    
        var popup_cc3c6ef1605a6adc6a1d62f95ee677b5 = L.popup({"maxWidth": "100%"});

        
            
                var html_1d5889535ed41cdedb410c311aba36fb = $(`<div id="html_1d5889535ed41cdedb410c311aba36fb" style="width: 100.0%; height: 100.0%;">Advocate Aurora Health -  Advocate Illinois Masonic Medical Center (AIMMC) and Advocate Good Samaritan Hospital (AGSH) (Addressing Social Issues)</div>`)[0];
                popup_cc3c6ef1605a6adc6a1d62f95ee677b5.setContent(html_1d5889535ed41cdedb410c311aba36fb);
            
        

        marker_2ff4fae96c3e8b9a2859f48891b44e79.bindPopup(popup_cc3c6ef1605a6adc6a1d62f95ee677b5)
        ;

        
    
    
            var marker_9b1d179841dbc4f5ba62c012e96eeaff = L.marker(
                [41.88322, -87.63249],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_c8dc8c3ab06c4f846bf4ff378388e7a8 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_9b1d179841dbc4f5ba62c012e96eeaff.setIcon(icon_c8dc8c3ab06c4f846bf4ff378388e7a8);
        
    
        var popup_da1f08d1449ef00311e1945544ef5942 = L.popup({"maxWidth": "100%"});

        
            
                var html_7f5d73af79488b54f45230865abf769b = $(`<div id="html_7f5d73af79488b54f45230865abf769b" style="width: 100.0%; height: 100.0%;">Chicago Lawyers Committee for Civil Rights (Addressing Social Issues)</div>`)[0];
                popup_da1f08d1449ef00311e1945544ef5942.setContent(html_7f5d73af79488b54f45230865abf769b);
            
        

        marker_9b1d179841dbc4f5ba62c012e96eeaff.bindPopup(popup_da1f08d1449ef00311e1945544ef5942)
        ;

        
    
    
            var marker_77f6fa34bec3335c6b18050cf24e3c40 = L.marker(
                [41.893164, -87.661408],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_66bd57d39e097a666b0fbc3f33456bbf = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_77f6fa34bec3335c6b18050cf24e3c40.setIcon(icon_66bd57d39e097a666b0fbc3f33456bbf);
        
    
        var popup_5ee18ff446c83b8dea39eae5309ecdf0 = L.popup({"maxWidth": "100%"});

        
            
                var html_1f7669923087af6ebdeefd8d54363f02 = $(`<div id="html_1f7669923087af6ebdeefd8d54363f02" style="width: 100.0%; height: 100.0%;">Erie Neighborhood House (Addressing Social Issues)</div>`)[0];
                popup_5ee18ff446c83b8dea39eae5309ecdf0.setContent(html_1f7669923087af6ebdeefd8d54363f02);
            
        

        marker_77f6fa34bec3335c6b18050cf24e3c40.bindPopup(popup_5ee18ff446c83b8dea39eae5309ecdf0)
        ;

        
    
    
            var marker_5645775b4529bd97f0ea640dc93947df = L.marker(
                [41.8008, -87.65654],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_78fea5527f1442238d6f64549d2fd6eb = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_5645775b4529bd97f0ea640dc93947df.setIcon(icon_78fea5527f1442238d6f64549d2fd6eb);
        
    
        var popup_edf493445974a6684718fd711256fb95 = L.popup({"maxWidth": "100%"});

        
            
                var html_09bc0617d5d785fd3223cfeb12b274c4 = $(`<div id="html_09bc0617d5d785fd3223cfeb12b274c4" style="width: 100.0%; height: 100.0%;">Precious Blood Ministry (Addressing Social Issues)</div>`)[0];
                popup_edf493445974a6684718fd711256fb95.setContent(html_09bc0617d5d785fd3223cfeb12b274c4);
            
        

        marker_5645775b4529bd97f0ea640dc93947df.bindPopup(popup_edf493445974a6684718fd711256fb95)
        ;

        
    
    
            var marker_2ac1277e9884eb7cb7168efb264135c3 = L.marker(
                [41.865068, -87.625282],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_a9375fb24325094524f3e5388db466de = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_2ac1277e9884eb7cb7168efb264135c3.setIcon(icon_a9375fb24325094524f3e5388db466de);
        
    
        var popup_6522f9c7bde6f3c7622c96832a73d585 = L.popup({"maxWidth": "100%"});

        
            
                var html_bafef5778f49c75cbfec862d46b5935d = $(`<div id="html_bafef5778f49c75cbfec862d46b5935d" style="width: 100.0%; height: 100.0%;">Chicago Alliance Against Racist and Political Repression (Addressing Social Issues)</div>`)[0];
                popup_6522f9c7bde6f3c7622c96832a73d585.setContent(html_bafef5778f49c75cbfec862d46b5935d);
            
        

        marker_2ac1277e9884eb7cb7168efb264135c3.bindPopup(popup_6522f9c7bde6f3c7622c96832a73d585)
        ;

        
    
    
            var marker_a3fcb5fbd925b708af9ba198fa265a03 = L.marker(
                [41.92214, -87.65462],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_b2f4385d82c7b6fad71d154975a4c210 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_a3fcb5fbd925b708af9ba198fa265a03.setIcon(icon_b2f4385d82c7b6fad71d154975a4c210);
        
    
        var popup_0ee412101c0ea7d00647c038f9e65abc = L.popup({"maxWidth": "100%"});

        
            
                var html_fbf9c1e94dc36e3f5e264d8ea5d0b0b9 = $(`<div id="html_fbf9c1e94dc36e3f5e264d8ea5d0b0b9" style="width: 100.0%; height: 100.0%;">DePaul Cities Project (Addressing Social Issues)</div>`)[0];
                popup_0ee412101c0ea7d00647c038f9e65abc.setContent(html_fbf9c1e94dc36e3f5e264d8ea5d0b0b9);
            
        

        marker_a3fcb5fbd925b708af9ba198fa265a03.bindPopup(popup_0ee412101c0ea7d00647c038f9e65abc)
        ;

        
    
    
            var marker_10c7cce97c8ccf420d0c132a20ce440a = L.marker(
                [41.87556, -87.71649],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_60169dfa442ed467862060dd0a68558e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_10c7cce97c8ccf420d0c132a20ce440a.setIcon(icon_60169dfa442ed467862060dd0a68558e);
        
    
        var popup_96e08bc6de339b55c13c93cabacb37dd = L.popup({"maxWidth": "100%"});

        
            
                var html_318ae9aa69f1f9d9c14876163489a1e0 = $(`<div id="html_318ae9aa69f1f9d9c14876163489a1e0" style="width: 100.0%; height: 100.0%;">Leif Ericson Elementary, Chicago Public Schools (Addressing Social Issues)</div>`)[0];
                popup_96e08bc6de339b55c13c93cabacb37dd.setContent(html_318ae9aa69f1f9d9c14876163489a1e0);
            
        

        marker_10c7cce97c8ccf420d0c132a20ce440a.bindPopup(popup_96e08bc6de339b55c13c93cabacb37dd)
        ;

        
    
    
            var marker_b8a9bd72a8cbe8051370fcbdfe46e15f = L.marker(
                [41.953995, -87.73588],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_bf3e3ce58b4b363bdb1446ef57f936fe = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_b8a9bd72a8cbe8051370fcbdfe46e15f.setIcon(icon_bf3e3ce58b4b363bdb1446ef57f936fe);
        
    
        var popup_f66d3831533538ab601da70ec10be05e = L.popup({"maxWidth": "100%"});

        
            
                var html_cce4e402b0ff8cb0eb4401e6f1f98e72 = $(`<div id="html_cce4e402b0ff8cb0eb4401e6f1f98e72" style="width: 100.0%; height: 100.0%;">Safe Families PLUS (Addressing Social Issues)</div>`)[0];
                popup_f66d3831533538ab601da70ec10be05e.setContent(html_cce4e402b0ff8cb0eb4401e6f1f98e72);
            
        

        marker_b8a9bd72a8cbe8051370fcbdfe46e15f.bindPopup(popup_f66d3831533538ab601da70ec10be05e)
        ;

        
    
    
            var marker_0fd9908d48ddc9c838d8a4ec28821a8e = L.marker(
                [41.872627, -87.627132],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_e3cc1d9ce698f3f50427f0b743148634 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_0fd9908d48ddc9c838d8a4ec28821a8e.setIcon(icon_e3cc1d9ce698f3f50427f0b743148634);
        
    
        var popup_6461956d8894d925818664abb0a9c10e = L.popup({"maxWidth": "100%"});

        
            
                var html_872ad662d20573a6f94bc30b482909f7 = $(`<div id="html_872ad662d20573a6f94bc30b482909f7" style="width: 100.0%; height: 100.0%;">Project NIA (Addressing Social Issues)</div>`)[0];
                popup_6461956d8894d925818664abb0a9c10e.setContent(html_872ad662d20573a6f94bc30b482909f7);
            
        

        marker_0fd9908d48ddc9c838d8a4ec28821a8e.bindPopup(popup_6461956d8894d925818664abb0a9c10e)
        ;

        
    
    
            var marker_3c65e6b9e5421d2bcc81472277c07b2d = L.marker(
                [41.885165, -87.631726],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_71d0f6a02253de91e65392625e7eb7f3 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_3c65e6b9e5421d2bcc81472277c07b2d.setIcon(icon_71d0f6a02253de91e65392625e7eb7f3);
        
    
        var popup_54d32179cf52af3b8447e2d6e16a0b14 = L.popup({"maxWidth": "100%"});

        
            
                var html_64eb1e58a12b0d5ea44d0c5df273dcbe = $(`<div id="html_64eb1e58a12b0d5ea44d0c5df273dcbe" style="width: 100.0%; height: 100.0%;">Illinois Department of Veterans Affairs (Addressing Social Issues)</div>`)[0];
                popup_54d32179cf52af3b8447e2d6e16a0b14.setContent(html_64eb1e58a12b0d5ea44d0c5df273dcbe);
            
        

        marker_3c65e6b9e5421d2bcc81472277c07b2d.bindPopup(popup_54d32179cf52af3b8447e2d6e16a0b14)
        ;

        
    
    
            var marker_7eb3e916af30fea367083717183c4dda = L.marker(
                [41.840449, -87.826807],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_a1440a1abe837a25f5c3281ca89ca6d7 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_7eb3e916af30fea367083717183c4dda.setIcon(icon_a1440a1abe837a25f5c3281ca89ca6d7);
        
    
        var popup_953227d61ff5bcbb61765a1d377a40f0 = L.popup({"maxWidth": "100%"});

        
            
                var html_f55f3901bd2bc69b9185989df12b7b7f = $(`<div id="html_f55f3901bd2bc69b9185989df12b7b7f" style="width: 100.0%; height: 100.0%;">Caledonia Senior Living & Memory Care (Addressing Social Issues)</div>`)[0];
                popup_953227d61ff5bcbb61765a1d377a40f0.setContent(html_f55f3901bd2bc69b9185989df12b7b7f);
            
        

        marker_7eb3e916af30fea367083717183c4dda.bindPopup(popup_953227d61ff5bcbb61765a1d377a40f0)
        ;

        
    
    
            var marker_3120d0164d8d03f1c3b90c0c38cff5df = L.marker(
                [41.90082, -87.7505],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_0907d274f15a1fdbfa45fadbca64a77a = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_3120d0164d8d03f1c3b90c0c38cff5df.setIcon(icon_0907d274f15a1fdbfa45fadbca64a77a);
        
    
        var popup_a81077769f7f01dd221024a6c36e7b17 = L.popup({"maxWidth": "100%"});

        
            
                var html_25b5f9191325ca8145b716e4c038b44e = $(`<div id="html_25b5f9191325ca8145b716e4c038b44e" style="width: 100.0%; height: 100.0%;">Bethel New Life, Stone Temple Baptist Church (Addressing Social Issues)</div>`)[0];
                popup_a81077769f7f01dd221024a6c36e7b17.setContent(html_25b5f9191325ca8145b716e4c038b44e);
            
        

        marker_3120d0164d8d03f1c3b90c0c38cff5df.bindPopup(popup_a81077769f7f01dd221024a6c36e7b17)
        ;

        
    
    
            var marker_def8605015d3edbb4eef97894cc9b92b = L.marker(
                [41.919585, -87.731175],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_407a12d26de8bd1505b1a0b5df1790f5 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_def8605015d3edbb4eef97894cc9b92b.setIcon(icon_407a12d26de8bd1505b1a0b5df1790f5);
        
    
        var popup_987904a6184039735f490c060d15efab = L.popup({"maxWidth": "100%"});

        
            
                var html_1a623cf9ed3398fe3865fe166c2b0b32 = $(`<div id="html_1a623cf9ed3398fe3865fe166c2b0b32" style="width: 100.0%; height: 100.0%;">William P. Nixon Elementary, Chicago Public Schools (Addressing Social Issues)</div>`)[0];
                popup_987904a6184039735f490c060d15efab.setContent(html_1a623cf9ed3398fe3865fe166c2b0b32);
            
        

        marker_def8605015d3edbb4eef97894cc9b92b.bindPopup(popup_987904a6184039735f490c060d15efab)
        ;

        
    
    
            var marker_d0cbc292a3679754f5ee6f95bd9ac2ae = L.marker(
                [41.890095, -87.670302],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_cf2d4d17a3670a7a5c5a174d6390a71a = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_d0cbc292a3679754f5ee6f95bd9ac2ae.setIcon(icon_cf2d4d17a3670a7a5c5a174d6390a71a);
        
    
        var popup_38e2861e90cdf520fed37f3f2d8b9f5e = L.popup({"maxWidth": "100%"});

        
            
                var html_6d4a8db67a8cc4fc5bde7db796bdd86d = $(`<div id="html_6d4a8db67a8cc4fc5bde7db796bdd86d" style="width: 100.0%; height: 100.0%;">Nourishing Hope (Addressing Social Issues)</div>`)[0];
                popup_38e2861e90cdf520fed37f3f2d8b9f5e.setContent(html_6d4a8db67a8cc4fc5bde7db796bdd86d);
            
        

        marker_d0cbc292a3679754f5ee6f95bd9ac2ae.bindPopup(popup_38e2861e90cdf520fed37f3f2d8b9f5e)
        ;

        
    
    
            var marker_40ae71cb265fd4c57f875b9c35627f9c = L.marker(
                [41.93339, -87.730855],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_e8c6efb2f8928b2e8826fdcbcb5b658a = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_40ae71cb265fd4c57f875b9c35627f9c.setIcon(icon_e8c6efb2f8928b2e8826fdcbcb5b658a);
        
    
        var popup_dc5b04bf3b7e742f2d692bd3328809af = L.popup({"maxWidth": "100%"});

        
            
                var html_2576ecec9ffef8d090cf380ca5cdd4c5 = $(`<div id="html_2576ecec9ffef8d090cf380ca5cdd4c5" style="width: 100.0%; height: 100.0%;">Cradles to Crayons (Addressing Social Issues)</div>`)[0];
                popup_dc5b04bf3b7e742f2d692bd3328809af.setContent(html_2576ecec9ffef8d090cf380ca5cdd4c5);
            
        

        marker_40ae71cb265fd4c57f875b9c35627f9c.bindPopup(popup_dc5b04bf3b7e742f2d692bd3328809af)
        ;

        
    
    
            var marker_da0ce1fbea7103de3c33d7f4ad5d95a5 = L.marker(
                [41.91827, -87.699001],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_9c7e8f9933143c535a200119090a90e6 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_da0ce1fbea7103de3c33d7f4ad5d95a5.setIcon(icon_9c7e8f9933143c535a200119090a90e6);
        
    
        var popup_eaca9da236901f0f03a73510b054690a = L.popup({"maxWidth": "100%"});

        
            
                var html_11029af1d21f0255354d8928dac758e3 = $(`<div id="html_11029af1d21f0255354d8928dac758e3" style="width: 100.0%; height: 100.0%;">La Casa Norte, Care for Friends (Addressing Social Issues)</div>`)[0];
                popup_eaca9da236901f0f03a73510b054690a.setContent(html_11029af1d21f0255354d8928dac758e3);
            
        

        marker_da0ce1fbea7103de3c33d7f4ad5d95a5.bindPopup(popup_eaca9da236901f0f03a73510b054690a)
        ;

        
    
    
            var marker_0d02816ae12006291634fbba6bd0823a = L.marker(
                [42.34918, -87.835955],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_49834aaf7781f315e7a8ec756f7c1728 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_0d02816ae12006291634fbba6bd0823a.setIcon(icon_49834aaf7781f315e7a8ec756f7c1728);
        
    
        var popup_5e0fa914c48f77e44d15cf3c4982a3ff = L.popup({"maxWidth": "100%"});

        
            
                var html_23c9ca0f7e89c0f13f67d79160429f89 = $(`<div id="html_23c9ca0f7e89c0f13f67d79160429f89" style="width: 100.0%; height: 100.0%;">Living Works After School Program, Free Lunch Academy, Project Exploration, National Marrow Donor Program (Addressing Social Issues)</div>`)[0];
                popup_5e0fa914c48f77e44d15cf3c4982a3ff.setContent(html_23c9ca0f7e89c0f13f67d79160429f89);
            
        

        marker_0d02816ae12006291634fbba6bd0823a.bindPopup(popup_5e0fa914c48f77e44d15cf3c4982a3ff)
        ;

        
    
    
            var marker_cc117f94530827c66c6d581c44776b51 = L.marker(
                [41.88291, -87.62666],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_91671ac26d931519436a90755c96ac88 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_cc117f94530827c66c6d581c44776b51.setIcon(icon_91671ac26d931519436a90755c96ac88);
        
    
        var popup_f64e59e5b886eb96095c3f27e8d07f00 = L.popup({"maxWidth": "100%"});

        
            
                var html_d5a6759c4d8144bee227dbc1373bb73c = $(`<div id="html_d5a6759c4d8144bee227dbc1373bb73c" style="width: 100.0%; height: 100.0%;">NoStigmas (Addressing Social Issues)</div>`)[0];
                popup_f64e59e5b886eb96095c3f27e8d07f00.setContent(html_d5a6759c4d8144bee227dbc1373bb73c);
            
        

        marker_cc117f94530827c66c6d581c44776b51.bindPopup(popup_f64e59e5b886eb96095c3f27e8d07f00)
        ;

        
    
    
            var marker_63d817ae59c4b41d7cc6bd792083602a = L.marker(
                [41.876985, -87.685001],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_860205be2498b7c23486378567f90f87 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_63d817ae59c4b41d7cc6bd792083602a.setIcon(icon_860205be2498b7c23486378567f90f87);
        
    
        var popup_a5cd7903fc5ba214ee22e3fe4d2203b7 = L.popup({"maxWidth": "100%"});

        
            
                var html_3da0bcab6ac8a0034e71b9778b29daaf = $(`<div id="html_3da0bcab6ac8a0034e71b9778b29daaf" style="width: 100.0%; height: 100.0%;">The Community Builders (Addressing Social Issues)</div>`)[0];
                popup_a5cd7903fc5ba214ee22e3fe4d2203b7.setContent(html_3da0bcab6ac8a0034e71b9778b29daaf);
            
        

        marker_63d817ae59c4b41d7cc6bd792083602a.bindPopup(popup_a5cd7903fc5ba214ee22e3fe4d2203b7)
        ;

        
    
    
            var marker_7d31e54f544c584327c26e8463467354 = L.marker(
                [41.818265, -87.726825],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_60f0ffa2c003f5a3e04e5a12eb34ce2b = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_7d31e54f544c584327c26e8463467354.setIcon(icon_60f0ffa2c003f5a3e04e5a12eb34ce2b);
        
    
        var popup_f74123d10a5ff2e78b2969d86e34124c = L.popup({"maxWidth": "100%"});

        
            
                var html_cde198874b98d333d30ed31873475d59 = $(`<div id="html_cde198874b98d333d30ed31873475d59" style="width: 100.0%; height: 100.0%;">Greater Chicago Food Depository (Addressing Social Issues)</div>`)[0];
                popup_f74123d10a5ff2e78b2969d86e34124c.setContent(html_cde198874b98d333d30ed31873475d59);
            
        

        marker_7d31e54f544c584327c26e8463467354.bindPopup(popup_f74123d10a5ff2e78b2969d86e34124c)
        ;

        
    
    
            var marker_803c0a583609e0c70e0ca59c2432b989 = L.marker(
                [41.92393, -87.653186],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_bd536ae4e8a4f359396a23a8aea50591 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_803c0a583609e0c70e0ca59c2432b989.setIcon(icon_bd536ae4e8a4f359396a23a8aea50591);
        
    
        var popup_367a0ec960f7abcf3df66a7ca123cf95 = L.popup({"maxWidth": "100%"});

        
            
                var html_5464d593ad8fe7e8fb669ff4fa8f2c06 = $(`<div id="html_5464d593ad8fe7e8fb669ff4fa8f2c06" style="width: 100.0%; height: 100.0%;">Marillac St. Vincent Family Services (Addressing Social Issues)</div>`)[0];
                popup_367a0ec960f7abcf3df66a7ca123cf95.setContent(html_5464d593ad8fe7e8fb669ff4fa8f2c06);
            
        

        marker_803c0a583609e0c70e0ca59c2432b989.bindPopup(popup_367a0ec960f7abcf3df66a7ca123cf95)
        ;

        
    
    
            var marker_c8ea1140deb4fa071d5aa2266d5e0203 = L.marker(
                [41.79935, -87.58874],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_869f29a02fc2f4fba6dc9a7e7d9148f5 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_c8ea1140deb4fa071d5aa2266d5e0203.setIcon(icon_869f29a02fc2f4fba6dc9a7e7d9148f5);
        
    
        var popup_8d68489a2e8518e9b663b68ecd92b19b = L.popup({"maxWidth": "100%"});

        
            
                var html_df1ae2d42d2f40f7bfca4fa6285ff4f8 = $(`<div id="html_df1ae2d42d2f40f7bfca4fa6285ff4f8" style="width: 100.0%; height: 100.0%;">The Safe Haven Network (Addressing Social Issues)</div>`)[0];
                popup_8d68489a2e8518e9b663b68ecd92b19b.setContent(html_df1ae2d42d2f40f7bfca4fa6285ff4f8);
            
        

        marker_c8ea1140deb4fa071d5aa2266d5e0203.bindPopup(popup_8d68489a2e8518e9b663b68ecd92b19b)
        ;

        
    
    
            var marker_7abad35ab381fe90adf05683608692c6 = L.marker(
                [41.72783, -87.55185],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_fa9fba291bde378613e4f194cb36a9fc = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_7abad35ab381fe90adf05683608692c6.setIcon(icon_fa9fba291bde378613e4f194cb36a9fc);
        
    
        var popup_244ac5a70dfae7b31d7575042d888063 = L.popup({"maxWidth": "100%"});

        
            
                var html_e43de72b07b6635b8bc0de06a3994e5b = $(`<div id="html_e43de72b07b6635b8bc0de06a3994e5b" style="width: 100.0%; height: 100.0%;">Alliance of the Southeast (Addressing Social Issues)</div>`)[0];
                popup_244ac5a70dfae7b31d7575042d888063.setContent(html_e43de72b07b6635b8bc0de06a3994e5b);
            
        

        marker_7abad35ab381fe90adf05683608692c6.bindPopup(popup_244ac5a70dfae7b31d7575042d888063)
        ;

        
    
    
            var marker_302321ffeeca8339748d29130055759e = L.marker(
                [41.76532, -87.65837],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_37196ffc5a529c2352f88146c2949de6 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_302321ffeeca8339748d29130055759e.setIcon(icon_37196ffc5a529c2352f88146c2949de6);
        
    
        var popup_c4f6d42f088369b442b1f56e26bb0480 = L.popup({"maxWidth": "100%"});

        
            
                var html_78e51455b6920eeb310904c311569ea0 = $(`<div id="html_78e51455b6920eeb310904c311569ea0" style="width: 100.0%; height: 100.0%;">COOK, Scott Joplin Elementary, St. Sabina, WENTWORTH (Addressing Social Issues)</div>`)[0];
                popup_c4f6d42f088369b442b1f56e26bb0480.setContent(html_78e51455b6920eeb310904c311569ea0);
            
        

        marker_302321ffeeca8339748d29130055759e.bindPopup(popup_c4f6d42f088369b442b1f56e26bb0480)
        ;

        
    
    
            var marker_aea16c55f3d0b84fb7f49bf1807530bf = L.marker(
                [41.75151, -87.65349],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_bb74e1fb63d93ac7611f00147d089abe = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_aea16c55f3d0b84fb7f49bf1807530bf.setIcon(icon_bb74e1fb63d93ac7611f00147d089abe);
        
    
        var popup_886f6e412ee82e4d3aa0c62815ffcb8b = L.popup({"maxWidth": "100%"});

        
            
                var html_de4414445f106d2bf88f6d171bae78ad = $(`<div id="html_de4414445f106d2bf88f6d171bae78ad" style="width: 100.0%; height: 100.0%;">St. Sabina, Archdiocese of Chicago (Addressing Social Issues)</div>`)[0];
                popup_886f6e412ee82e4d3aa0c62815ffcb8b.setContent(html_de4414445f106d2bf88f6d171bae78ad);
            
        

        marker_aea16c55f3d0b84fb7f49bf1807530bf.bindPopup(popup_886f6e412ee82e4d3aa0c62815ffcb8b)
        ;

        
    
    
            var marker_77442f290bb0fac508ffcdc0edd0de34 = L.marker(
                [41.923582, -87.65259],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_bdf45efb0a2b253c0f0cf629b0f1d400 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_77442f290bb0fac508ffcdc0edd0de34.setIcon(icon_bdf45efb0a2b253c0f0cf629b0f1d400);
        
    
        var popup_06e96f8489cd1fd9c898f2eb7e8145cd = L.popup({"maxWidth": "100%"});

        
            
                var html_3b22e72febae6006dff6fe97abc070ee = $(`<div id="html_3b22e72febae6006dff6fe97abc070ee" style="width: 100.0%; height: 100.0%;">Sheffield Neighborhood Association (Addressing Social Issues)</div>`)[0];
                popup_06e96f8489cd1fd9c898f2eb7e8145cd.setContent(html_3b22e72febae6006dff6fe97abc070ee);
            
        

        marker_77442f290bb0fac508ffcdc0edd0de34.bindPopup(popup_06e96f8489cd1fd9c898f2eb7e8145cd)
        ;

        
    
    
            var marker_28d76246dbac812470ca839489977bda = L.marker(
                [26.363835, -80.08703],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_d7ead7301a9c938341a5c645dfe91ad8 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_28d76246dbac812470ca839489977bda.setIcon(icon_d7ead7301a9c938341a5c645dfe91ad8);
        
    
        var popup_70f97c7634c331077b84dae91ba994d0 = L.popup({"maxWidth": "100%"});

        
            
                var html_d413976f7bf7668b15b5d658308cfbaa = $(`<div id="html_d413976f7bf7668b15b5d658308cfbaa" style="width: 100.0%; height: 100.0%;">Boca Helping Hands (Addressing Social Issues)</div>`)[0];
                popup_70f97c7634c331077b84dae91ba994d0.setContent(html_d413976f7bf7668b15b5d658308cfbaa);
            
        

        marker_28d76246dbac812470ca839489977bda.bindPopup(popup_70f97c7634c331077b84dae91ba994d0)
        ;

        
    
    
            var marker_bb0a04469277737dfdea7d2d49e5d3c2 = L.marker(
                [41.888387, -87.71402],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_ec584957bd24613e90513fa5ef73158d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_bb0a04469277737dfdea7d2d49e5d3c2.setIcon(icon_ec584957bd24613e90513fa5ef73158d);
        
    
        var popup_3ef006684a815669f1b2d2411e4f8cc2 = L.popup({"maxWidth": "100%"});

        
            
                var html_754833e20fad05fc4ec0483dddab699d = $(`<div id="html_754833e20fad05fc4ec0483dddab699d" style="width: 100.0%; height: 100.0%;">Breakthrough Urban Ministries (Addressing Social Issues)</div>`)[0];
                popup_3ef006684a815669f1b2d2411e4f8cc2.setContent(html_754833e20fad05fc4ec0483dddab699d);
            
        

        marker_bb0a04469277737dfdea7d2d49e5d3c2.bindPopup(popup_3ef006684a815669f1b2d2411e4f8cc2)
        ;

        
    
    
            var marker_dd3fa4f1ec3314cf92e16530ae63f2dd = L.marker(
                [38.94813, -76.99979],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_7f4a0de9e19c6420652eaa20919af94d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_dd3fa4f1ec3314cf92e16530ae63f2dd.setIcon(icon_7f4a0de9e19c6420652eaa20919af94d);
        
    
        var popup_37be24086443cf18e3f109abe9d247e4 = L.popup({"maxWidth": "100%"});

        
            
                var html_040771f4fbab829e92fdeaec15ed79c9 = $(`<div id="html_040771f4fbab829e92fdeaec15ed79c9" style="width: 100.0%; height: 100.0%;">Capital Area Food Bank (Addressing Social Issues)</div>`)[0];
                popup_37be24086443cf18e3f109abe9d247e4.setContent(html_040771f4fbab829e92fdeaec15ed79c9);
            
        

        marker_dd3fa4f1ec3314cf92e16530ae63f2dd.bindPopup(popup_37be24086443cf18e3f109abe9d247e4)
        ;

        
    
    
            var marker_feb24189edd44b8c71e5a7f5834d5b23 = L.marker(
                [41.84271, -87.713875],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_960e0ea80e45d3bea753b9bf2e7198f2 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_feb24189edd44b8c71e5a7f5834d5b23.setIcon(icon_960e0ea80e45d3bea753b9bf2e7198f2);
        
    
        var popup_b2103c5f0a21f318cb18ba8dd9235954 = L.popup({"maxWidth": "100%"});

        
            
                var html_4de017c9258b8ac94bf58099f5d9b5fe = $(`<div id="html_4de017c9258b8ac94bf58099f5d9b5fe" style="width: 100.0%; height: 100.0%;">El Valor (Addressing Social Issues)</div>`)[0];
                popup_b2103c5f0a21f318cb18ba8dd9235954.setContent(html_4de017c9258b8ac94bf58099f5d9b5fe);
            
        

        marker_feb24189edd44b8c71e5a7f5834d5b23.bindPopup(popup_b2103c5f0a21f318cb18ba8dd9235954)
        ;

        
    
    
            var marker_78cc8fa30bf641c721a71586b5779184 = L.marker(
                [33.49353, -112.01717],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_2d16339cf7df11b6a36a03af59b7ee03 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_78cc8fa30bf641c721a71586b5779184.setIcon(icon_2d16339cf7df11b6a36a03af59b7ee03);
        
    
        var popup_899a57e4442a997e539f79167b89cf85 = L.popup({"maxWidth": "100%"});

        
            
                var html_9f0527c2a6f3758df0ba68e09f34bd9a = $(`<div id="html_9f0527c2a6f3758df0ba68e09f34bd9a" style="width: 100.0%; height: 100.0%;">Maggie's Place Family Success Center (Addressing Social Issues)</div>`)[0];
                popup_899a57e4442a997e539f79167b89cf85.setContent(html_9f0527c2a6f3758df0ba68e09f34bd9a);
            
        

        marker_78cc8fa30bf641c721a71586b5779184.bindPopup(popup_899a57e4442a997e539f79167b89cf85)
        ;

        
    
    
            var marker_42a235df32d4bf78359a0fbab837d847 = L.marker(
                [42.28385, -87.94344],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_87b17b6a693fda69dbcfb7a4313f2bf7 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_42a235df32d4bf78359a0fbab837d847.setIcon(icon_87b17b6a693fda69dbcfb7a4313f2bf7);
        
    
        var popup_06530f712425ffd10e71de8bfcc294c5 = L.popup({"maxWidth": "100%"});

        
            
                var html_2eafed86da49fe6305a1ec9867a47711 = $(`<div id="html_2eafed86da49fe6305a1ec9867a47711" style="width: 100.0%; height: 100.0%;">Feed My Starving Children (Addressing Social Issues)</div>`)[0];
                popup_06530f712425ffd10e71de8bfcc294c5.setContent(html_2eafed86da49fe6305a1ec9867a47711);
            
        

        marker_42a235df32d4bf78359a0fbab837d847.bindPopup(popup_06530f712425ffd10e71de8bfcc294c5)
        ;

        
    
    
            var marker_3ff3bc5ce497acbb04444981c9198008 = L.marker(
                [41.991196, -87.729212],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_0de08dc4c31f1a1665f8985c1e2eee83 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_3ff3bc5ce497acbb04444981c9198008.setIcon(icon_0de08dc4c31f1a1665f8985c1e2eee83);
        
    
        var popup_0f8eec48ec6bde750315c6e705c57526 = L.popup({"maxWidth": "100%"});

        
            
                var html_48bd126c6661ba8c5f5dd9ddef9d01a2 = $(`<div id="html_48bd126c6661ba8c5f5dd9ddef9d01a2" style="width: 100.0%; height: 100.0%;">Habitat for Humanity ReStore (Addressing Social Issues)</div>`)[0];
                popup_0f8eec48ec6bde750315c6e705c57526.setContent(html_48bd126c6661ba8c5f5dd9ddef9d01a2);
            
        

        marker_3ff3bc5ce497acbb04444981c9198008.bindPopup(popup_0f8eec48ec6bde750315c6e705c57526)
        ;

        
    
    
            var marker_5f674218272cdc8f8c969d838512507b = L.marker(
                [37.74966, -122.38699],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_049caaac7d3b71c0ca8011a8d50dbb26 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_5f674218272cdc8f8c969d838512507b.setIcon(icon_049caaac7d3b71c0ca8011a8d50dbb26);
        
    
        var popup_a1dc21453a572ba28c17e11d566ad5e0 = L.popup({"maxWidth": "100%"});

        
            
                var html_666a38a228b4251c634aa78eaae121cd = $(`<div id="html_666a38a228b4251c634aa78eaae121cd" style="width: 100.0%; height: 100.0%;">Marin Food Bank (Addressing Social Issues)</div>`)[0];
                popup_a1dc21453a572ba28c17e11d566ad5e0.setContent(html_666a38a228b4251c634aa78eaae121cd);
            
        

        marker_5f674218272cdc8f8c969d838512507b.bindPopup(popup_a1dc21453a572ba28c17e11d566ad5e0)
        ;

        
    
    
            var marker_287bad03f56513db69c5cd247aee2f1a = L.marker(
                [34.04509, -118.24509],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_18417408db5a8ba27881227c0b44618b = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_287bad03f56513db69c5cd247aee2f1a.setIcon(icon_18417408db5a8ba27881227c0b44618b);
        
    
        var popup_a592cd8d9aacbd2a51979c4f1bdb8ade = L.popup({"maxWidth": "100%"});

        
            
                var html_3b0a9382fc9b13ddb74e5d44a57dfe58 = $(`<div id="html_3b0a9382fc9b13ddb74e5d44a57dfe58" style="width: 100.0%; height: 100.0%;">Los Angeles Mission (Addressing Social Issues)</div>`)[0];
                popup_a592cd8d9aacbd2a51979c4f1bdb8ade.setContent(html_3b0a9382fc9b13ddb74e5d44a57dfe58);
            
        

        marker_287bad03f56513db69c5cd247aee2f1a.bindPopup(popup_a592cd8d9aacbd2a51979c4f1bdb8ade)
        ;

        
    
    
            var marker_395accade2bd0854574a0e3a4e1f2ff2 = L.marker(
                [47.522, -122.32928],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_807989f549f37a6bf8fe0bbef79b3a0b = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_395accade2bd0854574a0e3a4e1f2ff2.setIcon(icon_807989f549f37a6bf8fe0bbef79b3a0b);
        
    
        var popup_224c09db1f2de67e35259b1913d73210 = L.popup({"maxWidth": "100%"});

        
            
                var html_68765a694bf50aba4fae4f2da292cf4a = $(`<div id="html_68765a694bf50aba4fae4f2da292cf4a" style="width: 100.0%; height: 100.0%;">Seattle (Addressing Social Issues)</div>`)[0];
                popup_224c09db1f2de67e35259b1913d73210.setContent(html_68765a694bf50aba4fae4f2da292cf4a);
            
        

        marker_395accade2bd0854574a0e3a4e1f2ff2.bindPopup(popup_224c09db1f2de67e35259b1913d73210)
        ;

        
    
    
            var marker_f416c651c3cbaf37c3413acd15b41ebb = L.marker(
                [42.3592, -71.05829],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_3a481f216f74d61452b670c41373bc14 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_f416c651c3cbaf37c3413acd15b41ebb.setIcon(icon_3a481f216f74d61452b670c41373bc14);
        
    
        var popup_aa0756dfd425c682ee1f366a447908f7 = L.popup({"maxWidth": "100%"});

        
            
                var html_000092ac51c7fbe61454e6fb6fd8d013 = $(`<div id="html_000092ac51c7fbe61454e6fb6fd8d013" style="width: 100.0%; height: 100.0%;">New England Center and Home for Veterans (Addressing Social Issues)</div>`)[0];
                popup_aa0756dfd425c682ee1f366a447908f7.setContent(html_000092ac51c7fbe61454e6fb6fd8d013);
            
        

        marker_f416c651c3cbaf37c3413acd15b41ebb.bindPopup(popup_aa0756dfd425c682ee1f366a447908f7)
        ;

        
    
    
            var marker_48422eee470e40b050fd42aac8adfc0a = L.marker(
                [42.01318, -87.68982],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_89e3801589e0b4f9f3240718b225e8a8 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_48422eee470e40b050fd42aac8adfc0a.setIcon(icon_89e3801589e0b4f9f3240718b225e8a8);
        
    
        var popup_b8d0de6ba7efaf0f0dfa73710a0225aa = L.popup({"maxWidth": "100%"});

        
            
                var html_53024e08651c5396424701f823de03db = $(`<div id="html_53024e08651c5396424701f823de03db" style="width: 100.0%; height: 100.0%;">Tree House Humane Society (Addressing Social Issues)</div>`)[0];
                popup_b8d0de6ba7efaf0f0dfa73710a0225aa.setContent(html_53024e08651c5396424701f823de03db);
            
        

        marker_48422eee470e40b050fd42aac8adfc0a.bindPopup(popup_b8d0de6ba7efaf0f0dfa73710a0225aa)
        ;

        
    
    
            var marker_58a4b4fc899c66c3cf807da8d3b7dbec = L.marker(
                [40.761445, -73.98565],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_a206a4917f8f5b68d69119b333ccf814 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_58a4b4fc899c66c3cf807da8d3b7dbec.setIcon(icon_a206a4917f8f5b68d69119b333ccf814);
        
    
        var popup_0daa034f334e64c2df1665c73decc4e8 = L.popup({"maxWidth": "100%"});

        
            
                var html_65bf8fc20d676c7e4f65fb792ba275b1 = $(`<div id="html_65bf8fc20d676c7e4f65fb792ba275b1" style="width: 100.0%; height: 100.0%;">Encore Community Services  (Addressing Social Issues)</div>`)[0];
                popup_0daa034f334e64c2df1665c73decc4e8.setContent(html_65bf8fc20d676c7e4f65fb792ba275b1);
            
        

        marker_58a4b4fc899c66c3cf807da8d3b7dbec.bindPopup(popup_0daa034f334e64c2df1665c73decc4e8)
        ;

        
    
    
            var marker_531654e385a85588c3f62c276085cdcd = L.marker(
                [41.84398, -87.71147],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_6bb2e6f92d74516ca9f91f02b9633de0 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_531654e385a85588c3f62c276085cdcd.setIcon(icon_6bb2e6f92d74516ca9f91f02b9633de0);
        
    
        var popup_474c8658296330733f4b7b9275486263 = L.popup({"maxWidth": "100%"});

        
            
                var html_565b0aeab2cf53a29bab1f59991467f9 = $(`<div id="html_565b0aeab2cf53a29bab1f59991467f9" style="width: 100.0%; height: 100.0%;">Enlace Chicago (Addressing Social Issues)</div>`)[0];
                popup_474c8658296330733f4b7b9275486263.setContent(html_565b0aeab2cf53a29bab1f59991467f9);
            
        

        marker_531654e385a85588c3f62c276085cdcd.bindPopup(popup_474c8658296330733f4b7b9275486263)
        ;

        
    
    
            var marker_2ef93af4543f23fdc2df16f1851408f1 = L.marker(
                [41.976663, -87.668055],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_81bbe1c3f6159c877224cbd51700b708 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_2ef93af4543f23fdc2df16f1851408f1.setIcon(icon_81bbe1c3f6159c877224cbd51700b708);
        
    
        var popup_8c9717f94480bae1593fae841a477c10 = L.popup({"maxWidth": "100%"});

        
            
                var html_175e4e514c5196f95f7297ac90a19577 = $(`<div id="html_175e4e514c5196f95f7297ac90a19577" style="width: 100.0%; height: 100.0%;">Swedish American Museum (Addressing Social Issues)</div>`)[0];
                popup_8c9717f94480bae1593fae841a477c10.setContent(html_175e4e514c5196f95f7297ac90a19577);
            
        

        marker_2ef93af4543f23fdc2df16f1851408f1.bindPopup(popup_8c9717f94480bae1593fae841a477c10)
        ;

        
    
    
            var marker_16d20534bb785b69b2619f1f083490d4 = L.marker(
                [41.578816, -88.088843],
                {}
            ).addTo(map_0645f74934c2e18d754fe391c86431ae);
        
    
            var icon_80fc9e5dee60e5f94012e4a5f1e89b66 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "users", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_16d20534bb785b69b2619f1f083490d4.setIcon(icon_80fc9e5dee60e5f94012e4a5f1e89b66);
        
    
        var popup_9284e117926caec42378115888888472 = L.popup({"maxWidth": "100%"});

        
            
                var html_c7aaa2d6d2ec61f0ccb99942fac336fc = $(`<div id="html_c7aaa2d6d2ec61f0ccb99942fac336fc" style="width: 100.0%; height: 100.0%;">Cook County Sheriff's Office, Illinois Department of Corrections, Chicago Votes, Chicago Lawyers Committee for Civil Rights (Addressing Social Issues)</div>`)[0];
                popup_9284e117926caec42378115888888472.setContent(html_c7aaa2d6d2ec61f0ccb99942fac336fc);
            
        

        marker_16d20534bb785b69b2619f1f083490d4.bindPopup(popup_9284e117926caec42378115888888472)
        ;

        
    
</script>
</html>
