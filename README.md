# Icons
Some icons for leaflet

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
