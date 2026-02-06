## Product Choice

- Wildberries.ru
- <https://www.wildberries.ru/>
- An online shopping store that provides the opportunity to try on an item before purchasing

## Main components

![Wildberries Component Diagram](.\diagrams\out\wildberries\architecture-component\Component%20Diagram.svg)

![Wildberries Component Diagram code](.\diagrams\src\wildberries\architecture-component.puml)

- Component "Catalog & Search Service" is used as menu where usser can search and found some product.
- Component "Customer Mobile App" is an app for mobile phone for clients.
- Component "WB Partners App (Seller)" is an app for mobile phone for some partners and sellers.
- Component "User Profile & Loyalty" is a part of website or app where user can see, apdate or delete information about itself.
- Component "Review & Ratings Service" is a part of website or app, where user can write and read the reviews.

## Data flow

![Wildberries Sequence Diagram](.\diagrams\out\wildberries\architecture-sequence\Sequence%20Diagram.svg)

![Wildberries Sequence Diagram code](.\diagrams\src\wildberries\architecture-sequence.puml)

- Group 3. Bank sends a request that the payment was successful. Gateway is activated and activate activate PaySvc. After Update Order Status to PAID.

## Deployment

![Wildberries Deployment Diagram](.\diagrams\out\wildberries\architecture-deployment\Deployment%20Diagram.svg)

![Wildberries Deployment Diagram code](.\diagrams\src\wildberries\architecture-deployment.puml)

- Apps and website deployment on smartphone and User Computer. Other on cloud Wildberries Global Infrastructure.

## Assumptions

- I assume the Logistics & Routing service integrates with multiple delivery partners to optimize shipping costs and delivery times.
- I assume that for seller and user have two different intefaces and apps.
  
## Open questions

- How they optimized a lot of parallel buying?
- What specific caching strategies are used to handle high traffic during sales events?
