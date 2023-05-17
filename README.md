# Product_Alternates

# Help shoppers find product “alternates”

When you go shopping, you may have noticed that some of the products are available in “alternate choices” of colors, prints, etc. 

You have to use your AI skills to write a program that will find alternates of the same product in a given e-commerce store. 
Write a function named `FindAlternateGroups()` that takes store_domain as the parameter and returns links of products that are alternates of each other in an array. 
There will be many product alternates arrays in a store, so return all of them in a JSON.


You can use any existing library or API to implement the solution.

Here is an example:

Boys Next Door Apparel Co is a popular Hong-Kong based Menswear & Lifestyle Store. 

You can visit their store at [boysnextdoor-apparel.co](https://www.boysnextdoor-apparel.co/)

You can find all products at [/collections/all](https://www.boysnextdoor-apparel.co/collections/all)

You can find all products data in JSON format by paginating through this link: 
[/collections/all/products.json?page=1](https://www.boysnextdoor-apparel.co/collections/all/products.json?page=1)

The following two products [BEAMS Two Pocket Sweater Navy](https://www.boysnextdoor-apparel.co/products/beams-two-pocket-sweater-navy) and 
[BEAMS Two Pocket Sweater White](https://www.boysnextdoor-apparel.co/products/beams-two-pocket-sweater-white) are alternate choices of the same product, 
so your function should return their product link in the same array.
