#Working with Databases in Magento

1. Which of the following methods do not exist to create joins between tables on collections and on select instances? (Choose 2)

  A. `joinWith`  
  B. `joinNatural`  
  C. `joinRight`  
  D. `joinFront`  
  E. `joinLeft`  
  F. `joinCross`  
  H. `joinInner`  
  I. `join`  
  J. `joinFull`  
  
2. Which of the following ways exist to specify filters on a flat table collection? (Choose 2)

  A. `$collection->where()`  
  B. `$collection->getSelect()->where()`  
  C. `$collection->addFieldToFilter()`  
  D. `$collection->addNewFilter()`  
  E. `$collection->getSelect()->addFieldToFilter()`  

3. Which of the following ways exist to influence the ordering of the result set for flat table collections? (Choose 2)

  A. `$collection->order()`  
  B. `$collection->setOrder()`  
  C. `$collection->getSelect()->order()`  
  D. `$collection->getSelect()->setNewOrder()`  
  E. `$collection->addOrder()`  

4. Which is the base setup class for flat table entities, and which one the base for EAV entities?

  A. `Mage_Core_Model_Resource_Setup` for flat table entities.  
  `Mage_Eav_Model_Resource_Entity_Setup` for EAV entities.  
  B. `Mage_Core_Model_Flat_Setup` for flat table entities.  
  `Mage_Core_Model_Resource_Setup` for EAV entities  
  C. `Mage_Core_Model_Resource_Setup` for both.  
  D. `Mage_Core_Model_Setup` for flat table entities.  
  `Mage_Core_Model_Setup_Eav` for EAV entities.  
  E. `Mage_Core_Model_Resource_Setup` for flat table entities.  
  `Mage_Eav_Model_Entity_Setup` for EAV entities.  

5. How can you implement a rollback in Magento?

  A. By decreasing the module version number and creating a data-upgrade file in the sql folder of the module with a filename like `data-upgrade-0.2.0-0.1.0`  
  B. By decreasing the module version number and creating a db-upgrade file in the sql folder of the module with a filename like `upgrade-0.2.0-0.1.0`   
  C. By decreasing the module version number and creating a data-rollback file in the sql folder of the module with a filename like `data-rollback-0.2.0-0.1.0`  
  D. By decreasing the module version number and creating a db-rollback file in the sql folder of the module with a filename like `rollback-0.2.0-0.1.0`  
  E. Magento does not support rollbacks.  

6. What is true about `addAttribute()` and `updateAttribute()` in EAV setup scripts? (Choose 2)  

  A. `addAttribute()` is used to add new EAV attributes.  
  B. `updateAttribute()` is a method of the class `Mage_Core_Model_Resource_Setup`   
  C. `addAttribute()` is used to add system configuration values only.  
  D. `addAttribute()` will return an error if the attribute already exists for the given entity type.  
  E. `updateAttribute()` is used to update an attributes data.  

##Answers
1. A, D  
2. B, C  
3. B, C  
4. E  
5. E  
6. A, E  
