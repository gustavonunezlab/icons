# Icons
Icons for leaflet made by me. If you need more icons, send request at guscostaf@gmail.com

Types of icon: airport, bank, educative, gym, goberment, hospital, hotel, home, church, office, shipport, rest, restaurant, market.

Types of marker: icon (classic marker), star, diamond, square.

Colours: darkred, red, orange, yellow, darkblue, blue, lightblue, violet, darkpink, pink, darkgreen, green, lightgreen, black, white.

All possible combinations.

# Usage
```
var blueIcon = new L.Icon({
  iconUrl: 'https://raw.githubusercontent.com/gustavonunezlab/icons/main/blue-matte.png'
  shadowUrl: 'https://cdnjs.cloudflare.com/ajax/libs/leaflet/0.7.7/images/marker-shadow.png',
  iconSize: [25, 41],
  iconAnchor: [12, 41],
  popupAnchor: [1, -34],
  shadowSize: [41, 41]
});

L.marker([-42, -65], {icon: blueIcon}).addTo(map);
```
