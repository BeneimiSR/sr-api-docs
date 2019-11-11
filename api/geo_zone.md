# Geo Zone Resource

## Tulajdonságok

<ResourceProperties :resource="'geo_zone'" :lang="'hu'"/>

## Endpoints

[//]: <> (GET ENDPOINT)
<ResourceEndpoint :resource="'geo_zone'" :endpoint="'get'" :lang="'hu'">

<template v-slot:responseJSON>

<<< @/docs/fixtures/api/geo_zone/response/json/get_id.json

</template>

<template v-slot:responseXML>

<<< @/docs/fixtures/api/geo_zone/response/xml/get_id.xml

</template>

</ResourceEndpoint>

[//]: <> (GETCOLLECTION ENDPOINT)
<ResourceEndpoint :resource="'geo_zone'" :endpoint="'getCollection'" :lang="'hu'">

<template v-slot:responseJSON>

<<< @/docs/fixtures/api/geo_zone/response/json/get_page.json

</template>

<template v-slot:responseXML>

<<< @/docs/fixtures/api/geo_zone/response/xml/get_page.xml

</template>

</ResourceEndpoint>

