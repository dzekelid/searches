---
name: Amadeus
x-slug: amadeus
description: Amadeus travel technology helps businesses connect to the global travel
  ecosystem, manage operations more effectively and serve travellers better than ever
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28139-sandbox-amadeus-com.jpg
x-kinRank: "8"
x-alexaRank: "4309"
tags: Searches
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/searches/master/_listings/amadeus/apis.md
specificationVersion: "0.14"
apis:
- name: Amadeus Get Travel Intelligence Top Searches
  x-api-slug: amadeus
  description: "The Top Flight Search allows you to find number of estimated searches
    from an origin, optionally a destination, within a time period when travelers
    are performing the searches. \nThe search is based on queries performed from within
    a country (also refers to as market) and returns up to 50 results, ordered by
    popularity, showing number of searches for most searched destination with its
    previous year comparison. This search also shows patterns on how travelers are
    searching for flights, revealing where, when and for how long they\u2019re planning
    to travel. See\nTrip Durations(How long are the trips planned for?) and\n Advance
    Search Period (How long before departures do travelers start searching for their
    trips?)\n\nThis estimated search is based on Amadeus' Travel Intelligence Engine,
    a high performance scalable cloud-based platform, born in the age of Big Data
    and purposely built for the industry bringing total flexibility and speed to business
    intelligence for travel. Please see amadeus.com/travelintelligence for more information."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28139-sandbox-amadeus-com.jpg
  humanURL: https://amadeus.com
  baseURL: https://api.sandbox.amadeus.com//v1.2//travel-intelligence/top-searches
  tags: Travel, Intelligence, Top, Searches
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/searches/master/_listings/amadeus/travelintelligencetopsearches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/searches/master/_listings/amadeus/travelintelligencetopsearches-get-openapi.md
- name: Amadeus
  x-api-slug: amadeus
  description: Amadeus travel technology helps businesses connect to the global travel
    ecosystem, manage operations more effectively and serve travellers better than
    ever
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28139-sandbox-amadeus-com.jpg
  humanURL: https://amadeus.com
  baseURL: https://api.sandbox.amadeus.com//v1.2
  tags: Searches
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/searches/master/_listings/amadeus/openapi.md
x-common:
- type: x-crunchbase
  url: https://crunchbase.com/organization/amadeus
- type: x-documentation
  url: https://sandbox.amadeus.com/api-catalog
- type: x-github
  url: https://github.com/AmadeusITGroup
- type: x-privacy-policy
  url: http://www.amadeus.com/web/amadeus/en_1A-corporate/Amadeus-Home/Amadeus_IT_Group_SA-Legal-notices-2014/1319560218660-Page-AMAD_Detail_PopUp_Ppal?assetid=1319607040997&assettype=DataProtection_C
- type: x-sandbox
  url: https://sandbox.amadeus.com
- type: x-twitter
  url: https://twitter.com/amadeusinnov
- type: x-website
  url: https://amadeus.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---