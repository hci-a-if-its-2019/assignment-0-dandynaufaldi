# Examples of Product with Bad UI <!-- omit in toc -->

Name  : Dandy Naufaldi <br>
NRP   : 05111640000011 <br>
Class : A

# Table of Contents <!-- omit in toc -->
- [1. EnterKomputer Website](#1-enterkomputer-website)
  - [1.1 Bad UI Aspects](#11-bad-ui-aspects)
  - [1.2 Suggestions](#12-suggestions)
  - [1.3 Video](#13-video)
- [2. itsDaring Website](#2-itsdaring-website)
  - [2.1 Bad UI Aspects](#21-bad-ui-aspects)
  - [2.2 Suggestions](#22-suggestions)
  - [2.3 Video](#23-video)
- [3. Department of Informatics ITS Website](#3-department-of-informatics-its-website)
  - [3.1 Bad UI Aspects](#31-bad-ui-aspects)
  - [3.2 Suggestions](#32-suggestions)
  - [3.3 Video](#33-video)
## 1. EnterKomputer Website
#### [Back to Table of Contents](#table-of-contents-) <!-- omit in toc -->
[**enterkomputer.com**](enterkomputer.com) is a website owned by *EnterKomputer*, a computer parts store, which is used for their online shopping platform. The homepage looks like the picture below
<br>
![enterkomp-homepage](img/enterkomp_homepage.png)
<br>
I want to highlight the product listing view when whe choose one of the available product categories from navigation bar. For example, the "LCD" menu section (actually they're all LED display monitor). It looks like this. All of the products are listed in a table. Containing only product name and price. They're separated only based on their brand.
![enterkomp-lcd](img/enterkomp_lcd.gif)
<br>
### 1.1 Bad UI Aspects
  - **No custom filter or sort for user** <br>
    Without additional filter and sort, it will be hard for user to get spesific information about product quickly. They may want to only look for products from certain brand, or see the product sorted from the lowest price, etc. Instead, user has to read through all the product lists.
  - **No image for product** <br>
    Instead of providing image for each of their product, they only give auto-generated URL linked to goole search to show relevant images based on the products name. 
    <br>
    ![enterkomp-lcd-url](img/enterkomp_lcd_url.png)
    <br>
    We have to spend extra time to know what the product looks like.
### 1.2 Suggestions
  - **Add sidebar for custom filter and sort** <br>
    By adding custom filter, potential buyer can filter out irrelevant product based on their preferences. For display monitor products, the filters may include brand, display size, display type, curved, and price range. Custom sort is needed to help user get information in the order they wanted. Custom sort may consist of sort by lowest price or highest price and sort by top selling products.
  - **Use card-like box for product information** <br>
    By using card-like box, EnterKomputer can attach the image of the products. So that, user can easily see what the product looks like without leaving the website.
### 1.3 Video
Coming soon

## 2. itsDaring Website
#### [Back to Table of Contents](#table-of-contents-) <!-- omit in toc -->
[**itsdaring.id**](itsdaring.id) is an online course platform made by PT ITS Tekno Sains to facilitate e-learning in various department. Using this website, lecturer and students can easily set up an online class, where they can share teaching matherials and giving assignment. The homepage look like the image below.
![itsdaring-homepage](img/itsdaring_homepage.png)
Here, I want to highlight the sign up feature.
### 2.1 Bad UI Aspects
- **Location of button to access sign up page** <br>
  From  homepage view like in the above image, can you figure out how you can sign up? There is no button or hyperlink with `sign up` written on it. Actually, to access sign up page you have to click on the "Login" button first. It will redirect you to a login page. Then, you will see a button redirecting to sig up page.
  ![itsdaring-signup](img/itsdaring_signup.gif)

- **Untidy and unintuitive sign up form** <br>
  Following the first bad UI aspect, the sign up form is **untidy** and **unintuitive**.
  ![itsdaring-signup-page](img/itsdaring_signup_page.png)
  We can see that the labels for form input have different size. Also, there is no password confirmation which may help us from misstyping (*typo*) our password. All of the required field has no direct html validation (using `required` attribute) that make user to submit the form first to get the error message.
  
### 2.2 Suggestions
- **Add "Signup" text next to "Login" text** <br>
  Adding simple text as "Signup" into the login button will instantly tell user that they can access signup page from that button
- **Tidy up and add required attribute in sign up form inputs** <br>
  Recheck the font size of form labels. So that, they all have same size. Then, add `required` attribute to relevant input to help user know that the field is required. We can also add a red star "*" next to form label to mark required field.
### 2.3 Video
Coming soon
## 3. Department of Informatics ITS Website
#### [Back to Table of Contents](#table-of-contents-) <!-- omit in toc -->
### 3.1 Bad UI Aspects
### 3.2 Suggestions
### 3.3 Video