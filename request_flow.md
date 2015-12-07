#Request Flow

1. Which of the following steps is run first when initializing the application from `Mage_Core_Model_App`?

  A. Apply database data updates whenever needed with `Mage_Core_Model_Resource_Setup::applyAllDataUpdates();`  
  B. Initialize currently ran store with `Mage_Core_Model_App::_initCurrentStore();`  
  C. Initialize base system configuration with `Mage_Core_Model_App::_initBaseConfig();`  
  D. Apply database updates whenever needed with `Mage_Core_Model_Resource_Setup::applyAllUpdates();`  
  E. Initialize application cache instance with `Mage_Core_Model_App::_initCache();`  

2. What is the proper xpath in Magento to add a router class?

  A.  
  ```
  <config>
    <default>
      <web>
        <routers>
          <router_name>
            <area>area_name</area>
            <class>class_name</class>
  ```
  B.  
  ```
  <config>
    <default>
      <web>
        <routers>
          <use>standard</use>
             <args>
              <module>module_name</module>
              <frontName>front_name</frontName>
  ```
  C.  
  ```
  <config>
    <default>
      <web>
        <routers>
          <name>route_name</name>
          <class>class_name</class>
  ```
  D.  
  ```
  <config>
    <routers>
      <route>
          <router_name>
            <area>area_name</area>
            <class>class_name</class>
  ```
  E.  
  ```
  <config>
    <admin>
      <web>
        <routers>
          <router_name>
            <use>area_name</use>
  ```
  
3. Which of the following is not a column in the `core_url_rewrite` table?

  A. `request_path`  
  B. `route_path`  
  C. `is_system`  
  D. `target_path`  
  E. `id_path`  

4. In what order are Magento's routers matched?

  A. `Standard, Admin, CMS, Default`  
  B. `Admin, Standard, Default, CMS`  
  C. `Admin, CMS, Default, Standard`  
  D. `Admin, Standard, CMS, Default`  
  E. `Default, Standard, CMS, Admin`  

5. What is the action in the following path?

  `catalog/category/view/id/4`

  A. `category`  
  B. `id`  
  C. `4`  
  D. `catalog`  
  E. `view`  
  
##Answers
1. C  
2. A  
3. B  
4. D  
5. E
