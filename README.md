# IKEA Clone Proxy

> This repo links all services required to display a working replica of IKEA's product pages. 
>
> The site has 100 real products for sale from IKEA's website and accurately mimics IKEA's format to display each product.

## Related Projects

  - https://github.com/MyKea/Searchbar-Service
  - https://github.com/MyKea/Image-View
  - https://github.com/MyKea/Carousels-Service
  - https://github.com/MyKea/MykeaReviewsAndDrawers
  - https://github.com/MyKea/Bruce_Product-Description-Service

## Usage
The results will filter as the user types in the search bar. Each drawer contains unique information stored for each product. 

#### ![](assets/readMe/searching:drawers.gif)

Clicking through the image carousel for a product will show all images of the product. 

#### ![](assets/readMe/going-through-images.gif)

Clicking `Add to Cart` will add whatever quantity is currently selected to the cart icon in the top right corner. If the user wishes to go straight to the reviews drawer, simply click the `reviews` next to the products rating.

#### ![](assets/readMe/going-through-product-description.gif)

If a user wishes to leave a review for a product, simply open the reviews drawer and click `Write a review`. Once submited, the results will dynamicly re-render for the avg rating and number of reviews.

#### ![](assets/readMe/writing-a-review.gif)

The user can also inform the author of other reviews if the review was helpful or not by clicking on `yes` or `no`

#### ![](assets/readMe/feedback-for-reviews.gif)

On the bottom of the page, there is a `Similar products` and a `You might also like` carousel. The user can cycle through these carousel and if an item is clicked, the page will dynamicly re-render for the clicked product.

#### ![](assets/readMe/going-through-carousel.gif)

### Installing Dependencies

From within the root directory:

```
npm install
```

