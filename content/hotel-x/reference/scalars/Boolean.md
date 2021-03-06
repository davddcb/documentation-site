{
  "title": "Boolean",
  "description": "",
  "weight": 1,
  "fields": null,
  "requireby": [
    {
      "name": "HotelSettingsInput",
      "description": "Settings that you can edit for this avail. Values are loaded by default in our Back Office.",
      "url": "/hotel-x/reference/inputobjects/hotelsettingsinput"
    },
    {
      "name": "PageInfo",
      "description": "",
      "url": "/hotel-x/reference/objects/pageinfo"
    },
    {
      "name": "HotelData",
      "description": "Hotel data",
      "url": "/hotel-x/reference/objects/hoteldata"
    },
    {
      "name": "DestinationData",
      "description": "Information about destinantion",
      "url": "/hotel-x/reference/objects/destinationdata"
    },
    {
      "name": "SettingsBaseInput",
      "description": "Contains the time out and business rules of a supplier or an access.",
      "url": "/hotel-x/reference/inputobjects/settingsbaseinput"
    },
    {
      "name": "Room",
      "description": "Contains the room information of the option returned.",
      "url": "/hotel-x/reference/objects/room"
    },
    {
      "name": "Price",
      "description": "Price indicates the value of the room/option.\nSupplements and/or surcharges can be included into the price, and will be verified with nodes Supplements/Surcharges.",
      "url": "/hotel-x/reference/objects/price"
    },
    {
      "name": "Supplement",
      "description": "Supplement that it can be or its already added to the option returned. Contains all the information about the supplement.",
      "url": "/hotel-x/reference/objects/supplement"
    },
    {
      "name": "Surcharge",
      "description": "Surcharge that it can be or it is already added to the option returned. Contains all the information about the surcharge.",
      "url": "/hotel-x/reference/objects/surcharge"
    },
    {
      "name": "CancelPolicy",
      "description": "Information about a policy cancellation.",
      "url": "/hotel-x/reference/objects/cancelpolicy"
    },
    {
      "name": "Bed",
      "description": "Contains information about a bed.",
      "url": "/hotel-x/reference/objects/bed"
    },
    {
      "name": "Markup",
      "description": "Informs markup applied over supplier price.",
      "url": "/hotel-x/reference/objects/markup"
    },
    {
      "name": "Priceable",
      "description": "",
      "url": "/hotel-x/reference/interfaces/priceable"
    },
    {
      "name": "HotelRuntimeParameter",
      "description": "template of all fields used by the supplier",
      "url": "/hotel-x/reference/objects/hotelruntimeparameter"
    },
    {
      "name": "HotelXUpdateStatusData",
      "description": "",
      "url": "/hotel-x/reference/objects/hotelxupdatestatusdata"
    },
    {
      "name": "HotelXAuditInput",
      "description": "",
      "url": "/hotel-x/reference/inputobjects/hotelxauditinput"
    },
    {
      "name": "DeltaPriceInput",
      "description": "Input delta price, indicates price variation permitted by the client\nAn error will be returned if the new price does not abide to DeltaPrice. If DeltaPrice is not sent and the integration implements it, we assume that the price range is 0 and the process will continue \n(price is lower or equal to the price showed in valuation).\nThis field is implemented if it’s native to the supplier or if another availability/valuation request needs to be done in Reservation. In case the supplier blocks the option in valuation, reservation \nwill be done automatically in reservation method.",
      "url": "/hotel-x/reference/inputobjects/deltapriceinput"
    }
  ],
  "enumValues": null,
  "operator": "scalar",
  "typename": "Boolean",
  "hideGithubLink": true
}
The `Boolean` scalar type represents `true` or `false`.
## GraphQL schema definition

{{% graphql-schema-scalar %}}

## Required by

{{% graphql-require-by %}}
