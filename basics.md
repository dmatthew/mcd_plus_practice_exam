#Basics

1. What are the three codepools in Magento?

  A. Code, Community, Local  
  B. Local, Community, Core  
  C. Community, Core, General  
  D. Mage, Local, Connect  
  E. Local, Code, Mage  
  
2. What are your options to add a custom translation for any given string? (Choose three)

  A. `core_translate` table.  
  B. `app/code/locale/<module>/<locale_code>/<Vendor_Modulename.csv>`  
  C. `app/locale/<locale_code>/<Vendor_Modulename.csv>`  
  D. `app/design/fontend/<package>/<theme>/locale/<locale_code>/translate.csv`  
  E. `app/etc/locale/<module>/<locale_code>/translate.csv`  
  
3. What is the priority of translation options?

  A. 
    1. package/theme translation file 
    2. module translation file
    3. database translations  
    
  B. 
    1. module translation file  
    2. package/theme translation file  
    3. database translations  
    
  C. 
    1. database translations  
    2. module translation file  
    3. package/theme translation file  
    
  D. 
    1. package/theme translation file  
    2. database translations  
    3. module translation file
    
  E. 
    1. database translations  
    2. package/theme translation file  
    3. module translation file  
    
4. Which class is responsible for loading module configuration?

  A. `Mage_Config_Model_Config`  
  B. `Mage_Core_Model_Config`  
  C. `Mage_Core_Model_Config_Base`  
  D. `Mage_Config_Model_Abstract`  
  E. `Mage_Core_Model_Config_Default`  
  
5. What are the common methods with which the framework accesses its configuration values and areas? (Choose four)

  A. `Mage::getStoreConfigFlag($path);`  
  B. `Mage::getConfig()->getNode($path);`  
  C. `Mage::getConfigFlag($path);`  
  D. `Mage::app()->getStore()->getConfig()->getNode($path);`  
  E. `Mage::app()->getStore()->getConfig($path);`  
  F. `Mage::getModel('core/config')->getConfig($path);`  
  G. `Mage::getStoreConfig($path);`  

##Answers
1. B  
2. A, C, D  
3. E  
4. B  
5. A, B, E, G
