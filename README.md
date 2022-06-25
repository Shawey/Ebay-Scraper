# EbayScraper
Get the average price of any product on Ebay.
```
import EbayScraping

price = EbayScraping.search('Nintendo Switch', 'ca', 'new')
print(price)
```
```
Output: {'soldPrice': 326.2, 'shippingPrice': 39.67, 'total': 365.87}
```
