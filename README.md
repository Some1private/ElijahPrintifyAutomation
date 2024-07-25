# Printify Automation Tool Documentation

## Web App

https://app.printifyautomation.com/

## Overview

This tool automates product creation on Printify, allowing users to generate thousands of products in minutes. It streamlines the process by using existing product templates to create new variations with custom images. The tool now includes Excel import/export functionality for even more efficient bulk product management.

## Key Features

- Bulk product creation
- Custom image upload
- Template-based product generation
- Excel import/export for efficient bulk editing

## Workflow

1. API Key Validation
2. Shop Selection
3. Product Template Selection
4. Image Upload
5. Excel Export/Import (Optional)
6. Automated Product Creation

## Usage Guide

### 1. API Key Validation

- Enter your Printify API key on the initial screen.
- The tool validates the key and grants access to your shops.

### 2. Shop Selection

- Choose the Printify shop where you want to create products.

### 3. Product Template Selection

- Browse and select existing products from your chosen shop.
- These will serve as templates for new product creation.

### 4. Image Upload

- Upload your custom images.
- Supports drag-and-drop and multi-file selection.

### 5. Excel Export/Import (Optional)

- Download an Excel template containing your selected products and uploaded images.
- Edit product details in bulk using the Excel file.
- Upload the modified Excel file to create products with customized information.

### 6. Automated Product Creation

- The tool creates new products using selected product templates and uploaded images.
- If using Excel import, product details are customized based on the Excel data.
- All other product details (variants, pricing, etc.) are copied from the template.

## Excel Functionality

### Exporting Excel Template

1. After selecting products and uploading images, click the "Download Excel Template" button.
2. The Excel file will contain columns for product_id, image_id, title, description, and tags.
3. Each row represents a combination of a selected product and an uploaded image.

### Editing Excel File

1. Open the downloaded Excel file in your preferred spreadsheet application.
2. Modify the title, description, and tags for each product-image combination as desired.
3. Save the Excel file after making your changes.

### Importing Excel File

1. Click the "Upload Excel File" button and select your modified Excel file.
2. The tool will process the Excel file and create new products based on the provided information.
3. Product creation progress and results will be displayed on the screen.

## Example Use Case

Creating a themed collection with customized details:

1. Select three base products: a hoodie, a t-shirt, and sweatpants.
2. Upload 100 themed designs.
3. Download the Excel template.
4. Customize titles, descriptions, and tags for each product-image combination in the Excel file.
5. Upload the modified Excel file.
6. The tool will create 300 new products (100 designs x 3 base products) with customized details.

## Potential Impact

- Dramatically reduce time spent on product creation and customization.
- Quickly populate stores with large, diverse product catalogs.
- Easily create themed collections or test multiple designs with unique metadata.
- Efficiently manage and update product information in bulk.

## Notes

- Ensure template products are fully configured (variants, pricing, etc.).
- When using Excel import, only the title, description, and tags are customizable. Other product details are copied from the template.

This tool transforms the product creation process, enabling rapid store expansion, efficient design testing, and bulk product management at scale.
