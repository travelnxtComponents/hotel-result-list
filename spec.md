
## Hotel Result Spec


#### List Componenet

##### Spec

```html

   
   <hotel-result-list
          options = [[listOption]]
          page-size = "10"
          data = [[hotelList]]
          enable-review = false
          primary-amenities=[[primaryAmenities]]
           >   
   </hotel-result-list>

```


##### Data

```javascript

    primaryAmenities = [
            "Bar",
            "Restaurant",
            "Wifi",
            "Parking"
    ];

    list =[

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
            
        }

    ]

```
