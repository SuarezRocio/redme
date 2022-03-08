# redme


Utilizando el metodo POST.
Recupere, los detalles de la propiedad.
POST https://supply-xml.booking.com/hotels/ota/OTA_HotelDescriptiveInfo


utilice el punto final <OTA_HotelDescriptiveInfo

El cuerpo contine el ID de la propiedad:
<OTA_HotelDescriptiveInfoQR>
<HotelDescriptiveInfos>
  <HotelDescriptiveInfo HotelCode="{PropertyID}"></HotelDescriptiveInfo>
</HotelDescriptiveInfo>
</OTA_HotelDescriptiveInfoRQ>

La respuesta es larga, por lo que no daremos un ejemplo completo aqui, pero las primeras
lineas se ven asi:
<?xml verion="1.0" encoding="UTF-8"?>
<OTA_HotelDescriptiveInfoRS
xmlns= "http://www.opentravel.org/OTA/2003/05 OTA_HotelDescriptiveInfoRS.xsd"
TimeStamp="2018-02-07T14:08:01+00:00"
Target="Production"
Version="1.006"
<HotelDescriptiveContents>
<HotelDescriptiveContent
HotelName="The Best Hotel"
LanguageCode="en"
ID="1234567"
Status="Test Hotel"
CurrencyCode= "EUR">
  </HotelDescriptiveContent>
</HotelDescriptiveContents>

</OTA_HotelDescriptiveContentNotifRS>
/*-------------------------------------------------------*/




