# Mountais Are Calling

## ¿De que se trata?
_'Mountains are calling'_ es una aplicación que se encarga de recopilar publicaciones en plataformas tales como **Instagram**, **Facebook** o **YouTube** y obtiene la ubicación para generar un mapa de calor en **Google Maps**, permitiendote seleccionar rango de tiempo, localizaciones concretas, etc.
También mostrará los lugares de hospedaje más cercanos además de poder reservarlos. 

## ¿Cómo va a funcionar?
Haré uso de las **APIs** como YouTube, Facebook, Instagram para recopilar las ubicaciones y las fechas de subida de las mismas, y después las usaré en la API de Google Maps.

### APIs
- [Facebook](https://developers.facebook.com/docs/graph-api?locale=es_ES): Autenticación *OAuth 2.0*
- [Instagram](https://developers.facebook.com/docs/instagram-api/): Autenticación *OAuth 2.0*
      (Está construida sobre la API de Facebook)
- [Youtube](https://developers.google.com/youtube/v3/): Autenticación *key* o *OAuth 2.0*
- [MapBox](https://docs.mapbox.com/api/): Autenticación *key*
- [Booking](https://developers.booking.com/api/commercial/index.html?version=2.4&page_url=getting-started): Autenticación *HTTP*

**Todas estas APIs ofrecen una respuesta en formato *JSON***
