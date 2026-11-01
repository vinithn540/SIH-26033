# Smart India Hackathon Workshop
# Date:1/11/2026
## Reference Number:26018378
## Name:Vinith.R

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
Detailed Explanation of the Proposed Solution

HarvestLoop AI is a digital agricultural procurement platform designed to reduce unnecessary intermediaries between farmers and consumers. Unlike conventional marketplaces, where farmers list products and wait for buyers, HarvestLoop AI allows buyers to publish their agricultural requirements in advance.

The platform combines requirements from hostels, restaurants, retailers, supermarkets, and other bulk buyers. It identifies suitable farmers and FPOs, consolidates available produce, and recommends suitable supplier combinations based on quantity, price, quality, location, and delivery requirements.

The system also incorporates AI-based demand forecasting, surplus produce matching, farmer earnings calculations, and shared logistics optimization. Farmers can view their estimated net earnings before accepting an order, while buyers can compare supplier offers and delivery costs.

The platform aims to establish a transparent, efficient, and accessible agricultural supply chain that benefits farmers and consumers.

How It Addresses the Problem

Reduces intermediaries: Establishes direct connections between farmers and buyers.

Improves farmer earnings: Helps farmers compare selling options based on estimated net earnings after expenses.

Reduces consumer costs: Identifies opportunities to reduce avoidable commissions and transportation expenses.

Combines small quantities: Enables multiple farmers to fulfill large orders collectively.

Reduces food waste: Connects surplus produce with potential alternative buyers.

Improves transportation: Groups compatible orders and optimizes collection and delivery routes.

Improves market planning: Uses buyer requirements and historical data to estimate agricultural demand.

Increases transparency: Provides clear product quantities, prices, expenses, and order status.

Innovation and Uniqueness of the Solution

1. Agricultural Demand Bank

A centralized system where buyers publish upcoming agricultural requirements. The platform aggregates demand from multiple buyers and allows farmers to submit suitable supply offers.

2. Multi-Farmer Order Allocation

The platform combines produce from multiple small farmers to fulfill bulk orders based on availability, quality, price, and delivery constraints.

3. FairDeal Earnings Calculator

Calculates estimated farmer earnings after deducting transportation, packaging, platform fees, and other applicable expenses. Farmers can compare alternative selling options before accepting orders.

4. Crop Rescue System

Identifies unsold or surplus produce and recommends potential alternative buyers based on location, quantity, freshness, and purchasing requirements.

5. SharedRoute Optimization

Coordinates collections from multiple farms and deliveries to compatible buyers, considering distance, vehicle capacity, delivery deadlines, and product perishability.

6. AI-Based Demand Forecasting

Uses historical transactions, seasonal patterns, market information, and buyer requests to estimate future demand and support informed agricultural planning.

These features form a coordinated procurement system rather than simply providing an online product-listing marketplace.

## Technical Approach
Technologies to Be Used

Component

Proposed Technology

Purpose

Mobile application

Flutter

Farmer and buyer access

Web application

React.js

Marketplace and administrative dashboards

Backend

Python with FastAPI

Application logic and API development

Database

PostgreSQL

Store farmer, buyer, inventory, and order information

Machine learning

Python, Scikit-learn

Demand forecasting and price analysis

Order allocation

Python optimization algorithms

Allocate orders across multiple farmers

Route optimization

Google OR-Tools

Optimize collection and delivery routes

Mapping

OpenStreetMap and Leaflet

Display farms, buyers, and routes

Authentication

Secure authentication with role-based access

Protect user accounts and information

Notifications

Firebase Cloud Messaging

Provide order and delivery updates

Digital payments

UPI-compatible payment gateway

Support digital transactions

Methodology and Process for Implementation

Step 1: User Registration

Farmers, FPOs, buyers, and transport providers register and provide the required information.

Step 2: Demand Registration

Buyers enter the products, quantities, expected delivery dates, quality requirements, and preferred price ranges.

Step 3: Farmer Supply Registration

Farmers list available produce, quantities, prices, locations, harvest dates, and relevant quality details.

Step 4: Demand Aggregation

The system combines compatible requirements from different buyers to identify bulk purchasing opportunities.

Step 5: Intelligent Supply Matching

The platform identifies suitable farmers and FPOs based on product availability, quantity, price, location, and delivery requirements.

Step 6: Farmer Earnings Calculation

The FairDeal module calculates expected net earnings after applicable expenses and allows farmers to review offers.

Step 7: Order Confirmation

Buyers and farmers confirm the quantities, prices, quality requirements, payment terms, and delivery arrangements.

Step 8: Logistics Optimization

The platform groups compatible orders and recommends efficient collection and delivery routes.

Step 9: Delivery and Payment

The system updates order status and records delivery completion and payment information.

Step 10: Performance Analysis

The platform evaluates transaction costs, farmer earnings, order fulfillment, and delivery efficiency to improve future recommendations.

System Workflow

BUYERS REGISTER REQUIREMENTS
↓
AGRICULTURAL DEMAND BANK
↓
AGGREGATE BUYER REQUIREMENTS
↓
MATCH WITH FARMERS AND FPOS
↓
ALLOCATE ORDERS ACROSS FARMS
↓
CALCULATE FARMER NET EARNINGS
↓
CONFIRM ORDERS
↓
OPTIMIZE SHARED DELIVERY ROUTES
↓
TRANSPORT AND DELIVER PRODUCE
↓
RECORD RESULTS AND IMPROVE FORECASTS

Working Prototype

The initial prototype will demonstrate:

Farmer and buyer registration.

Product listings and buyer demand registration.

Agricultural Demand Bank dashboard.

Multi-farmer order allocation.

Farmer earnings comparison.

Basic surplus produce matching.

Map-based delivery route visualization.

Order tracking and transaction records.

Dashboard showing supply, demand, completed orders, and estimated savings.

The first version can use sample agricultural data to demonstrate the workflow. Forecasting and cost-saving claims will be validated against appropriate data before real-world deployment.

## Feasibility and Viability
Analysis of the Feasibility of the Idea

HarvestLoop AI is technically feasible using existing mobile development frameworks, web technologies, databases, mapping services, and optimization algorithms.

The project can initially be implemented in one agricultural region with a limited number of farmers, FPOs, and institutional buyers. This pilot approach will allow the team to evaluate the procurement workflow before expanding to additional locations.

The platform does not require the team to own farms, warehouses, or delivery vehicles. Instead, it can coordinate existing agricultural suppliers and logistics providers.

The initial version can use rule-based supply matching and route optimization, while AI-based demand forecasting can be introduced progressively as reliable transaction data becomes available.

Potential revenue sources include transparent transaction fees, logistics coordination fees, and optional procurement management services for institutional buyers.

Potential Challenges and Risks

Challenge

Proposed Mitigation

Limited digital literacy

Provide a simple interface, regional-language support, and farmer training

Insufficient historical data

Begin with rule-based forecasts and progressively incorporate verified data

Inconsistent product quality

Use clear quality specifications and optional verification

Fluctuating agricultural supply

Update inventory regularly and allow partial order fulfillment

High transportation costs

Group compatible orders and optimize collection routes

Limited farmer participation

Partner with FPOs, cooperatives, and local agricultural organizations

Payment disputes

Define payment, cancellation, refund, and dispute-resolution procedures

Data security concerns

Use secure authentication, access controls, and appropriate encryption

Buyer demand uncertainty

Separate confirmed orders from predicted demand

Delivery delays

Consider product perishability, delivery deadlines, and contingency arrangements

Strategies for Overcoming These Challenges

Conduct a pilot with selected farmers and institutional buyers.

Partner with FPOs and local agricultural organizations to improve adoption.

Use reliable historical market information and actual transaction records.

Provide transparent price calculations and transaction histories.

Establish partnerships with existing logistics providers.

Introduce demand forecasting only after sufficient suitable data is available.

Collect feedback from farmers and buyers to improve the platform.

Expand to new regions after evaluating pilot performance.


## Impact and Benefits
Potential Impact on the Target Audience

Farmers and FPOs

Direct access to institutional and retail buyers.

Opportunities to negotiate better selling terms.

Ability to combine produce with other farmers to fulfill bulk orders.

Improved visibility into upcoming demand.

Better understanding of net earnings after expenses.

Consumers and Institutional Buyers

Potentially lower procurement costs.

More transparent supplier comparisons.

Easier access to agricultural produce.

Improved procurement planning.

Better visibility into order status and delivery arrangements.

Transport Providers

Additional delivery opportunities.

Better vehicle utilization.

Potential reduction in unnecessary travel.

More coordinated agricultural collections and deliveries.

Social, Economic, and Environmental Benefits

Impact Area

Expected Benefit

Economic

Potential improvement in farmer margins and reduced avoidable supply-chain costs

Social

Better market access for small and marginal farmers

Agricultural

Improved coordination between demand and available produce

Environmental

Potential reduction in food waste and unnecessary transportation

Consumer welfare

Greater pricing transparency and access to agricultural products

Rural development

Opportunities for digital services and local logistics

Technology

Increased use of data-driven agricultural procurement

Key Performance Indicators

The project will be evaluated using the following measurable indicators:

Number of farmers and FPOs registered.

Number of active buyers.

Total agricultural produce traded through the platform.

Average net earnings per unit of produce for participating farmers.

Difference between comparable farm-gate and consumer prices.

Percentage of orders successfully fulfilled.

Average transportation cost per order.

Delivery time and distance.

Quantity of surplus produce successfully sold.

Buyer satisfaction and repeat purchases.

The actual results will be measured during the pilot rather than assumed in advance.

## Research and References
Reference 1: Electronic National Agriculture Market (e-NAM)

An Indian electronic agricultural trading platform that provides a reference for digital agricultural marketing and market access.

Official website: https://www.enam.gov.in/web/

Reference 2: Agricultural Marketing Information Network (Agmarknet)

Provides agricultural market information, including commodity prices and market arrivals, which may support market analysis and demand estimation.

Official website: https://agmarknet.gov.in/

Reference 3: OpenStreetMap

Provides geographic data for mapping farms, buyers, collection points, and delivery locations.

Official website: https://www.openstreetmap.org/

Reference 4: Google OR-Tools

Provides optimization tools that can support vehicle routing, capacity constraints, and delivery scheduling.

Official documentation: https://developers.google.com/optimization

Reference 5: Scikit-learn

Provides machine-learning algorithms and evaluation tools for developing demand-forecasting models.

Official documentation: https://scikit-learn.org/stable/

Research and Development Plan

Study existing agricultural marketplaces and identify gaps in demand aggregation and shared procurement.

Consult farmers, FPOs, retailers, and institutional buyers to identify practical requirements.

Examine suitable historical agricultural price and market-arrival data.

Develop a prototype for the Agricultural Demand Bank and multi-farmer order allocation.

Test earnings calculations against realistic procurement and transportation costs.

Compare optimized delivery routes with separate deliveries using the same locations and constraints.

Evaluate demand forecasts against actual observations when suitable data is available.

Conduct a pilot and measure farmer earnings, procurement costs, order fulfillment, and surplus utilization.

Data availability, API access, and usage permissions will be verified before integrating external datasets or services.
