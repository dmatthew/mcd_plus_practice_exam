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
