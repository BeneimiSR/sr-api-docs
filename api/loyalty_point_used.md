# Loyalty Point Used Resource

## Tulajdonságok

<ResourceProperties :resource="'loyalty_point_used'" :lang="'hu'"/>

## Endpoints

[//]: <> (GET ENDPOINT)
<ResourceEndpoint :resource="'loyalty_point_used'" :endpoint="'get'" :lang="'hu'">

<template v-slot:responseJSON>

<<< @/docs/fixtures/api/loyalty_point_used/response/json/get_id.json

</template>

<template v-slot:responseXML>

<<< @/docs/fixtures/api/loyalty_point_used/response/xml/get_id.xml

</template>

</ResourceEndpoint>

[//]: <> (GETCOLLECTION ENDPOINT)
<ResourceEndpoint :resource="'loyalty_point_used'" :endpoint="'getCollection'" :lang="'hu'">

<template v-slot:responseJSON>

<<< @/docs/fixtures/api/loyalty_point_used/response/json/get_page.json

</template>

<template v-slot:responseXML>

<<< @/docs/fixtures/api/loyalty_point_used/response/xml/get_page.xml

</template>

</ResourceEndpoint>

[//]: <> (POST ENDPOINT)
<ResourceEndpoint :resource="'loyalty_point_used'" :endpoint="'post'" :lang="'hu'">

<template v-slot:request>

<<< @/docs/fixtures/api/loyalty_point_used/request/post.json

</template>

<template v-slot:responseJSON>

<<< @/docs/fixtures/api/loyalty_point_used/response/json/get_id.json

</template>

<template v-slot:responseXML>

<<< @/docs/fixtures/api/loyalty_point_used/response/xml/get_id.xml

</template>

</ResourceEndpoint>

[//]: <> (PUT ENDPOINT)
<ResourceEndpoint :resource="'loyalty_point_used'" :endpoint="'put'" :lang="'hu'">

<template v-slot:request>

<<< @/docs/fixtures/api/loyalty_point_used/request/put.json

</template>

<template v-slot:responseJSON>

<<< @/docs/fixtures/api/loyalty_point_used/response/json/get_id.json

</template>

<template v-slot:responseXML>

<<< @/docs/fixtures/api/loyalty_point_used/response/xml/get_id.xml

</template>

</ResourceEndpoint>

[//]: <> (DELETE ENDPOINT)
<ResourceEndpoint :resource="'loyalty_point_used'" :endpoint="'delete'" :lang="'hu'"/>

