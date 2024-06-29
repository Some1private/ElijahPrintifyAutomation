https://github.com/Some1private/ElijahPrintifyAutomation/assets/88380595/a9c669dc-0fd2-4b7f-b581-6dd25042197f

New Web App: https://printify.streamlit.app/

To receive a free license key for 24 hours (Works on web app & program): https://printifyautomation.com/

The Printify Automation Tool is a Windows application that streamlines the process of creating and publishing products on Printify. It allows you to easily duplicate base products with multiple images, saving you time and effort.

 **Features**

- Fetch shops associated with your Printify account
- Select base products to duplicate
- Upload multiple images to create new products
- Customize image positioning, scaling, and angle
- Use options the title for each new products such as using the image file name, or Appending the blueprint title.
- Create and publish products to your store platform with a single click

 **Getting Started**

1. Download the Windows executable file from the [release page](https://github.com/Some1private/ElijahPrintifyAutomation/releases).
2. Run the executable file to launch the application.
3. Enter your license key and click "Activate License".
4. Enter your Printify API key and click "Fetch Shops" to retrieve the list of shops associated with your account.
5. Select a shop from the dropdown menu to work with.
6. Create your base products on Printify (see FAQ for more information).
7. In the application, choose the base products by selecting them from the product list or entering comma-separated product IDs.
8. Click "Choose Images" to select the images you want to use to create new products and then click "Upload Images".
9. (Optional) Enter custom values for image positioning (X, Y), scaling, and angle.
10. (Optional) Use Image file name as product titles, and append the product blueprint title.
11. Click "Create Products" to initiate the product creation process.
12. Once the products are created, click "Publish Products" to publish them from Printify to your store platform.

 **FAQ**

 **What's a base product?**  
Your base products are the products that will be duplicated to create new products with the uploaded images. For example, if you create 3 base products (T-shirt, Hoodie, Bag) on Printify and upload 500 images, the application will create 1500 products (500 T-shirts, 500 Hoodies, 500 Bags) automatically. You can then publish all the newly created products to your store (Shopify, and others) with a single click.

 **What scopes does the program need?**  
To ensure the program functions correctly without granting full access to your account, you can select the following custom scopes when generating your API key:

- Shops.read
- Catalog.read
- Products.read
- Products.write
- Uploads.write

These custom scopes allow the program to:
- Read the name/ID of your shops (needed to select your shop)
- Read Printify's catalogue of products (needed for the Append Blueprint Title option)
- Read products (needed to fetch your base products for selection and information extraction)
- Write products (needed to create products)
- Write images (needed to upload your images)

 **How do the custom values work?**  
By default, each new product created will use the same values as the corresponding base product. If you enter a custom value, that custom image position value will be used on all the created products. It is recommended to use custom values only when choosing a single base product, not multiple. For more information on the correct values to enter, refer to the [Printify API documentation](https://developers.printify.com/image-positioning).

 **Requirements**

- Windows operating system
- Internet connection
- Printify account with API access

 **Disclaimer**

This application is not officially endorsed or affiliated with Printify. Use it at your own risk. The developer is not responsible for any consequences arising from the use of this application.
