# Create Entity

With the help of this action you will be able to build an entity list from scratch by just appending values from Form/Grid.

Using this Action you can edit the following fields:

* **Description**. A short description for the action. Only admins will be able to see this field.
* **Error Message**. An error message that will be displayed in case if a error occurs in this action.
* **Condition**. This boolean expression is used to determine if this action will execute. Use it to enable or disable actions programatically. For example, you'd enable a **ShowError** action only if you've found an error let's say when you parsed a response from a web service. A common example is **\[SomeField\] == "Some Value"**. This field supports **My Tokens**. 
* **Entity Name**. Provide a name for your new entity.
* **Properties**.  select which properties\(and corresponding values\) should be added to the newly created entity.

![](//static.dnnsharp.com/documentation/create_entity.png)

