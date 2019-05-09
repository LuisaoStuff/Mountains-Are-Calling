# Mountais Are Calling

## ¿De que se trata?
_'Mountains are calling'_ es una aplicación que se encarga de recopilar publicaciones en plataformas tales como **Instagram**, **Facebook**,**Twitter** o **YouTube** y obtiene la ubicación para generar un mapa de calor en **Google Maps**, permitiendote seleccionar rango de tiempo, localizaciones concretas, etc.
También mostrará los lugares de hospedaje más cercanos además de poder reservarlos. 

## ¿Cómo va a funcionar?
Haré uso de las **APIs** como YouTube, Facebook, Twitter, Instagram para recopilar las ubicaciones y las fechas de subida de las mismas, y después las usaré en la API de Google Maps.

### APIs
- Facebook: Autenticación *OAuth 2.0*
- Instagram: Autenticación *OAuth 2.0*
      (Está construida sobre la API de Facebook)
- Youtube: Autenticación *keyª* o *OAuth 2.0*
- Google Maps: Autenticación *keyª* o *OAuth 2.0*
- Booking: Autenticación *HTTP*

**Todas estas APIs ofrecen una respuesta en formato *JSON***

**keyª**: Esta key es la que obtienes al crear un proyecto en el entorno de desarrollo de APIs de Google.
