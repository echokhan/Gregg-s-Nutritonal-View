# Greggs-Nutritonal-View
A repo of my attempt at providing a one-window 360 degree nutritional view of Gregg's menu

Greggs has nutrional data uploaded on their website for each product.
Our task required collection of this data for downstream one-window view.

This was done from products available at https://www.greggs.co.uk/menu/product/


:fries: The *get_href_list* function is a function used to extract specific hyperlink URLs from a given web page. The primary use case for this function is to retrieve links that lead to product pages within a specified base path.

:baguette_bread: The *get_image* function dynamically retrieves and saves product images from specified web content using BeautifulSoup. It identifies image URLs from meta tags, fetches the images via HTTP requests, and stores them locally in a structured directory format based on the product type.

:hamburger: The *get_nutrition* function extracts and organizes nutritional information from a specified webpage for a given product. Utilizing BeautifulSoup to parse HTML content, the function captures the product's name and description from meta tags, navigates its nutritional table, and constructs a dictionary that summarizes the product's nutrition details, including dynamically retrieved nutritional data from the web page's table elements.
Later on transformations are carried out that ensure that the data is fit for our dashboard.

![image](https://github.com/echokhan/Greggs-Nutritonal-View/assets/33589432/13c8ed66-1d95-4a08-bb85-bc25c43dc686)








