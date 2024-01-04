# Chosen payment processing method

## Context
How the user payments will be processed within the system

## Decision
This system will use a PSP (payment service provider) such as paypal and stripe to process the payments over building a payment service from scratch. 

### Other Options
We would have to look into building a payment service specifically for this system due to the demand of visa applications
- It could be made asyncronous using Kafka (https://www.youtube.com/watch?v=olfaBgJrUBI, https://www.youtube.com/watch?v=zsD4R_aQctw)
- The payment service could be self-hosted (https://www.merchantsavvy.co.uk/payment-gateways/)

## Consequences
- Less time consuming
- High demand may prove less cost effective in the long run

## Status
Accepted
