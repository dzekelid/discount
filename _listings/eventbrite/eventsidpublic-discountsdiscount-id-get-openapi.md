---
swagger: "2.0"
x-collection-name: Eventbrite
x-complete: 0
info:
  title: Eventbrite Get Events Public Discounts Discount
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-get-discounts-discount-id
  version: 1.0.0
host: www.eventbrite.com
basePath: /%7Bdata-type%7D/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /discount_new:
    get:
      summary: Get Discount New
      description: This method creates a new discount code for a specific event. It
        returns the ID of the newly created discount code.
      operationId: Get_discount_new_
      x-api-path-slug: discount-new-get
      parameters:
      - in: query
        name: amount_off
        description: The fixed amount off the ticket price
      - in: query
        name: code
        description: The discount code
      - in: query
        name: data-type
        description: xml or json data-types are supported
      - in: query
        name: end_date
        description: The discount end date and time, in ISO 8601 format (e
      - in: query
        name: event_id
        description: The event ID
      - in: query
        name: percent_off
        description: The percentage off the ticket price
      - in: query
        name: quantity_available
        description: Maximum number of times this discount can be used
      - in: query
        name: start_date
        description: The discount start date and time, in ISO 8601 format (e
      - in: query
        name: tickets
        description: Comma-separated list of ticket IDs for which the discount applies
      responses:
        200:
          description: OK
      tags:
      - Discount
      - New
  /discount_update:
    get:
      summary: Get Discount Update
      description: This method is used to update an existing discount code. Only the
        fields passed as arguments will be modified. This method returns the ID of
        the modified discount code.
      operationId: Get_discount_update_
      x-api-path-slug: discount-update-get
      parameters:
      - in: query
        name: amount_off
        description: The fixed amount off the ticket price
      - in: query
        name: code
        description: The discount code
      - in: query
        name: data-type
        description: xml or json data-types are supported
      - in: query
        name: end_date
        description: The discount end date and time, in ISO 8601 format (e
      - in: query
        name: id
        description: The discount ID to update
      - in: query
        name: percent_off
        description: The percentage off the ticket price
      - in: query
        name: quantity_available
        description: Maximum number of times this discount can be used
      - in: query
        name: start_date
        description: The discount start date and time, in ISO 8601 format (e
      - in: query
        name: tickets
        description: Comma-separated list of ticket IDs for which the discount applies
      responses:
        200:
          description: OK
      tags:
      - Discount
      - Update
  /discounts/:discount_id/:
    get:
      summary: Get Discounts Discount
      description: Returns the cross_event_discount with the specified :discount_id.
      operationId: getDiscountsDiscount
      x-api-path-slug: discountsdiscount-id-get
      responses:
        200:
          description: OK
      tags:
      - Discounts
      - :discount
    post:
      summary: Post Discounts Discount
      description: Updates the discount with the specified :discount_id. Returns the
        updated cross_event_discount. The fields sent are the ones that are going
        to be updated, the fields that are not sent will be unchanged. The same conditions
        and notes for the discount creation apply.
      operationId: postDiscountsDiscount
      x-api-path-slug: discountsdiscount-id-post
      parameters:
      - in: query
        name: discount.amount_off
        description: Fixed reduction amount
        type: query
      - in: query
        name: discount.code
        description: Code used to activate discount
        type: query
      - in: query
        name: discount.end_date
        description: Allow use until this date
        type: query
      - in: query
        name: discount.end_date_relative
        description: Allow use until this number of seconds before the event starts
        type: query
      - in: query
        name: discount.hold_ids
        description: IDs of holds this discount can unlock
        type: query
      - in: query
        name: discount.percent_off
        description: Percentage reduction
        type: query
      - in: query
        name: discount.quantity_available
        description: Number of discount uses
        type: query
      - in: query
        name: discount.start_date
        description: Allow use from this date
        type: query
      - in: query
        name: discount.start_date_relative
        description: Allow use from this number of seconds before the event starts
        type: query
      - in: query
        name: discount.ticket_class_ids
        description: IDs of tickets to limit discount to
        type: query
      responses:
        200:
          description: OK
      tags:
      - Discounts
      - :discount
    delete:
      summary: Delete Discounts Discount
      description: |-
        Deletes the cross_event_discount with the specified :discount_id.
        Only unused discounts can be deleted.
      operationId: deleteDiscountsDiscount
      x-api-path-slug: discountsdiscount-id-delete
      responses:
        200:
          description: OK
      tags:
      - Discounts
      - :discount
  /events/{id}/discounts/:discount_id/:
    get:
      summary: Get Events Discounts Discount
      description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-get-discounts-discount-id
      operationId: getEventsDiscountsDiscount
      x-api-path-slug: eventsiddiscountsdiscount-id-get
      responses:
        200:
          description: OK
      tags:
      - Events
      - Discounts
      - :discount
    post:
      summary: Post Events Discounts Discount
      description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-post-discounts-discount-id
      operationId: postEventsDiscountsDiscount
      x-api-path-slug: eventsiddiscountsdiscount-id-post
      responses:
        200:
          description: OK
      tags:
      - Events
      - Discounts
      - :discount
    delete:
      summary: Delete Events Discounts Discount
      description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-delete-discounts-discount-id
      operationId: deleteEventsDiscountsDiscount
      x-api-path-slug: eventsiddiscountsdiscount-id-delete
      responses:
        200:
          description: OK
      tags:
      - Events
      - Discounts
      - :discount
  /events/{id}/public_discounts/:discount_id/:
    get:
      summary: Get Events Public Discounts Discount
      description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-get-discounts-discount-id
      operationId: getEventsPublicDiscountsDiscount
      x-api-path-slug: eventsidpublic-discountsdiscount-id-get
      responses:
        200:
          description: OK
      tags:
      - Events
      - Public
      - Discounts
      - :discount
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---