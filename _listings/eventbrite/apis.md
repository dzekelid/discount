---
name: Eventbrite
x-slug: eventbrite
description: Eventbrite brings people together through live experiences. Discover
  events that match your passions, or create your own with online ticketing tools.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
x-kinRank: "9"
x-alexaRank: "643"
tags: Discount
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/discount/master/_listings/eventbrite/apis.md
specificationVersion: "0.14"
apis:
- name: Eventbrite - Get Discount New
  x-api-slug: discount-new-get
  description: This method creates a new discount code for a specific event. It returns
    the ID of the newly created discount code.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discount/master/_listings/eventbrite/discount-new-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discount/master/_listings/eventbrite/discount-new-get-openapi.md
- name: Eventbrite - Get Discount Update
  x-api-slug: discount-update-get
  description: This method is used to update an existing discount code. Only the fields
    passed as arguments will be modified. This method returns the ID of the modified
    discount code.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discount/master/_listings/eventbrite/discount-update-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discount/master/_listings/eventbrite/discount-update-get-openapi.md
- name: Eventbrite - Get Discounts Discount
  x-api-slug: discountsdiscount-id-get
  description: Returns the cross_event_discount with the specified :discount_id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discount/master/_listings/eventbrite/discountsdiscount-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discount/master/_listings/eventbrite/discountsdiscount-id-get-openapi.md
- name: Eventbrite - Post Discounts Discount
  x-api-slug: discountsdiscount-id-post
  description: Updates the discount with the specified :discount_id. Returns the updated
    cross_event_discount. The fields sent are the ones that are going to be updated,
    the fields that are not sent will be unchanged. The same conditions and notes
    for the discount creation apply.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discount/master/_listings/eventbrite/discountsdiscount-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discount/master/_listings/eventbrite/discountsdiscount-id-post-openapi.md
- name: Eventbrite - Delete Discounts Discount
  x-api-slug: discountsdiscount-id-delete
  description: |-
    Deletes the cross_event_discount with the specified :discount_id.
    Only unused discounts can be deleted.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discount/master/_listings/eventbrite/discountsdiscount-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discount/master/_listings/eventbrite/discountsdiscount-id-delete-openapi.md
- name: Eventbrite - Get Events Discounts Discount
  x-api-slug: eventsiddiscountsdiscount-id-get
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-get-discounts-discount-id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discount/master/_listings/eventbrite/eventsiddiscountsdiscount-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discount/master/_listings/eventbrite/eventsiddiscountsdiscount-id-get-openapi.md
- name: Eventbrite - Post Events Discounts Discount
  x-api-slug: eventsiddiscountsdiscount-id-post
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-post-discounts-discount-id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discount/master/_listings/eventbrite/eventsiddiscountsdiscount-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discount/master/_listings/eventbrite/eventsiddiscountsdiscount-id-post-openapi.md
- name: Eventbrite - Delete Events Discounts Discount
  x-api-slug: eventsiddiscountsdiscount-id-delete
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-delete-discounts-discount-id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discount/master/_listings/eventbrite/eventsiddiscountsdiscount-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discount/master/_listings/eventbrite/eventsiddiscountsdiscount-id-delete-openapi.md
- name: Eventbrite - Get Events Public Discounts Discount
  x-api-slug: eventsidpublic-discountsdiscount-id-get
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-get-discounts-discount-id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discount/master/_listings/eventbrite/eventsidpublic-discountsdiscount-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discount/master/_listings/eventbrite/eventsidpublic-discountsdiscount-id-get-openapi.md
- name: Eventbrite - Post Events Public Discounts Discount
  x-api-slug: eventsidpublic-discountsdiscount-id-post
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-post-discounts-discount-id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discount/master/_listings/eventbrite/eventsidpublic-discountsdiscount-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discount/master/_listings/eventbrite/eventsidpublic-discountsdiscount-id-post-openapi.md
- name: Eventbrite - Delete Events Public Discounts Discount
  x-api-slug: eventsidpublic-discountsdiscount-id-delete
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-delete-discounts-discount-id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discount/master/_listings/eventbrite/eventsidpublic-discountsdiscount-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discount/master/_listings/eventbrite/eventsidpublic-discountsdiscount-id-delete-openapi.md
x-common:
- type: x-api-gallery
  url: http://europeana.api.gallery.streamdata.io
- type: x-api-stack
  url: http://eventbrite.stack.network
- type: x-apigee-console
  url: https://api.apigee.com/v1/consoles/eventbrite/apidescription?format=internal&ver=1351170233000
- type: x-authentication
  url: https://developer.eventbrite.com/docs/auth/
- type: x-base
  url: https://www.eventbriteapi.com/
- type: x-blog
  url: http://blog.eventbrite.com/
- type: x-blog-rss
  url: http://blog.eventbrite.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/eventbrite
- type: x-crunchbase
  url: https://crunchbase.com/organization/eventbrite
- type: x-developer
  url: https://developer.eventbrite.com/
- type: x-github
  url: https://github.com/eventbrite
- type: x-pricing
  url: http://help.eventbrite.com/customer/en_us/portal/articles/428604
- type: x-privacy
  url: http://www.eventbrite.com/privacypolicy
- type: x-sdks-io
  url: https://sdks.io/SDK/View/eventbrite
- type: x-selfservice-registration
  url: https://www.eventbrite.com/signup/?referrer=%2F%3Fshow_onboarding%3D1&user_type=prebuyer&user_type_sig=AH_ElWGNJ_zHaAxwjzt5jiCRmvPvNBsy6w
- type: x-terms-of-service
  url: http://www.eventbrite.com/tos
- type: x-twitter
  url: https://twitter.com/EventbriteAPI
- type: x-twitter
  url: https://twitter.com/eventbrite
- type: x-website
  url: http://eventbriteapi.com
- type: x-website
  url: http://developer.eventbrite.com/
- type: x-website
  url: http://eventbrite.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---