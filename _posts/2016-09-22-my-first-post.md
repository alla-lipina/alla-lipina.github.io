---
layout: post
title: My first post!
---
# Hello World!

Here are the countries I have been to!

<script src="https://www.amcharts.com/lib/3/ammap.js" type="text/javascript"></script>
<script src="https://www.amcharts.com/lib/3/maps/js/worldHigh.js" type="text/javascript"></script>
<script src="https://www.amcharts.com/lib/3/themes/dark.js" type="text/javascript"></script>
<div id="mapdiv" style="width: 100%; height: 450px;"></div>

<script type="text/javascript">
var map = AmCharts.makeChart("mapdiv",{
type: "map",
theme: "dark",
projection: "mercator",
panEventsEnabled : true,
backgroundColor : "#535364",
backgroundAlpha : 1,
zoomControl: {
zoomControlEnabled : true
},
dataProvider : {
map : "worldHigh",
getAreasFromMap : true,
areas :
[
  {
    "id": "AT",
    "showAsSelected": true
  },
  {
    "id": "BE",
    "showAsSelected": true
  },
  {
    "id": "CH",
    "showAsSelected": true
  },
  {
    "id": "CZ",
    "showAsSelected": true
  },
  {
    "id": "DE",
    "showAsSelected": true
  },
  {
    "id": "DK",
    "showAsSelected": true
  },
  {
    "id": "EE",
    "showAsSelected": true
  },
  {
    "id": "ES",
    "showAsSelected": true
  },
  {
    "id": "FI",
    "showAsSelected": true
  },
  {
    "id": "FR",
    "showAsSelected": true
  },
  {
    "id": "GB",
    "showAsSelected": true
  },
  {
    "id": "GR",
    "showAsSelected": true
  },
  {
    "id": "IT",
    "showAsSelected": true
  },
  {
    "id": "ME",
    "showAsSelected": true
  },
  {
    "id": "NL",
    "showAsSelected": true
  },
  {
    "id": "PT",
    "showAsSelected": true
  },
  {
    "id": "SE",
    "showAsSelected": true
  },
  {
    "id": "TR",
    "showAsSelected": true
  },
  {
    "id": "RU",
    "showAsSelected": true
  },
  {
    "id": "TH",
    "showAsSelected": true
  },
  {
    "id": "VN",
    "showAsSelected": true
  }
]
},
areasSettings : {
autoZoom : true,
color : "#B4B4B7",
colorSolid : "#84ADE9",
selectedColor : "#84ADE9",
outlineColor : "#666666",
rollOverColor : "#9EC2F7",
rollOverOutlineColor : "#000000"
}
});
</script>

