
<img width="1000" alt="Fuente_5V_4 8A" src="https://github.com/AlanRavelo/Power_flyback_4.8A/assets/88397949/fb821288-8b77-4366-9bef-5bbf648218e7">


## Descripción

Este repositorio contiene información sobre el diseño de una fuente SMPS de topología Flyback, de entrada monofásica, diseñada para proporcionar una salida de 5 VDC / 4.8 A.

Una fuente SMPS (Switched-Mode Power Supply) es un tipo de fuente de alimentación que utiliza la conmutación rápida de componentes electrónicos, como transistores, para convertir la energía eléctrica de una forma a otra de manera eficiente. En lugar de usar grandes transformadores y componentes pasivos, como en las fuentes de alimentación tradicionales, las fuentes SMPS utilizan una conmutación rápida para controlar la cantidad de energía que se entrega a un dispositivo, lo que las hace más compactas y eficientes en la conversión de energía.

El funcionamiento de una fuente SMPS se basa en un tranformador flyback, el cual aprovecha la propiedad de transformación electromagnética para convertir la energía rectificada en un voltaje de salida establecido. Para lograr esto, se utiliza una fuente de conmutación representado por el [TNY290P](https://www.power.com/sites/default/files/documents/tinyswitch-4_family_datasheetTW.pdf), el cual genera un almacenamiento de energía en el núcleo magnético del tranformador durante una fase y liberada en la siguiente. Esto produce un cambio de voltaje del inductor primario e induce una tensión, en este caso, más baja en el lado secundario del transformador, que se rectifica y filtra para obtener una corriente continua más suave y estable.
 
## Aplicaciones

Esta fuente conmutada es adecuada para una variedad de aplicaciones como:
* Electrodomésticos
* Aplicaciones de retorno sin conexión
* Controles industriales
* Iluminación LED
* Adaptadores inteligentes
* Medición.

## Referencias
* PI Expert Online
* [DESIGN CONSIDERATIONS FOR FLYBACK TRANSFORMER](https://www.we-online.com/files/pdf1/design-considerations-for-flyback-transformer.pdf)
* [Würth Elektronik](https://www.we-online.com/en/components/products)
* [KiCad.org](https://www.kicad.org/)
* [FreeCad](https://www.freecad.org/)

**Para obtener más información técnica, esquemas eléctricos y detalles sobre el diseño, consulte los archivos y documentos en este repositorio.
