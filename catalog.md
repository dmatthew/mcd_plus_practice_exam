#Catalog

1. Which product type does not exist in Magento?  

  A. `simple`  
  B. `bundle`  
  C. `options`  
  D. `grouped`  
  E. `configurable`  
  F. `virtual`  

2. Which product types are not implemented as part of the Mage_Catalog module? (Choose 2)  

  A. `simple`  
  B. `configurable`  
  C. `virtual`  
  D. `bundle`  
  E. `grouped`  
  F. `downloadable`  
  
3. What is the correct xpath to register a new catalog product type?  

  A.
  ```
  <config>
    <global>
      <catalog_product>
        <type>
          <new_type_code>
  ```  
  B.
  ```
  <config>
    <global>
      <catalog>
        <product>
          <type>
            <new_type_code>
  ```  
  C.
  ```
  <config>
    <global>
      <catalog>
        <product_type>
          <new_type_code>
  ```  
  D.
  ```
  <config>
    <global>
      <catalog>
        <new_type_code>
  ```  
  E.
  ```
  <config>
    <global>
      <catalog>
        <product>
          <default>
            <type>
              <new_type_code>
  ```  
  
4. Which table stores relationship data between configurable and simple products?

  A. `catalog_product_relation`  
  B. `catalog_product_link`  
  C. `catalog_product_super_link`  
  D. `catalog_product_entity_relation`  
  E. `catalog_product_option`
  
5. Which index table is used to store final prices.

  A. `catalog_product_index_price_idx`  
  B. `catalog_product_index_final_price`  
  C. `product_final_price_index_idx`  
  D. `catalog_product_index_price_final_idx`  
  E. `catalog_product_index_eav_price_final_idx`  
  
6. Which of the following would return a product collection with the skus "123" and "456"? (Choose 2)

  A.
  ```
  Mage::getModel('catalog/product)->getCollection()
      ->addAttributeToFilter('sku', array('123', '456'))
  ```
  B.  
  ```
  Mage::getModel('catalog/product)->getCollection()
      ->addAttributeToFilter('sku', '123', '456')
  ```  
  C.  
  ```
  Mage::getModel('catalog/product)->getCollection()
      ->addAttributeToFilter('sku', array('in' => array('123', '456')))
  ```  
  D.  
  ```
  Mage::getModel('catalog/product)->getCollection()
      ->addAttributeToFilter(array('sku' => '123'), array('sku' => '456'))
  ```  
  E.  
  ```
  Mage::getModel('catalog/product)->getCollection()
      ->addAttributeToFilter(array('sku' => array('in' => '123')), array('sku' => array('in' => '456')))
  ```  

7. Assume you have created a new product type. What class would you extend to handle price calculation for the new product type?

  A. `Mage_Catalog_Model_Product_Price`  
  B. `Mage_Catalog_Model_Product_Type_Price`  
  C. `Mage_Catalog_Model_Price`  
  D. `Mage_Catalog_Model_Price_Abstract`  
  E. `Mage_Catalog_Model_Product_Attribute_Price_Abstract`  

8. Assume you have created a new product type. What xpath would you require to register that your product type can have child products?

  A. 
  ```
  <new_type_code>
    <bundle>1</bundle>
  ```  
  B. 
  ```
  <new_type_code>
    <children>1</children>
  ```  
  C. 
  ```
  <new_type_code>
    <composite>1</composite>
  ```  
  D. 
  ```
  <new_type_code>
    <group>1</group>
  ```  
  E. 
  ```
  <new_type_code>
    <options>1</options>
  ```  

9. Which product types implement a parent-child relationship between product entities? (Choose 3)

  A. `simple`  
  B. `configurable`  
  C. `virtual`  
  D. `bundle`  
  E. `group`  
  F. `downloadable`  

10. A customer belongs to the "Special" group and a product's prices are as follows:
  * Price: $10
  * Group Price: Groups: "Special" Price: $15
  * Tier Price 1: Groups: "All" Qty: 1 Price: $20
  * Tier Price 2: Groups: "Special" Qty: 1 Price: $25
  
  What is the price?

  A. $10  
  B. $15  
  C. $20  
  D. $25  
  E. None of the above  

11. What table is tier pricing stored in?

  A. `catalog_product_entity_int`  
  B. `catalog_product_entity_price`  
  C. `catalog_product_entity_tier_price`  
  D. `catalog_product_entity_group_price`  
  E. `catalogrule_product_price`  

12. Which of the following `Mage_Catalog_Model_Resource_Category` methods exist? (Choose 3)

  A. `getChildrenCategories()`  
  B. `getChildren()`  
  C. `getCategoryChildren()`  
  D. `getAllChildren()`  
  E. `getChildrenOfCategory()`  

##Answers
1. C  
2. D, F  
3. B  
4. C  
5. D  
6. A, C  
7. B  
8. C  
9. B, E, F  
10. A  
11. C  
12. A, B, D 
