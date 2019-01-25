[Home](home.md) | [Getting Started](getting-started.md) | [Documentation](docs-air.md) | [Guides](guides-air.md) | [Updates](updates.md) | [Support](support.md)

# Guides

[Air](guides-air.md) | [Hotel](guides-hotel.md) | [Car Rentals](guides-car.md) 

------------

## Air

### Booking Flows

Get familiar with the proper booking flow for your site and where to use our API data.

#### Flight Search Flow

1. [Destination AutoComplete](#docs)  
Provide a list of suggested cities or airports based on the user's search input
2. [Departure Flights](#docs) / [Flight Combined](#docs)  
Get a list of departure flights available / combine departure and return flights 
3. [Return Flights](#docs) / [Flight Combined](#docs)  
Get a list of return flights available / combine departure and return flights

#### Contract and Booking Flow

1. [Flight Contract](#docs)  
Return the selected flight itinerary including price and connection info
2. [Flight Seat Map](#docs) (optional)  
Returns a matrix to render a seat map 
3. [Flight Book](#docs)  
Submits the flight booking reservation

#### Post Sale Functions

- [Flight Lookup](#docs)  
Returns the itinerary and price details for the selected flight
- [Flight Seat Update](#docs)  
Sends a request to update a customers seat selection
- [Resend Itinerary Request](#docs)  
Submits a request to resend the itinerary email
- [Flight Void Request](#docs)  
Submits a request to cancel a flight reservation
- [Flight Lost Offer Request](#docs)  
Returns booking information for an email and date range

