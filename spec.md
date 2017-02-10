
## Hotel Result Spec


#### List Componenet

##### Spec

```html

   
   <hotel-result-list
          options = [[option]]
          default-view = "List"
          data = [[hotelList]]
          
          primary-amenities=[[primaryAmenities]]

          on-sort-change = "_partenComponentHandling"
          on-view-change = "_onViewChange"
           
          filter-state = {{filterState}}
           >   
   </hotel-result-list>

```


##### Data Attribute

```javascript

    // options
    options = {
        filterMessage : "We found {{count}} hotels for your search",

        pageSize : 10,

        sortAllowed : [ 
            { name:"Price", default: "true"},
            { name:"HotelName"},
            { name:"Star Rating"}
        ],

        enableListView : true,
        enableMapView : true,

        showReview : false,

        showRoomText : "See Available Rooms",
        
        primaryAmenities : [
            { name : "Bar", icon: "bar"},
            { name : "Restaurant", icon: "restaurant"},
            { name : "Wifi", icon : "wifi"},
            { name : "Parking", icon : "parking" }
        ]

    };

    // filter State
    filterState = [
        {
            name : "Price"
        },
        {
            name : "Rating"
        }
    ]

    hotelList =[

        {
            "id": "55610",
            "name": "THE WESTIN LAKE LAS VEGAS RESORT &amp; SPA",
            "rating": 5,
            "address": "101 MONTELAGO BOULEVARD  HENDERSON",
            "phoneNumber": "702 567 1234",
            "distance": 13.86,
            "description": "The luxury hotel radiates a Moroccan atmosphere and comprises a total of 493 rooms spread over 9 floors. Amongst the hotel's facilities count an air-conditioned lobby with a 24-hour reception desk, lift access, a hotel safe, a cloakroom and a currency exchange desk. Further amenities include a newspaper stand, a range of shops, a hairdressing salon, a casino, a kids' club, and free car parking spaces. Dining options include a cozy bar and a pleasing restaurant. Guests may also make use of the public Internet access in addition to the laundry and 24-hour room services. Self and valet parking, secure golf bag storage, concierge-assisted boarding passes, and intra-resort on-demand transportation are also offered.",
            "descriptions": [
                {
                    "key": "",
                    "value": "The luxury hotel radiates a Moroccan atmosphere and comprises a total of 493 rooms spread over 9 floors. Amongst the hotel's facilities count an air-conditioned lobby with a 24-hour reception desk, lift access, a hotel safe, a cloakroom and a currency exchange desk. Further amenities include a newspaper stand, a range of shops, a hairdressing salon, a casino, a kids' club, and free car parking spaces. Dining options include a cozy bar and a pleasing restaurant. Guests may also make use of the public Internet access in addition to the laundry and 24-hour room services. Self and valet parking, secure golf bag storage, concierge-assisted boarding passes, and intra-resort on-demand transportation are also offered."
                }
            ],
            "heroImageUrl": "http://d3mj096p5q0e20.cloudfront.net/ti/HBD/55610/043509a_hb_a_001.jpg",
            "geoCode": "36.113,-114.925",
            "amenities": [
                {
                    "type": "Hotel",
                    "description": "24h check-in"
                },
                {
                    "type": "Hotel",
                    "description": "24h. Reception"
                },
                {
                    "type": "Room",
                    "description": "Air-conditioned in common areas"
                },
                {
                    "type": "Hotel",
                    "description": "American Express"
                },
                {
                    "type": "Hotel",
                    "description": "Bar-s"
                },
                {
                    "type": "Room",
                    "description": "Bath"
                },
            ],
             "photoUrls": [
                "http://d3mj096p5q0e20.cloudfront.net/fi/HBD/55610/043509a_hb_f_004.jpg",
                "http://d3mj096p5q0e20.cloudfront.net/fi/HBD/55610/043509a_hb_f_006.jpg",
                "http://d3mj096p5q0e20.cloudfront.net/fi/HBD/55610/043509a_hb_f_007.jpg",
                "http://d3mj096p5q0e20.cloudfront.net/fi/HBD/55610/043509a_hb_w_002.jpg",
                "http://d3mj096p5q0e20.cloudfront.net/fi/HBD/55610/043509a_hb_p_003.jpg",
                "http://d3mj096p5q0e20.cloudfront.net/fi/HBD/55610/043509a_hb_r_005.jpg"
            ],
            "pointsOfInterest": [],
            "minFare": {
                "areRatesAvailable": true,
                "fare": {
                    "amount": 165.3,
                    "currency": "USD",
                    "displayAmount": "USD 165.30"
                },
                "equivalentFares": null,
                "equivalents": null
            },
            "rooms": null,
            "isCancellable": true,
            "allPassengersInfoRequired": false,
            "isGuaranteeRequired": true,
            "fare": {
                "type": "Published",
                "code": null,
                "isRefundable": false,
                "components": [
                    {
                        "money": {
                            "amount": 4108.86,
                            "currency": "USD",
                            "displayAmount": "USD 4,108.86"
                        },
                        "components": null,
                        "type": "BaseFare",
                        "properties": []
                    },
                    {
                        "money": {
                            "amount": 4578.42,
                            "currency": "USD",
                            "displayAmount": "USD 4,578.42"
                        },
                        "components": null,
                        "type": "TotalFare",
                        "properties": []
                    },
                    {
                        "money": {
                            "amount": 127.72,
                            "currency": "USD",
                            "displayAmount": "USD 127.72"
                        },
                        "components": null,
                        "type": "TotalFee",
                        "properties": []
                    },
                    {
                        "money": {
                            "amount": 421.84,
                            "currency": "USD",
                            "displayAmount": "USD 421.84"
                        },
                        "components": null,
                        "type": "TotalTax",
                        "properties": []
                    },
                    {
                        "money": {
                            "amount": 80,
                            "currency": "USD",
                            "displayAmount": "USD 80.00"
                        },
                        "components": null,
                        "type": "TotalDiscount",
                        "properties": []
                    }
                ],
            },
            "isPostPaid": false,
            "isSoldOut": false,
            "isPreferred": false,
            "source": {
                "inventoryId": "55610",
                "id": 111,
                "name": "HotelBeds Test"
            },

            userRating : "3.4",
            userReviewCount : 500
            reviewType : "Excellent"
            
        },


        {
            "rating": 5,
            "address": "221 N. RAMPART BLVD  LAS VEGAS",
            "phoneNumber": "702-869-7777",
            "distance": 7.74,
            "description": "This is a superb casino resort with no booking restrictions. It features a swimming lagoon with private cabanas and a full-service spa. It has a glamorous casino, as well as 7 restaurants and bars. The hotel consists of 531 beautifully-appointed guest rooms with very upscale amenities. Further facilities include air conditioning, Internet access, room and laundry services, as well as a car park and garage for those arriving by car.",
            "descriptions": [
                {
                    "key": "",
                    "value": "This is a superb casino resort with no booking restrictions. It features a swimming lagoon with private cabanas and a full-service spa. It has a glamorous casino, as well as 7 restaurants and bars. The hotel consists of 531 beautifully-appointed guest rooms with very upscale amenities. Further facilities include air conditioning, Internet access, room and laundry services, as well as a car park and garage for those arriving by car."
                }
            ],
            "heroImageUrl": "http://d3mj096p5q0e20.cloudfront.net/ti/HBD/55880/041786_hb_a_001.jpg",
            "geoCode": "36.1759,-115.2872",
            "amenities": [
                {
                    "type": "Room",
                    "description": "Air-conditioned in common areas"
                },
                {
                    "type": "Room",
                    "description": "Balcony"
                },
                {
                    "type": "Hotel",
                    "description": "Bar-s"
                },
                {
                    "type": "Room",
                    "description": "Bathroom"
                },
                {
                    "type": "Hotel",
                    "description": "Vehicle Parking"
                },
                {
                    "type": "Room",
                    "description": "Central air-conditioned"
                },
                {
                    "type": "Hotel",
                    "description": "Central heating"
                },
                {
                    "type": "Room",
                    "description": "Direct dial telephone"
                },
                {
                    "type": "Hotel",
                    "description": "Fresh water pool"
                },
                {
                    "type": "Hotel",
                    "description": "Garage"
                },
                {
                    "type": "Hotel",
                    "description": "Fitness Facility"
                },
                {
                    "type": "Room",
                    "description": "Hairdryer"
                },
                {
                    "type": "Hotel",
                    "description": "Heated pool"
                },
                {
                    "type": "Hotel",
                    "description": "Indoor pool"
                },
                {
                    "type": "Room",
                    "description": "Internet"
                },
                {
                    "type": "Hotel",
                    "description": "Laundry service"
                },
                {
                    "type": "Hotel",
                    "description": "Number of floors (main building)"
                },
                {
                    "type": "Room",
                    "description": "Internet"
                },
                {
                    "type": "Hotel",
                    "description": "Restaurant"
                },
                {
                    "type": "Hotel",
                    "description": "Restaurant"
                },
                {
                    "type": "Room",
                    "description": "Room service"
                },
                {
                    "type": "Room",
                    "description": "Safe"
                },
                {
                    "type": "Hotel",
                    "description": "Sauna"
                },
                {
                    "type": "Hotel",
                    "description": "Suites"
                },
                {
                    "type": "Hotel",
                    "description": "Total number of rooms"
                },
                {
                    "type": "Hotel",
                    "description": "Year of construction"
                }
            ],
            "photoUrls": [
                "http://d3mj096p5q0e20.cloudfront.net/fi/HBD/55880/041786_hb_w_002.jpg"
            ],
            "pointsOfInterest": [],
            "minFare": {
                "areRatesAvailable": true,
                "fare": {
                    "amount": 235.28,
                    "currency": "USD",
                    "displayAmount": "USD 235.28"
                },
                "equivalentFares": null,
                "equivalents": null
            },
            "rooms": null,
            "brand": {
                "code": "MARIO",
                "name": "MARRIOTT HOTELS AND RESORTS",
                "logo": null
            },
            "type": "Hotel",
            "moreRoomsAvailable": true,
            "brandAvailablility": true,
            "deal": null,
            "isCancellable": true,
            "allPassengersInfoRequired": false,
            "isGuaranteeRequired": true,
            "id": "55880",
            "name": "JW Marriott Resort &amp; Casino",
            "fare": {
                "type": "Negotiated",
                "code": null,
                "isRefundable": false,
                "components": [
                    {
                        "money": {
                            "amount": 787.28,
                            "currency": "USD",
                            "displayAmount": "USD 787.28"
                        },
                        "components": null,
                        "type": "BaseFare",
                        "properties": []
                    },
                    {
                        "money": {
                            "amount": 867.34,
                            "currency": "USD",
                            "displayAmount": "USD 867.34"
                        },
                        "components": null,
                        "type": "TotalFare",
                        "properties": []
                    },
                    {
                        "money": {
                            "amount": 0,
                            "currency": "USD",
                            "displayAmount": "USD 0.00"
                        },
                        "components": null,
                        "type": "TotalFee",
                        "properties": []
                    },
                    {
                        "money": {
                            "amount": 80.06,
                            "currency": "USD",
                            "displayAmount": "USD 80.06"
                        },
                        "components": null,
                        "type": "TotalTax",
                        "properties": []
                    },
                    {
                        "money": {
                            "amount": 0,
                            "currency": "USD",
                            "displayAmount": "USD 0.00"
                        },
                        "components": null,
                        "type": "TotalDiscount",
                        "properties": []
                    }
                ],
                "equivalents": null
            },
           
            "isPostPaid": false,
            "isSoldOut": false,
            "isPreferred": false,
            "preferredSortOrder": 0,
            "source": {
                "inventoryId": "55880",
                "id": 111,
                "name": "HotelBeds Test"
            },
            "restrictions": null
        }

    ]

```

## Important Information
- In case no thumpnail image available for hotel, show default image available here - 
- Hotel lengthy name max will come in 2 lines, after that start display like "Hotel casino..."
- Hotel address lengthy name will remain in 1 line only and after that .....
- Hotel aminities max can be 7 only. (and need to display icons those are available in hotel property)
- On hover on particular itinerary under line the hotel name and fill color in "See available rooms" button.
- In case of rooms count less that 3, start showing "We have xyz left at USD 123" in red.
- Default sorting will set on Price (ascending order)

## Test Cases
-

## Steps to Start
- Set Github repository at your end for this project, we will merge them later
- You can use Google/Vaadin's elements (like calender element and textboxes etc.)
- You can use some Tavisca's elements like auto-suggest if required from https://github.com/atomelements/t-autosuggest but all the features and properties mentioned in scope should be added. (Fork the existing element and create V2)
- APIs Integration - Use Tavisca's APIs for integration purpose.

## Performance standard
- Any component if opened via [web page tester](https://www.webpagetest.org/), it should load under 500ms (milli seconds).

## Documents
- Visual designs for search components - https://projects.invisionapp.com/share/6E9PJ7R4Q#/screens/212067485
- API access : Url - http://demo.travelnxt.com/dev
- Tavisca Elements - https://github.com/atomelements and https://github.com/travelnxtelements
- Vaadin elements - https://vaadin.com/docs/-/part/elements/elements-getting-started.html
- Google - https://elements.polymer-project.org/browse?package=google-web-components
- Tavisca Web component style Guide - https://drive.google.com/open?id=0B7BT_2nBFNYVR2tscE9pRnVJYmc
