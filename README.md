# XML-formatted data
This repo contains all the XMLs of the italian route related to the Erasmus project.
The XMLs are divided in 2 categries:
  - Cities:
  ```
  <?xml version="1.0" encoding="UTF-8"?>
<city_overview>
    <city>
         <id></id>                         <!--integer-->
         <title></title>                   <!--string-->
         <lat></lat>                       <!--DMS(degree, minutes, seconds)-->
         <lng></lng>                       <!--DMS(degree, minutes, seconds)-->
         <description></description>       <!--inhabitants, area, picture, region, foundation, history, around 50 words-->
         <inhabitants></inhabitants>       <!--integer-->
         <area></area>                     <!--square kilometers-->
         <image></image>                   <!--image file-->
         <region></region>                 <!--string-->
    </city>
</city_overview>
  ```
  - Sights:
  ```
<?xml version="1.0" encoding="UTF-8"?>
<sight>
    <id></id>
    <title></title>
    <lat></lat>                     <!--GMS(degree,minute,seconds)-->
    <lng></lng>                     <!--GMS(degree,minute,seconds)-->
    <description></description>     <!--yearOfConstruction,architect,what can you do?, what makes this place unique?,size, History-->
    <category></category>           <!-- String-->
    <image></image>
    <yearOfConstruction></yearOfConstruction>
    <architect></architect>
    <size></size>                   <!--height-->
</sight>
  ```
