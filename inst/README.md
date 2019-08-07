### Primary Project Info:

1. The Binding field tells RStudio which R function the project template is associated with. When a user creates a new project using this template, the hello_world() function defined by this package will be used to generate the project.

2. The Title field is used and shown within the new project wizard.

3. The OpenFiles field instructs the IDE to open a file called INDEX when the project is first opened, after creating the project.



### Define Input Widget


The Parameter field is used to identify the parameter name. That is, the value of the widget used here will be associated with the parameter called check when passed to the template function hello_world().

The Widget field is used to specify the type of widget to be used. Here, we use a checkbox, to allow for ‘on / off’ input from the user.

The Label field is used to give a label associated with the checkbox.

The Default field gives the default value for the checkbox input – here, we want to default having the checkbox ‘on’, or checked.

The Position field tells the RStudio IDE that this widget should be displayed on the left side of the wizard dialog.
