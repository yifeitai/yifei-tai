# yifei-tai

My Fresh Crop

This is a Web App to help people find the freshest and the best crop   in Indiana.

The App uses Google Map API with a database which will updated every day to show the crop   from the best to the worst in local food markets. The database includes: fresh level, price, market location, customer rate of the crop   , parking lot, open hour, customer rate of the market, service, etc. You can compare those markets on the App to decide which market you will go.

Description

1.	Datasets
	
Agriculture,Crops - CROPS_2008_USDA_IN: Crops in Indiana for 2008, Derived from National Agricultural Statistics Service (http://catalog.data.gov/dataset/agriculture-crops-crops-2008-usda-in-crops-in-indiana-for-2008-derived-from-national-agricultu). 

Data from 2008 to 2014.

Columns used: farmland, grain, farming, crop, etc.

2.	Map View
	
At the first, the map is located at Indianapolis which is the capital of Indiana.

We will mark a point on the food market where sell the crop   and we will also mark a star on the food market when they have the freshest crop today.

We will have some recommend markets on the bottom of the map.

When you click one of the food markets on the map, the information will show on the right of the screen, you can know the basic information of that market such as open hour and price of the freshest crop   they have etc.

On the left top there will be a current weather data use OpenWeatherMap API (http://openweathermap.org/api).


<html>
<body>

<div id= "demo"><h2>Let AJAX change this text</h2></div>

<button type="botton" onclick="loadDoc()"> Change Content</button>

<script>
function loadDoc() {
  var xhttp = new XMLHttpRequest();
  xhttp.onreadystatechange = function() {
    if (this.readyState == 4 && this.status == 200) {
     document.getElementById("demo").innerHTML = this.responseText;
    }
  };
  xhttp.open("GET", "ftp://ftp.ncdc.noaa.gov/pub/data/hourly_precip-3240/by_month2013/3240sep2013.dat", true);
  xhttp.send();
}

</script>

</body>
</html>




for the website looks like. i think its pretty like google map which can search the freshest crop in west lafayette and when you find the market you interested in you can click it on the map and the detail of that market and crop will be showed such asfresh level, price, market location, customer rate of the crop   , parking lot, open hour, customer rate of the market, service, etc.  
