# E-commerce-analysis-project

## Problem statement: 
In e-commerce start-up. Stakeholders want to know which products performed best over the Christmas period. They want to optimise the products they promote for future sales periods. They do this by analysing up to two months of event data. These are presented as two separate data sources with identical structures. Events refer not only to sales, but also to more general customer actions, such as the viewing of a product on the website or the placing of a product in their virtual shopping basket (cart).


## Datasets
We have a two dataset for November and December events. Each in a separate CSV file with same structure.

| Column Name   | Description                              |
|---------------|------------------------------------------|
| `event_time`  | The date and time of the transaction     |
| `event_type`        | purchase or cart event             |
| `product_id`         | The unique identifier of the product |
| `category_id`      | The unique identifier of the product category |
| `category_code`  | A code that describes the product’s main and subcategories |
| `brand`        | The brand of a product      |
| `price`         | The price the user paid for the product in USD  |
| `user_id`      | The unique identifier of the registered customer |
| `user_session`  | The unique identifier of the user’s browsing session |
