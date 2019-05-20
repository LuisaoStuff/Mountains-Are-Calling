# Mountais Are Calling

## ¿De que se trata?
_'Mountains are calling'_ es una aplicación que se encarga de recoger los datos de vías y lugares de escalada a través de la página **Mountain Project**, y usa la *API* de **Mapbox** para mostrarlos en un mapa interactivo. En principio también daré la posibilidad de ver los precios de **blablacar**, aunque más adelante si consigo los permisos necesarios también mostrará los lugares de hospedaje más cercanos además de poder reservarlos. 

## ¿Cómo va a funcionar?
Haré uso de las *API* como **MountainProject** para recopilar las ubicaciones y las fechas de subida de las mismas, y después las usaré en la *API* de **Mapbox** además de **blablacar**.

### APIs
- [MapBox](https://docs.mapbox.com/api/): Autenticación *key*
- [MountainProject](https://www.mountainproject.com/data): Autenticación *key*
- [Blablacar](https://dev.blablacar.com/docs/versions/1.0): Autenticación *key*

**Todas estas APIs ofrecen una respuesta en formato *JSON***
### Pequeño programa en la [terminal](Consultas a MountainProject.py)
