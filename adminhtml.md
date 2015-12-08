#Adminhtml

1. Which block does a standard Magento form extend?

  A. `Mage_Adminhtml_Block_Catalog_Form`  
  B. `Mage_Adminhtml_Block_Widget_Form`  
  C. `Mage_Widget_Block_Adminhtml_Widget`  
  D. `Mage_Adminhtml_Block_Template`  
  E. `Mage_Adminhtml_Block_Abstract`  

2. What is the default template for a Magento Admin form?

  A. `app/design/adminhtml/default/default/template/page.phtml`  
  B. `app/design/adminhtml/default/default/template/widget/form.phtml`  
  C. `app/design/adminhtml/default/default/template/widget/form/container.phtml`  
  D. `app/design/adminhtml/default/default/template/form.phtml`  
  E. `app/design/adminhtml/default/default/template/widget/grid/container.phtml`  

3. Which of the following is not true for a Magento Admin form container? (Choose two)

  A. Its template is `app/design/adminhtml/default/default/template/widget/form/container.phtml`  
  B. It is a wrapper for the form.  
  C. Its template is `app/design/adminhtml/default/default/template/form/container.phtml`  
  D. It adds a `save` button.  
  E. It adds a `back` button.  
  F. It loads the collection for the form.  

4. Which of the following is not true about adding a field to a form fieldset?

  A. To add a field before another field use the `before` parameter in the addField() method, like the following
  ```
  $fieldSet->addField($elementId, $type, $config, 'before_element_id');
  ```  
  B. Custom element types can be added by creating a class which extends `Varien_Data_Form_Element_Abstract`.   
  C. To add a field after another field use the `after` parameter in the addField() method, like the following
  ```
  $fieldSet->addField($elementId, $type, $config, 'after_element_id');
  ```  
  D. To add a field to the beginning of the fieldset pass a caret as the `after` parameter in the addField() method, like the following
  ```
  $fieldSet->addField($elementId, $type, $config, '^');
  ```  
  E.  To add a form field label, add a `label` key and its value to the `config` parameter in the addField() method, like the following
  ```
  $fieldSet->addField($elementId, $type, array('label' => 'label_value'));
  ```  

5. Which block class do Magento grid classes typically extend?

  A. `Mage_Adminhtml_Block_Widget_Grid`  
  B. `Mage_Adminhtml_Block_Widget`  
  C. `Mage_Adminhtml_Block_Widget_Grid_Container`  
  D. `Mage_Adminhtml_Block_Grid_Abstract`  
  E. `Mage_Adminhtml_Block_Grid_Widget`  

6. What is the default template for Magento grid instances?

  A. `app/design/adminhtml/default/default/template/grid.phtml`  
  B. `app/design/adminhtml/default/default/template/page.phtml`  
  C. `app/design/adminhtml/default/default/template/grid/container.phtml`  
  D. `app/design/adminhtml/default/default/template/widget/grid.phtml`  
  E. `app/design/adminhtml/default/default/template/widget/grid/container.phtml`  

7. What is the first step in preparing an Adminhtml grid?

  A. `_prepareCollection()`  
  B. `_prepareColumns()`  
  C. `_prepareDelete()`  
  D. `_prepareGridItems()`  
  E. `_prepareMassaction()`  

8. Which of the following would filter a grid collection so only products which are enabled are loaded by default? (Choose 2)

  A. `$this->setDefaultFilter('status = 1');`  
  B. `$this->setDefaultFilter('status', 1);`  
  C. `$this->setDefaultFilter(array('default' => array('status' => 1)));`  
  D. `$this->setDefaultFilter(array('status' => array('in' => array(1))))`  
  E. `$this->setDefaultFilter(array('status' => 1));`  
  F. `$this->setDefaultFilter('status', 'eq', '1')`  

9. Which of the following is not a responsiblity of `Mage_Adminhtml_Block_Widget_Grid_Column`? (Choose 2)

  A. Managing a column's renderer.  
  B. Managing data about a grid column.  
  C. Preparing a grid's collection.  
  D. Managing a column's filter.  
  E. Adding new columns to a grid.  

10. Which xpath would allow a system configuration element to be rendered with a custom template?

  A. 
  ```
  <config>
    <sections>
      <{section_name}>
        <groups>
          <{group_name}>
            <fields>
              <{field_name}>
                <model>
  ```
  B. 
  ```
  <config>
    <sections>
      <{section_name}>
        <groups>
          <{group_name}>
            <fields>
              <{field_name}>
                <backend_model>
  ```
  C. 
  ```
  <config>
    <sections>
      <{section_name}>
        <groups>
          <{group_name}>
            <fields>
              <{field_name}>
                <frontend_model>
  ```
  D. 
  ```
  <config>
    <sections>
      <{section_name}>
        <groups>
          <{group_name}>
            <fields>
              <{field_name}>
                <frontend_class>
  ```
  E. 
  ```
  <config>
    <sections>
      <{section_name}>
        <groups>
          <{group_name}>
            <fields>
              <{field_name}>
                <source_model>
  ```

11. What is the syntax for specifying the options in dropdowns and multiselects in system.xml?

  A. `<model>`  
  B. `<backend_model>`  
  C. `<frontend_model>`  
  D. `<frontend_class>`  
  E. `<source_model>`  
  
12. In which table does Magento store data for system configuration?

  A. `core_config_data`  
  B. `core_data`  
  C. `core_cache`  
  D. `core_variable`  
  E. `system_configuration`  

13. For what purpose is the _isAllowed() method used?

  A. To check if a particular admin page is enabled.  
  B. To get the role of a particular user.  
  C. To act as a wrapper for `Mage_Admin_Model_Acl::isAllowed`.  
  D. To check if a particular admin role has access to a particular admin page.  
  E. To get the permissions of a particular role.

14. Which xpath in adminhtml.xml would add a `Manage Prices` menu item within the `Catalog` dropdown menu item.

  A. 
  ```
  <config>
    <menu>
      <item>
        <catalog>
          <children>
            <product_prices>
              <title>Manage Prices</title>
  ```
  B. 
  ```
  <config>
    <menu>
      <catalog>
        <children>
          <product_prices>
            <title>Manage Prices</title>
  ```
  C. 
  ```
  <config>
    <catalog>
      <menu>
        <product_prices>
          <title>Manage Prices</title>
  ```
  D. 
  ```
  <config>
    <menu>
      <catalog>
        <section>
          <products>
            <children>
              <product_prices>
                <title>Manage Prices</title>
  ```
  E. 
  ```
  <config>
    <items>
      <menu>
        <catalog>
          <children>
            <product_prices>
              <title>Manage Prices</title>
  ```

15. Which class parses adminhtml.xml?

  A. `Mage_Core_Model_Config`  
  B. `Mage_Adminhtml_Block_Widget`  
  C. `Mage_Config_Model_Config`  
  D. `Mage_Admin_Model_Config`  
  E. `Mage_Adminhtml_Model_Config`  

##Answers
1. B  
2. B
3. C, F
4. A  
5. A  
6. D  
7. B  
8. D, E  
9. C, E  
10. C  
11. E 
12. A  
13. D  
14. B  
15. D  
