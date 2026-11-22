# Smart India Hackathon Workshop
# Date:22/11/2026
## Reference Number:26008446
## Name:A JOHN RYAN

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description

Multiple intermediaries between farmers and buyers can reduce producer price realization and increase consumer prices. The brief calls for a digital marketplace connecting farmers/FPOs with consumers and bulk buyers, logistics support, and AI-based demand forecasting and route optimization.

## Proposed Solution

KisanSetu Direct is a farmer-first marketplace for transparent produce listings, pooled demand, coordinated logistics, and traceable order fulfillment.

## Workflow 

1. Farmers/FPOs register crops, quantity, quality grade, harvest window, location, and minimum acceptable net price.
2. Buyers (consumers, retailers, hotels, institutions) browse listings or post demand.
3. The platform matches by crop, grade, quantity, location, and freshness window.
4. Compatible orders are pooled into buyer-ready lots; farmers see buyer price, logistics costs, and any platform fee separately.
5. Farmers accept or reject offers. A price-floor alert flags offers below their chosen minimum net price.
6. FPO collection points aggregate produce. Logistics planning accounts for vehicle capacity, distance, time windows, and perishability.
7. Orders track accepted, aggregated, picked up, delivered, and settled states. Proof of delivery and dispute handling improve trust.
8. Demand forecasting estimates crop/region demand using transaction history and seasonality; forecast confidence is shown. change diffenerntly with same content

## How it addresses the problem

    * Establishes a direct connection between agricultural producers and buyers, minimizing dependence on        traditional middlemen.
    * Combines produce from multiple small-scale farmers to meet large-volume purchasing requirements.
    * Provides clear pricing details, allowing farmers to understand their actual earnings after                 deductions.
    * Uses advance market-demand insights to support better crop planning and minimize excess production.
    * Organizes shared transportation and bulk deliveries to lower shipping expenses and minimize post-          harvest losses. 

## Innovation and uniqueness of the solution

*Smart Freshness-Based Matching: Matches agricultural products according to harvesting schedules, freshness levels, and delivery deadlines.

*FPO-Based Bulk Collection: Brings together produce from small and marginal farmers through FPO centres to fulfill large institutional requirements.

*Intelligent Recommendation System: Suggests suitable buyers and transportation routes by evaluating quantity, distance, vehicle availability, product freshness, and delivery time.

*Farmer Price Protection: Allows farmers to set their own minimum expected earnings and prevents acceptance of offers below their chosen price limit.

*Accessible Digital Platform: Offers a mobile-friendly interface with regional language support, simple onboarding assistance, and smooth operation on low-speed internet connections.

*Food Waste Reduction System: Gives priority to agricultural lots nearing their freshness deadlines to ensure faster distribution and reduce post-harvest wastage.

## Technical Approach

A modular MVP web app with REST APIs, PostgreSQL data storage, deterministic matching, and an optimization service. ML complexity grows only after sufficient reliable data is collected.

## Proposed stack

1. Frontend: React and TypeScript for a responsive mobile-friendly application.
2. Backend: Python FastAPI for server-side operations and REST APIs.
3. Database: PostgreSQL with PostGIS for storing data and location-based searches.
4. Forecasting: Python, Pandas, and Scikit-learn for predicting crop demand.
5. Routing: Google OR-Tools for optimizing delivery routes and vehicle capacity.
6. Authentication: Secure role-based access for farmers, buyers, FPOs, and logistics users.
7. Notifications: SMS, email, and push notifications for alerts and updates.
8. Deployment: Docker, cloud hosting, TLS security, database backups, and monitoring.

##Architecture diagram

<img width="1088" height="1280" alt="image" src="https://github.com/user-attachments/assets/f1a92ed2-c164-42fe-84fb-5e467419af7c" />



## Implementation Process:

1. Database Design: Create data structures for users, crops, quality grades, units, listings, buyer requests, orders, vehicles, routes, and payments.
2. User Interface Development: Build registration, farmer onboarding, crop listing, product search, and filtering features.
3. Order Management: Develop price offers, order confirmation, stock reservation, and order status tracking.
4. Order Pooling: Combine suitable orders based on crop type, quality, location, and delivery schedule.
5. Logistics Planning: Generate efficient delivery routes based on vehicle capacity and delivery time limits.
6. Demand Forecasting: Integrate basic forecasting models with prediction periods and confidence levels.
7. System Testing: Test user permissions, stock availability, invalid quantities, cancellations, disputes, and delivery problems.
8. Pilot Launch: Test the platform with selected FPOs and buyers, then evaluate performance using
collected data and measurable results.

## Order and logistics sequence

<img width="1280" height="793" alt="image" src="https://github.com/user-attachments/assets/1f17c664-d0fa-4d21-a9f5-5d4ea7e0e6ae" />



## Feasibility and Viability


1. Crop Listing: Farmers can easily register and publish crop details through the web application.
2. Platform Development: User registration, product listings, order management, and access control use well-established web technologies.
3. Smart Matching: The system can match farmers and buyers based on crop, quantity, quality, and location.
4. Route Optimization: Available routing tools support vehicle capacity and delivery time constraints.
5. Demand Forecasting: Basic forecasting is possible using historical sales and seasonal data.
6. Future Integration: Payment gateways, market prices, and transportation services can be added gradually through modular development.

## Risks and Mitigation

- Insufficient Data: Start with basic forecasting and improve it as data grows.
- Network Issues: Provide a lightweight, mobile-friendly application.
- Delivery Delays: Use route optimization and alternative delivery plans.
- Data Security: Apply secure authentication and access controls.
- Low User Adoption: Provide local-language support and simple onboarding.

<img width="1280" height="793" alt="image" src="https://github.com/user-attachments/assets/3da2bebc-f434-4c1e-a7a3-e1023cb333b8" />

## Viability

Potential revenue: transparent transaction fee, optional logistics coordination fee, or institutional buyer subscription. Pilot unit economics must be validated and fees must be disclosed before farmer acceptance.

## Impact and Benefits

## Target audience

* Small and marginal farmers
* Farmer Producer Organizations (FPOs)
* Individual consumers and retailers
* Hotels and institutional purchasers
* Transportation and logistics providers
  
## Expected Impact
       * Helps farmers achieve better selling prices.
       * Improves price transparency between buyers and sellers.
       * Reduces transportation costs through combined deliveries.
## Social Impact
* Provides wider market opportunities for small farmers.
* Supports regional languages and assisted registration.
Environmental Impact.
* Reduces unnecessary transportation trips.
* Minimizes food wastage through freshness-based matching.
## Operational Impact
* Improves order tracking and delivery transparency.
* Helps farmers plan harvesting using demand forecasts.
  give 10 lines

## Benefits

1.Helps farmers receive better prices for their produce.
2.Provides transparent price comparisons for buyers and farmers.
3.Reduces transportation costs through bulk deliveries.
4.Connects small farmers with wider markets.
5.Supports regional languages and easy platform access.
6.Reduces unnecessary transportation trips.
7.Minimizes food wastage through freshness-based matching.
8.Improves transparency through real-time order tracking.
9.Helps farmers plan harvesting using demand forecasts.
10.Creates an efficient and sustainable agricultural supply chain.


## Research and References

1. SIH-26033 workshop problem brief, Ministry of Consumer Affairs, Food & Public Distribution.
2. FAO, The State of Food and Agriculture: https://www.fao.org/publications/sofa/
3. FAO, Food Loss and Food Waste: https://www.fao.org/food-loss-and-food-waste/
4. Government of India e-NAM: https://www.enam.gov.in/
5. Google OR-Tools optimization: https://developers.google.com/optimization
6. PostGIS: https://postgis.net/ 7. scikit-learn: https://scikit-learn.org/stable/
