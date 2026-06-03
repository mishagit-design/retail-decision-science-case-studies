# Sister Store Recommendation Engine

## Business Problem

The Size Optimization platform required historical store relationships to support size profile recommendations. When a store lacked sufficient history or was newly opened, a comparable "sister store" needed to be identified to provide a reasonable proxy for assortment and size planning decisions.

Manual identification of sister stores was time-consuming and difficult to scale across a large retail fleet.

## Objective

Develop an automated recommendation framework that identifies suitable sister stores using geographic proximity and store capacity characteristics.

## Approach

* Leveraged geospatial functions in BigQuery SQL to calculate distances between store locations
* Developed recommendation logic based on store capacity and geographic proximity
* Automated the identification of comparable stores through scalable SQL workflows
* Generated sister-store recommendations used by the Size Optimization process when historical store data was unavailable
* Validated recommendations with merchandising stakeholders to ensure business relevance
* Collaborated with engineering partners responsible for downstream API integrations and production workflows

## Stakeholders

### Merchandising

Used sister-store recommendations to support assortment and size planning decisions when direct historical information was unavailable.

### Engineering

Partnered on downstream system integration and operationalization of recommendation outputs within the broader Size Optimization ecosystem.

## Technologies

* SQL
* BigQuery
* Geospatial Analytics
* Recommendation Systems
* Retail Analytics

## Impact

* Automated sister-store identification across hundreds of store locations
* Reduced manual effort required to establish comparable store relationships
* Improved consistency and scalability of store pairing recommendations
* Enabled the Size Optimization platform to support stores with limited or unavailable historical data

## Key Learnings

Recommendation systems are valuable not only for customer-facing experiences but also for operational decision-making. Combining location intelligence and business constraints can create scalable solutions that support merchandising and planning processes across large retail organizations.
