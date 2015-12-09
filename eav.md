#Entity-Attribute_Value (EAV) Model

1. Which entities in a native Magento installation do not use EAV resource models? (Choose 2)  

  A. `catalog_category`  
  B. `order`  
  C. `customer_address`  
  D. `catalog_product`  
  E. `customer`  
  F. `quote_item`  

2. Which models, (attribute models, attribute source models, attribute backend models, attribute frontend models) are responsible for frontend logic? 

  A. attribute models  
  B. source models  
  C. backend models   
  D. frontend models  
  E. none of the above  

3. Which models, (attribute models, attribute source models, attribute backend models, attribute frontend models) base class is `Mage_Eav_Model_Entity_Attribute`? 

  A. attribute models  
  B. source models  
  C. backend models   
  D. frontend models  
  E. none of the above  

4. Which models, (attribute models, attribute source models, attribute backend models, attribute frontend models) are responsible for managing the available options for an attribute? 

  A. attribute models  
  B. source models  
  C. backend models   
  D. frontend models  
  E. none of the above  

5. Which models, (attribute models, attribute source models, attribute backend models, attribute frontend models) are responsible for validating attribute data? 

  A. attribute models  
  B. source models  
  C. backend models   
  D. frontend models  
  E. none of the above  

6. Which methods have to be implemented in a custom attribute source model? (Choose 2)  

  A. `setAttribute()`  
  B. `getAttribute()`  
  C. `getFlatColums()`  
  D. `getAllOptions()`  
  E. `getOptionText()`  
  F. none  

7. Which methods have to be implemented in a custom attribute frontend model?  

  A. `setAttribute()`  
  B. `getAttribute()`  
  C. `getFlatColums()`  
  D. `getAllOptions()`  
  E. `getOptionText()`  
  F. none  

8. Which of the following methods do not have to be implemented in a custom attribute backend model?  

  A. `validate()`  
  B. `isStatic()`  
  C. `beforeSave()`  
  D. `getTable()`  
  E. `afterSave()`  
  F. `getEntityValueId`  

9. What is the default frontend model for EAV attributes?  

  A. `Mage_Eav_Model_Resource_Attribute_Frontend`  
  B. `Mage_Eav_Model_Entity_Attribute`  
  C. `Mage_Eav_Model_Resource_Attribute`  
  D. `Mage_Eav_Model_Entity_Attribute_Frontend_Default`  
  E. `Mage_Eav_Model_Frontend_Default`  

10. How do you get a list of all options for an attribute?  

  A. `Mage::getModel('eav/entity')->getAttribute()->load($id)->getSource()->getOptions();`  
  B. `Mage::getModel('eav/entity_attribute')->load($id)->getSource()->getAllOptions();`  
  C. `Mage::getModel('eav/entity')->getAttribute($id)->getSource()->getAllOptions();`  
  D. `Mage::getModel('eav/entity_attribute')->load($id)->getAllOptions();`  
  E. `Mage::getModel('eav/entity')->getAttributeOptions($id)`  

##Answers
1. B, F  
2. D  
3. A  
4. B  
5. C  
6. D, E 
7. F  
8. A  
9. D  
10. B  
