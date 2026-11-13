# API Skins

CS2 skin prices from every major marketplace in one API: the cheapest offer of every item on each marketplace, the highest buy orders, sales history and item data.

**[apiskins.com](https://apiskins.com)** · [API docs](https://apiskins.com/api-docs) · [Pricing](https://apiskins.com/pricing) · [Skin prices](https://apiskins.com/prices)

## Client libraries

| | Install | Repository |
|---|---|---|
| **Node.js / TypeScript** | `npm install cs2-price-api` | [cs2-price-api](https://github.com/apiskins/cs2-price-api) |
| **Python** | `pip install cs2-price-api` | [cs2-price-api-python](https://github.com/apiskins/cs2-price-api-python) |

```python
from cs2_price_api import ApiSkins, lowest_offer

api = ApiSkins(api_key="...")
print(lowest_offer(api.offers.get("AK-47 | Redline (Field-Tested)")))
```

## What we offer

- [Price API](https://apiskins.com/price-api): every item's cheapest listing on each marketplace
- [Buy order API](https://apiskins.com/buy-order-api): the highest buy orders
- [Sales API](https://apiskins.com/sales-api): sales, medians and volumes over 7 to 90 days
- [Item API](https://apiskins.com/item-api): what every CS2 item is, for filtering
- [Arbitrage tool](https://apiskins.com/arbitrage): price gaps between marketplaces
- [Trading bots](https://apiskins.com/trading-bots): keep your offers and buy orders at the best price
- [Market index](https://apiskins.com/market-index): the CS2 market, knives, gloves, cases and more over time

The free plan includes Steam prices and buy orders. Get a key by signing in with Steam on [apiskins.com](https://apiskins.com).
