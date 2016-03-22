# UC Forest Products Group Biomass Database Web Resource

Displays database resources as publicly available HTML table and leaflet map.

##Sources
Built on a compilation of many openly sourced javascript plugins
	Leaflet
	<script src="https://cdnjs.cloudflare.com/ajax/libs/leaflet/0.7.3/leaflet.js" ></script>
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/leaflet/0.7.3/leaflet.css" />
   	
   	Jquery
   	<script src="https://code.jquery.com/jquery-1.10.1.min.js" ></script>
   <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js" ></script>
   <script src="https://code.jquery.com/jquery-migrate-1.2.1.min.js" ></script>
   <!--[if lte IE 8] ><link rel="stylesheet" href="http://leaflet.cloudmade.com/dist/leaflet.ie.css" / ><![endif]-->

   <!--  group layer control -->
   <script src="https://cdn.rawgit.com/ismyrnow/Leaflet.groupedlayercontrol/gh-pages/src/leaflet.groupedlayercontrol.js"></script>
   <link rel="stylesheet" href="https://cdn.rawgit.com/ismyrnow/Leaflet.groupedlayercontrol/gh-pages/src/leaflet.groupedlayercontrol.css" />

   <!-- font aswesome icons used in social plugin-->
   <link href="https://netdna.bootstrapcdn.com/font-awesome/3.1.1/css/font-awesome.css" rel="stylesheet" />

   <!-- maki markers-->
   <script src="https://cdn.rawgit.com/jseppi/Leaflet.MakiMarkers/master/Leaflet.MakiMarkers.js" ></script>

   <!-- leaflet hash for social integration-->
   <script type='text/javascript' src="https://cdn.rawgit.com/mlevans/leaflet-hash/master/leaflet-hash.js" ></script>

   <!-- context menu plugin -->
   <script src="https://aratcliffe.github.io/Leaflet.contextmenu/dist/leaflet.contextmenu.js" ></script>
   <link rel="stylesheet" href="https://aratcliffe.github.io/Leaflet.contextmenu/dist/leaflet.contextmenu.css"/>

   <!-- GEOCONTROL - geocontrol search box script -->
   <script src="https://smeijer.github.io/GeoSearch/js/l.control.geosearch.js" ></script>
   <script src="https://smeijer.github.io/GeoSearch/js/l.geosearch.provider.google.js" ></script>
   <link rel="stylesheet" href="https://smeijer.github.io/GeoSearch/css/l.geosearch.css" />

   <!-- marker cluster script -->
   <link rel="stylesheet" href="https://leaflet.github.io/Leaflet.markercluster/dist/MarkerCluster.css" />
   <link rel="stylesheet" href="https://leaflet.github.io/Leaflet.markercluster/dist/MarkerCluster.Default.css" />
   <script src="https://leaflet.github.io/Leaflet.markercluster/dist/leaflet.markercluster-src.js" ></script>

   <!-- GOOGLE  - google map plugin -->
   <!-- <script src="https://maps.google.com/maps/api/js?v=3.2&sensor=false" ></script> -->
   <!-- // <script src="http://psha.org.ru/leaflet/plugins/layer/tile/Google.js" ></script> -->
   <!-- // <script src="https://cdn.rawgit.com/DGuidi/1992824.js"></script> -->
   <!-- // <script src="https://gist.githubusercontent.com/crofty/2197042/raw/2b90c41b39b7d5b3a851d8f256de2ebd3fe1fb74/leaflet-google.js"></script> -->
   <!-- // <script type='text/javascript' src="https://gist.githubusercontent.com/crofty/2197042/raw/"></script> -->
   <!-- // <script  type="text/javascript" src="https://gist.githubusercontent.com/AndrewJHart/9766852/raw/2b90c41b39b7d5b3a851d8f256de2ebd3fe1fb74/leaflet-google.js"></script> -->
   <script  type="text/javascript" src="https://rawgit.com/AndrewJHart/9766852/raw/2b90c41b39b7d5b3a851d8f256de2ebd3fe1fb74/leaflet-google.js"></script>
   <!-- // <script type='text/plain' src="https://gist.githubusercontent.com/crofty/2197042/raw/"></script> -->
   <script type="text/javascript" src="https://stamen-maps.a.ssl.fastly.net/js/tile.stamen.js" ></script>
   
   <!-- MINIMAP Plugins -->
   <link rel="stylesheet" href="https://norkart.github.io/Leaflet-MiniMap/Control.MiniMap.css" />
   <script src="https://norkart.github.io/Leaflet-MiniMap/Control.MiniMap.js" type="text/javascript" ></script>

   <!-- Omnivore Script -->
   <script src='https://api.tiles.mapbox.com/mapbox.js/plugins/leaflet-omnivore/v0.2.0/leaflet-omnivore.min.js' ></script>
   <meta name='viewport' content='width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no' />

   <!-- fullscreen scripts -->
   <script src='https://api.tiles.mapbox.com/mapbox.js/plugins/leaflet-fullscreen/v0.0.1/Leaflet.fullscreen.min.js' ></script>
   <link href='https://api.tiles.mapbox.com/mapbox.js/plugins/leaflet-fullscreen/v0.0.1/leaflet.fullscreen.css' rel='stylesheet' />

   <!-- zoom slider scripts -->
   <script src='https://api.tiles.mapbox.com/mapbox.js/plugins/leaflet-zoomslider/v0.7.0/L.Control.Zoomslider.js' ></script>
   <link href='https://api.tiles.mapbox.com/mapbox.js/plugins/leaflet-zoomslider/v0.7.0/L.Control.Zoomslider.css' rel='stylesheet' />

   <!-- leaflet share control https://github.com/makinacorpus/Leaflet.Social/blob/master/example.html -->
   <script type='text/javascript' src="https://makinacorpus.github.io/Leaflet.Social/leaflet.social.js" ></script>
   <link rel="stylesheet" type="text/css" href="https://makinacorpus.github.io/Leaflet.Social/leaflet.social.css" />

  <!-- Leaflet map print scripts. Saved on google drive in folder. No web script link
  <link rel="stylesheet" href="dist/easyPrint.css"/> 
  <script src="dist/jQuery.print.js" ></script>
  <script src="dist/leaflet.easyPrint.js" ></script> 
  old print screen scripts
  <script src="http://aratcliffe.github.io/Leaflet.print/dist/leaflet.print.js" ></script>
    <link rel="stylesheet" href="http://aratcliffe.github.io/Leaflet.print/dist/leaflet.print.css"/>
    <script src="http://apps2.geosmart.co.nz/mapfish-print/pdf/info.json?var=printConfig"></script>-->

####

 Done in 100% JavaScript.

Check out the working demo: http://derekeder.github.io/csv-to-html-table/

## Usage

#### 1. Clone this repository (in the command line)

``` bash
git clone git@github.com:derekeder/csv-to-html-table.git
cd csv-to-html-table
```

#### 2. Add your CSV file to the `data/` folder

#### 3. In `index.html` configure the `init_table()` function

``` html
<script>
  init_table({
    csv_path: 'data/Health Clinics in Chicago.csv', 
    element: 'table-container', 
    allow_download: true,
    csv_options: {separator: ',', delimiter: '"'},
    datatables_options: {"paging": false}
  });
</script>
```

Available options:
* `csv_path` Path to your CSV file.
* `element` The HTML element to render your table to. Defaults to `table-container`
* `allow_download` if true, shows a link to download the CSV file. Defaults to `false`
* `csv_options` jQuery CSV configuration. Use this if you want to use a custom `delimiter` or `separator` in your input file. See [their documentation](https://code.google.com/p/jquery-csv/wiki/API#$.csv.toArrays%28%29).
* `datatables_options` DataTables configuration. See [their documentation](http://datatables.net/reference/option/).

#### 4. Run it

You can run this locally using this handy python command:

```bash
python -m SimpleHTTPServer
```

navigate to http://localhost:8000/

#### 5. Deploy it

**GitHub pages** You can host your table on GitHub pages for free! Once you've made all your changes and committed them, push everything in the `master` branch to `gh-pages` which automatically enables GitHub pages.
```bash
git push origin master:gh-pages
```

Then navigate to http://your-github-username.github.io/csv-to-html-table/

Read more on working with [GitHub pages projects](https://help.github.com/articles/user-organization-and-project-pages/#project-pages).

**Web server** This project should work on any web server. Upload this entire project (including all the `css`, `data`, `fonts` and `js` folders) to a public folder on your server using FTP.

#### 6. iframe it (optional)

Want to embed your nifty table on your website? You can use an [iframe](http://www.w3schools.com/tags/tag_iframe.asp). Once you've deployed your table (above in step 5) you can link to it in an iframe right in your HTML.

```html
<iframe style="border-style: none;" src="http://derekeder.github.io/csv-to-html-table/" height="950" width="600"></iframe>
```

## Dependencies

* [Bootstrap](http://getbootstrap.com/) - Responsive HTML, CSS and Javascript framework
* [jQuery](https://jquery.com/) - a fast, small, and feature-rich JavaScript library
* [jQuery CSV](https://code.google.com/p/jquery-csv/) - Parse CSV (Comma Separated Values) to Javascript arrays or dictionaries.
* [DataTables](http://datatables.net/) - add advanced interaction controls to any HTML table.

## Errors / Bugs

If something is not behaving intuitively, it is a bug, and should be reported.
Report it here: https://github.com/derekeder/csv-to-html-table/issues

## Note on Patches/Pull Requests
 
* Fork the project.
* Make your feature addition or bug fix.
* Send a pull request. Bonus points for topic branches.

## Copyright

Copyright (c) 2015 Derek Eder. Released under the [MIT License](https://github.com/derekeder/csv-to-html-table/blob/master/LICENSE).
