# Domain Resource

## Tulajdonságok

<ResourceProperties :resource="'domain'" :lang="'hu'"/>

## Endpoints

[//]: <> (GETCOLLECTION ENDPOINT)
<ResourceEndpoint :resource="'domain'" :endpoint="'getCollection'" :lang="'hu'">

<template v-slot:responseJSON>

<<< @/docs/fixtures/api/domain/response/json/get_page.json

</template>

<template v-slot:responseXML>

<<< @/docs/fixtures/api/domain/response/xml/get_page.xml

</template>

</ResourceEndpoint>

