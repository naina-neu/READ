# Shopify Frontend

## Overview

This repository contains the frontend code for a Shopify store, utilizing Liquid, HTML, and CSS.

## Prerequisites

Shopify Account

Activate the "profilesforhumanity-org-theme-exp" theme in Shopify.

## Project Structure

#### Templates

##### Liquid Templates:

Located in the "templates" directory, these files control the structure of different pages (e.g., product.liquid).
Import the code from "profile_textarea.html" into "product.theme_template.liquid".

#### Stylesheets:

CSS files in the "assets" directory handle store styling. Customize styles in "main.css".

#### JavaScript

The "assets" directory may include custom JS files. Customize JavaScript in "main.js".

### Registration of the Product form creation in Shopify (Form User profile creation as per condition check of customer ID and order ID)

#### Step 1 - Login to Shopify

Login to Shopify account - https://www.shopify.com/login

![Alt text](/images/registeration/login_step1.png?raw=true "Optional Title")

#### Step 2 - Dashboard Selection

Default PFH-clone is displayed, since user is been added to the project

![Alt text](/images/registeration/login_selection_step2.png?raw=true "Optional Title")

#### Step 3 - Theme Selection

- Default Dashboard is being displayed on entering the Shopify account.
- Ensure the "profilesforhumanity-org-theme-exp" theme is highlighted in the Online Store theme selection.
- This is the theme of the project, is highlighted in the image below.

![Alt text](/images/registeration/Online_Store_theme_selection_step3.png?raw=true "Optional Title")

#### Step 4 - Access Code Editing

Click on the (...) beside the Customize button, to create a Registration of the Product creation template page. Click on the 'Edit code' highlighted in the image below

![Alt text](/images/registeration/Edit_code_menu_step4.png?raw=true "Optional Title")

#### Step 5

Click on the section in the Menu, and select the file name product-template.liquid. Default product-template code is contained in the file.

![Alt text](/images/registeration/product_registeration_code_display_step5.png?raw=true "Optional Title")

#### Step 6

Front-end code git URL - https://github.com/changing-the-present/pfh-editable-profiles/blob/main/frontend/product-template.liquid

Copy the product-template.liquid in the above git url to the product-template.liquid file into the shopify.

![Alt text](/images/registeration/product_template_liquid_gitcode_step6.png?raw=true "Optional Title")

#### Step 7

The listing of Registration Product Collection is displayed in Shopify Collections. Select ctp-clone-registration product

![Alt text](/images/registeration/Collection_listing_step7.png?raw=true "Optional Title")

#### Step 8

Creation Registration Product Collection through Shopify admin portal

![Alt text](/images/registeration/collection_listing_step8.pdf?raw=true "Optional Title")

#### Step 9

Preview Registration Product Collection through online store click on the any of the listing collection.

![Alt text](/images/registeration/Step9.png?raw=true "Optional Title")

#### Step 10

The registration of the product collection form.

![Alt text](/images/registeration/Step10.png?raw=true "Optional Title")

### Product Creation in Shopify - (User Profile)

#### Step 1 - Login to Shopify

Login to Shopify account - https://www.shopify.com/login

![Alt text](/images/product/login_step1.png?raw=true "Optional Title")

#### Step 2 - Dashboard Selection

Default PFH-clone is displayed, since user is been added to the project

![Alt text](/images/product/login_selection_step2.png?raw=true "Optional Title")

#### Step 3 - Theme Selection

- Default Dashboard is being displayed on entering the Shopify account.
- Ensure the "profilesforhumanity-org-theme-exp" theme is highlighted in the Online Store theme selection.
- This is the theme of the project, is highlighted in the image below.

![Alt text](/images/product/Online_Store_theme_selection_step3.png?raw=true "Optional Title")

#### Step 4 - Access Code Editing

Click on the (...) beside the Customize button, to create a Product new template page. Click on the 'Edit code' highlighted in the image below

![Alt text](/images/product/Edit_code_menu_step4.png?raw=true "Optional Title")

#### Step 5 - Create a New Template

On clicking on the 'Edit code' button, a default dashboard is displayed. Click on the Add new template to create the product page.

![Alt text](/images/product/Edit_Code_dashboard_display_step5.png?raw=true "Optional Title")

#### Step 6 - Configure New Template

Popup of 'Add new template' is been displayed.

- 6.1 Template type - Select product
- 6.2 Select liquid file
- 6.3 File name - name the file as per your preference

After filing up all the required data, click on done.

![Alt text](/images/product/Edit_Code_Product_Creation_Step6.png?raw=true "Optional Title")

#### Step 7 - Edit Template Code

product.theme_profile.liquid template is been created. This page contains the default code. We can change in this .liquid file as per user development requirements.

![Alt text](/images/product/Default_Product_theme_page_step7.png?raw=true "Optional Title")

#### Step 8 - Save Changes

Front-end code git URL - https://github.com/changing-the-present/pfh-editable-profiles/blob/main/frontend/profile_textarea.html
Copy the profile_textarea.html (code in the above git url) code to the .liquid file that is created.

![Alt text](/images/product/Edit_Code_product_code_git_step8.png?raw=true "Optional Title")

#### Step 9 - Save Changes

Make sure you 'save' the code and 'exit' the .liquid page. The product theme template is created by the following code.

![Alt text](/images/product/Edit_Code_exit_step9.png?raw=true "Optional Title")

#### Step 10 - Create Product

Navigate to 'Products' on the left menu, then click on the 'Add Product' to create a product (profile page as per our project)

![Alt text](/images/product/Default_Product_display_step10.png?raw=true "Optional Title")

#### Step 11 - Product Details

Details of the product need to be entered to create a product page. Make sure you enter Title, which will be displayed as the name of the product. Also select the theme template 'theme_profile', which is the name of the product.theme_profile.liquid which was created in step 6. Click on save.

![Alt text](/images/product/Product_theme_selection_step11.jpg "Optional Title")

#### Step 12 - Preview and Confirm

After the creation of the product, make sure your product name(profile name) is listed in the product listing. You can click on preview eye icon to preview on the Online Store.

![Alt text](/images/product/Emma_Will_Product_display_step12.png?raw=true "Optional Title")

#### Step 13 - Product Page Display

- These steps guide you through setting up and customizing a product page on Shopify using the specified frontend code

- Below image shows default Profile page being displayed

![Alt text](/images/product/Emma_will_product_layout_step13.jpg?raw=true "Optional Title")
