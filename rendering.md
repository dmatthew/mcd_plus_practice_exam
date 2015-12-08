#Rendering

1. Which class does each block that uses a template extend?

  A. `Mage_Core_Block_Template_Default`  
  B. `Mage_Core_Block_Template_Facade`  
  C. `Mage_Core_Block_Text`  
  D. `Mage_Core_Block_Default`  
  E. `Mage_Core_Block_Template`  
  
2. What events do `Mage_Core_Block_Abstract` and `Mage_Core_Block_Template` fire? (Choose two)

  A. `core_block_abstract_to_html_before`  
  B. `core_block_to_html_before`  
  C. `core_block_abstract_to_html_after`  
  D. `core_block_to_html_after`  
  E. `to_html_before`  
  F. `to_html_after`  

3. Which block type renders its children automatically?

  A. `Mage_Core_Block_Text_Tag`  
  B. `Mage_Core_Block_Abstract`  
  C. `Mage_Core_Block_Text`  
  D. `Mage_Core_Block_Text_List`   
  E. `Mage_Core_Block_Template`  

4. Which of the following xpaths would add register a layout xml file for the frontend of the `Mage_Catalog` module?

  A. 
  ```
  <config>
    <front>
      <layout>
        <updates>
          <catalog>
            <file>catalog.xml</file>
  ```
  B. 
  ```
  <config>
    <frontend>
      <layout>
        <updates>
          <catalog>
            <file>catalog.xml</file>
  ```
  C. 
  ```
  <config>
    <type>
      <frontend>
        <layout>
          <updates>
            <catalog>
              <file>catalog.xml</file>
  ```
  D. 
  ```
  <config>
    <layout>
      <frontend>
        <updates>
          <catalog>
            <file>catalog.xml</file>
  ```
  E. 
  ```
  <config>
    <frontend>
      <layout>
        <catalog>
          <file>catalog.xml</file>
  ```

5. How could a custom variable be passed to a block via layout xml?

  A. 
  ```
  <block type="core/template" name="custom">
    <action>
      <method>
        <setCustomValue>
          <value>123</value>
  ```
  B. 
  ```
  <block type="core/template" name="custom">
    <setCustomValue>
      <value>123</value>
  ```
  C. 
  ```
  <block type="core/template" name="custom">
    <action method="setCustomValue">123</action>
  ```
  D. 
  ```
  <block type="core/template" name="custom">
    <action method="setCustomValue">
      <value>123</value>
  ```
  E. 
  ```
  <block type="core/template" name="custom">
    <action method="setCustomValue" value="123" />
  ```

6. Which block is responsible for rendering JavaScript in Magento?

  A. `Mage_Core_Block_Html_Link`  
  B. `Mage_Page_Block_Html`  
  C. `Mage_Core_Block_Template`  
  D. `Mage_Page_Block_Html_Head`  
  E. `Mage_Page_Block_Template_Links`  

##Answers
1. E  
2. A, C
3. D
4. B  
5. D
6. D  
