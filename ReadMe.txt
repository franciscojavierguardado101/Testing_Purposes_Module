This example provides a basic structure for a custom module named 
"My Test Module".
The .info.yml file specifies basic information about the module.
The my_test_module.module file defines two example hooks:
hook_init(): This hook is called when the module is initialized. 
You can use it to perform actions like setting up data, registering 
services, or logging messages.
hook_form_alter(): This hook allows you to modify existing forms in Drupal. 
This example shows how to add a custom field to the user 
registration form.