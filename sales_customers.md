#Sales and Customers

1. Which of the following entities have separate comments tables (Choose 3)?  
  A. Order  
  B. Invoice  
  C. Shipment  
  D. Quote  
  E. Creditmemo  

2. How can a credit card payment method allow for the storage of customer credit cards?  
  A. This is disallowed for security reasons in Magento  
  B. Setting the config node `default/payment/[METHOD CODE]/save_cc` to 1  
  C. Setting the protected property `_canSaveCc` to true  
  D. Changing the admin setting in `Sysetm -> Configuration -> Sales -> Payment Methods -> [Method name] -> Allow Credit Card Save` to "Yes"  
  E. The customer always has this option for CC methods during checkout  

3. To implement a new way for customers to pay for their orders, which of the following is the most correct base class?  
  A. `Mage_Core_Model_Payment_Method`  
  B. `Mage_Payment_Model_Method_Abstract`  
  C. `Mage_Sales_Model_Method_Payment_Abstract`  
  D. `Mage_Sales_Model_Resource_Payment_Method_Abstract`  
  E. `Mage_Payment_Model_Payment_Method_Abstract`  

4. Choose the following statement which is NOT true about customers in Magento  
  A. Customers can be a member of just one group.  
  B. Customers are not an EAV entity. Additional customer attributes are stored in serialized format.  
  C. When a customer account is created, it must be associated with a website.  
  D. Customer forms can be customized in the admin: names, address information, and more.  
  E. A customer can only have one default shipping address and one default billing address.  

5. In order to add a new total to a quote in Magento, which class should be extended?  
  A. `Mage_Core_Model_Store_Address_Total`  
  B. `Mage_Customer_Model_Address_Total_Abstract`  
  C. `Mage_Sales_Model_Quote_Total_Abstract`  
  D. `Mage_Sales_Model_Quote_Address_Total_Abstract`  
  E. `Mage_Sales_Model_Quote_Item_Total_Abstract`  

6. Except for virtual orders, tax totals are calculated based on what part of an order?  
  A. All billing addresses  
  B. All items individually  
  C. The physical location of the Magento store  
  D. The whole order is taxed as a single unit  
  E. All shipping addresses  

## Answers
  1. B,C,E
  2. C
  3. B
  4. B
  5. D
  6. E
