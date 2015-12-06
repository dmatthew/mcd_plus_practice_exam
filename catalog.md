#Catalog

[1. Which table stores relationship data between configurable and simple products?](#answers)

  A. `catalog_product_relation`  
  B. `catalog_product_link`  
  C. `catalog_product_super_link`  
  D. `catalog_product_entity_relation`  
  E. `catalog_product_option`
  
[2. Which index table is used to store final prices.](#answers)

  A. `catalog_product_index_price_idx`  
  B. `catalog_product_index_final_price`  
  C. `product_final_price_index_idx`  
  D. `catalog_product_index_price_final_idx`  
  E. `catalog_product_index_eav_price_final_idx`  
  
[3. Which of the following would return a product collection with the skus "123" and "456"? (Choose 2)](#answers)

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

##[Answers](#catalog)
1. C  
2. D  
3. A and C
