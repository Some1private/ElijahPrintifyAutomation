Tutorial & Demo:

https://github.com/Some1private/ElijahPrintifyAutomation/assets/88380595/a9c669dc-0fd2-4b7f-b581-6dd25042197f

Download: https://github.com/Some1private/ElijahPrintifyAutomation/releases

Getting Started

1. Download the Windows executable file from the release page.
2. Run the executable file to launch the application.
3. Enter your license key and click "Activate License"
4. Enter your Printify API key and click "Fetch Shops" to retrieve the list of shops associated with your account.
6. Select a shop from the dropdown menu to work with.
7. Go to Printify and create your base products. What's a base product? Check the FAQ below
8. Choose the base products by selecting them from the product list or entering comma-separated product IDs.
9. Click "Choose Images" to select the images you want to use to create new products and then click "Upload Images".
8. Optionally, enter custom values for image positioning (X, Y), scaling, and angle.
9. Click "Create Products" to initiate the product creation process.
10. Once the products are created, click "Publish Products" to make them publish from printify to your store platform.

FAQ

What's a base product?
Your base products are the products that will be "duplicated" in able to create new products with the images you uploaded. 

Example of use: I create 3 base products (Tshirt, Hoodie, Bag) on Printify. I launch the Printify Automation application and enter my API key, select my shop, and select the 3 base products. Then I upload 500 images in the next step in the application. I press create products and the result will be 1500 products (500 Tshirts, 500 Hoodies, 500 Bags) will be created automatically with the option to publish all the newly created products to my Store (Shopify, and all others) in one click.

What scopes does the program need?
I understand that you might not want to give full scopes access when generating your api key so the program doesn't have full access to your account.
You can select the custom scopes option and select the following for all the options in the program to work correctly:

Shops.read
Catalog.read
Products.read
Products.write
Uploads.write

By using these custom scopes when generating your API key the program will only be able to:
 - Read the name/ID of your shops (Needed to select your shop)
 - Read printifys catalogue of products (Needed to use the Append Blueprint Title option)
 - Read products (Needed to fetch your base products to select and extract information)
 - Write products (Needed to create products)
 - Write images (Needed to upload your images)


 Requirements

- Windows operating system
- Internet connection
- Printify account with API access

 Disclaimer

This application is not officially endorsed or affiliated with Printify. Use it at your own risk. The developer is not responsible for any consequences arising from the use of this application.
