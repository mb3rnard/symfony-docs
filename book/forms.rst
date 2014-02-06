The label option
The label for the form field can be set using the label option, which can be applied to any field:

->add('dueDate', 'date', array(
    'widget' => 'single_text',
    'label'  => 'Due Date',
))

The label for a field can also be set in the template rendering the form, see below.
If you don't need a label associated to your input, you can disable it by setting it's value to false.
