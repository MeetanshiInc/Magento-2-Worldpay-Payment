# **Magento 2 Worldpay Payment Extension**

**Magento 2 Worldpay Payment Extension** by Meetanshi simplifies the integration of Worldpay payment gateway with Magento 2 stores. This extension offers secure, reliable and user-friendly payment solutions, empowering businesses to provide a seamless shopping experience.

Whether you're targeting global customers or focusing on local markets, this extension supports a wide range of payment options, ensuring smooth transactions for all users.

## **How It Works**

The **Magento 2 Worldpay Payment Extension** enables merchants to integrate the Worldpay payment gateway into their store seamlessly. Once installed and configured, the extension connects your Magento 2 store to Worldpay's payment processing system, allowing you to accept online payments securely.

It uses tokenization to protect sensitive customer data, ensuring compliance with PCI DSS standards. The extension supports multiple payment methods, including credit/debit cards and wallets, making it versatile for diverse customer preferences.

## **Key Features**

* Configure a specific time delay for capturing transactions after payment authorization in your Magento 2 store.  
* Customers are redirected to a secure hosted payment page to enter their card details, complete payments, and select acquirer responses from a dropdown menu.  
* No card data is saved in magento 2 server and thus , worldpay payment method for magento 2 ensures security  

## **Secure Payment Processing**

Ensures a secure connection to Worldpay servers with PCI DSS-compliant tokenization for safeguarding customer data, while incorporating real-time fraud detection and prevention measures to enhance transaction security.

## **Support for Multiple Payment Methods**

Supports a wide range of payment options, including credit and debit cards, wallet payments for added convenience and recurring payments for subscription-based services.

## **Global Compatibility**

Offers multi-currency support for seamless international transactions and localization features, including multi-language capabilities to cater to a global audience.

## **Seamless User Experience**

Provides a mobile-optimized payment interface, a quick checkout process to enhance user satisfaction and customizable payment options for a personalized customer experience.

## **Extension Installation**

To install the Magento 2 Worldpay Payment Extension:

### **Step 1:** 

Unzip the downloaded folder and upload the extension files to the root directory of your Magento 2 installation using FTP.

### **Step 2:** 

### Login to your SSH and run below commands step by step:

* php bin/magento setup:upgrade  
* For Magento version 2.0.x to 2.1.x \- php bin/magento setup:static-content:deploy  
* For Magento version 2.2.x & above \- php bin/magento setup:static-content:deploy –f  
* php bin/magento cache:flush

## **How to Configure Magento 2 Worldpay Payment Extension**

### **Step 1: Payment Gateway Setup**

Ensure the payment gateway is properly configured before setting up the extension.

### **Step 2: Configure Settings**

Navigate to **Sales \> Payment Methods \> Worldpay for Business** to access the settings.

![Configure Settings](https://github.com/user-attachments/assets/ccc37abe-000c-45cd-9dd6-8cc9b9772bab)

* **Enabled**: Set to "YES" to activate the Worldpay for Business payment method.  
* **Title**: Enter the desired title for the payment method displayed to customers.  
* **Show Worldpay Logo**: Choose "YES" to display the Worldpay logo alongside the payment method.  
* **Sandbox Mode**: Set to "YES" to enable sandbox mode for testing purposes.  
* **Installation ID**: Enter the installation ID provided during your Worldpay registration.  
* **Gateway URL**: Provide the gateway URL received during your Worldpay setup.  
* **Merchant Code**: Input the merchant code obtained during registration.  
* **MD5 Secret**: Enter the MD5 secret key set during your payment gateway configuration.  
* **Allow Refund**: Choose "YES" to enable refunds for Worldpay transactions.  
* **Remote Admin Installation ID**: Add the remote admin installation ID provided by Worldpay.  
* **Remote Admin Password**: Enter the remote admin password from your Worldpay account.  
* **Capture Delay**: Specify the delay (in seconds) for capturing transactions after authorization. Ensure this value matches your Worldpay account settings.  
* **Allow Delivery Address**: Select "YES" to enable sending the delivery address to the payment gateway.  
* **Fixed Contact Details**: Set to "YES" to restrict customers from editing billing details passed to the payment gateway.  
* **Hide Contact Details**: Choose "YES" to hide billing details from customers at checkout.  
* **Allow Auto Invoice**: Set "YES" to automate invoice generation for Worldpay orders.  
* **Payment from Applicable Countries**: Select the countries where this payment method will be available.  
* **Additional Information**: Enter any additional details to display on the checkout page.  
* **Sort Order**: Define the display order of the payment method in the payment options list.

### **Step 3: Worldpay for Business on the Frontend**

![Worldpay for Business on the Frontend](https://github.com/user-attachments/assets/eef6b131-1530-4270-a5bd-ae844fd8d682)

After configuring the extension, the Worldpay for Business payment method will be available on the storefront. When customers add products to their cart and proceed to checkout, they can select Worldpay for Business as their preferred payment method and proceed to complete their payment.

### **Step 4: Redirection to the Hosted Payment Page**

![Redirection to the Hosted Payment Page](https://github.com/user-attachments/assets/20e7f256-2efe-425e-bb81-b9c065f2a0ad)

When the user clicks the "Continue to Payment" button on the checkout page, they will be redirected to the hosted payment page to choose their preferred payment method.

### **Step 5: Enter Card Details**

![Enter Card Details](https://github.com/user-attachments/assets/3ac3b0b3-3ad4-4a50-945b-0de596121a4e)

After selecting the payment method, enter your card details as prompted. Verify the reCAPTCHA and proceed to complete the payment.

### **Step 6: Acquirer Responses**

![Acquirer Responses](https://github.com/user-attachments/assets/5edfda04-667c-4633-9537-61a001707678)

Select an acquirer response from the available options and proceed.

### **Step 7: Check Worldpay for Business Details in "My Account"**

![Check Worldpay for Business Details](https://github.com/user-attachments/assets/ee2c2092-75dd-47b2-b9f3-5b2617e80c8b)

After a successful payment, the user will be redirected back to the website. Payment details, including card type, transaction ID, authentication message, authentication code and transaction status, will be available under the "My Orders" tab in the "My Account" section.

### **Step 8: Check Worldpay for Business in the Backend**

![Check Worldpay for Business in the Backend](https://github.com/user-attachments/assets/04447a8d-9423-4dcd-bae6-63fb3d52fe93)

The admin can view the Worldpay for Business payment method details in the backend by navigating to **Sales \> Orders \> Order View**.

## Download our [Magento 2 Worldpay Payment](https://meetanshi.com/magento-2-worldpay.html) Extension
