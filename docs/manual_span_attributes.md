# List of manual span attributes

This document contains the list of manual Span Attributes used throughout the demo:

## AdService

| Name                        | Type    | Description                           |
|-----------------------------|---------|---------------------------------------|
| `app.ads.category`          | string  | Category for returned ad              |
| `app.ads.contextKeys`       | string  | Context keys used to find related ads |
| `app.ads.contextKeys.count` | number  | Count of unique context keys used     |
| `app.ads.count`             | number  | Count of ads returned to user         |

## CartService

| Name                   | Type   | Description              |
|------------------------|--------|--------------------------|
| `app.product.id`       | string | Product Id for cart item |
| `app.product.quantity` | string | Quantity for cart item   |
| `app.user.id`          | string | User Id                  |

## CheckoutService

| Name                      | Type   | Description                     |
|---------------------------|--------|---------------------------------|
| `app.cart.items.count`    | number | Number of unique items in cart  |
| `app.order.id`            | string | Order Id                        |
| `app.order.shipping.cost` | number | Order shipping cost             |
| `app.order.total.cost`    | number | Order total cost                |
| `app.order.tracking.id`   | string | Order shipping tracking Id      |
| `app.order.items.count`   | number | Number of unique items in order |
| `app.user.currency`       | string | User currency                   |
| `app.user.id`             | string | User Id                         |

## CurrencyService

| Name                           | Type   | Description                   |
|--------------------------------|--------|-------------------------------|
| `app.currency.conversion.from` | string | Currency code to convert from |
| `app.currency.conversion.to`   | string | Currency code to convert to   |

## EmailService

| Name                         | Type   | Description                       |
|------------------------------|--------|-----------------------------------|
| `app.email.sent`             | string | Email used for order confirmation |
| `app.order.id`               | string | Order Id                          |
| `app.shipping.cost.currency` | string | Order currency                    |
| `app.shipping.cost.total`    | string | Order cost total                  |
| `app.shipping.tracking.id`   | string | Order shipping tracking Id        |

## FeatureFlagService

| Name      | Type | Description |
|-----------|------|-------------|
| None yet  |      |             |

## Frontend

| Name                     | Type   | Description                   |
|--------------------------|--------|-------------------------------|
| `app.cart.size`          | number | Total number of items in cart |
| `app.cart.items.count`   | number | Count of unique items in cart |
| `app.cart.shipping.cost` | number | Cart shipping cost            |
| `app.cart.total.price`   | number | Cart total price              |
| `app.currency`           | string | User currency                 |
| `app.currency.new`       | string | New currency to set           |
| `app.order.total`        | number | Order total cost              |
| `app.product.id`         | string | Product Id                    |
| `app.product.quantity`   | number | Product quantity              |
| `app.products.count`     | number | Total products displayed      |
| `app.request.id`         | string | Request Id                    |
| `app.session.id`         | string | Session Id                    |
| `app.user.id`            | string | User Id                       |

## LoadGenerator

| Name      | Type | Description |
|-----------|------|-------------|
| None yet  |      |             |

## PaymentService

| Name                   | Type   | Description        |
|------------------------|--------|--------------------|
| `app.payment.cost`     | number | Total payment cost |
| `app.payment.currency` | string | Payment currency   |

## ProductCatalogService

| Name                 | Type   | Description                           |
|----------------------|--------|---------------------------------------|
| `app.product.id`     | string | Product Id                            |
| `app.product.name`   | string | Product name                          |
| `app.products.count` | number | Number of products returned in search |

## RecommendationService

| Name                             | Type   | Description                             |
|----------------------------------|--------|-----------------------------------------|
| `app.filtered_products.count`    | number | Number of filtered products returned    |
| `app.products.count`             | number | Total number of products                |
| `app.products_recommended.count` | number | Number of recommended products returned |

## ShippingService

| Name                       | Type   | Description          |
|----------------------------|--------|----------------------|
| `app.shipping.cost.total`  | number | Total shipping cost  |
| `app.shipping.items.count` | number | Total items to ship  |
| `app.shipping.tracing.id`  | string | Shipping tracking Id |
