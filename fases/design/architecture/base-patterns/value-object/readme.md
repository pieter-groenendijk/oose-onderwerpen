# Value Object

You have two types of objects. _Reference_ objects and _value_ objects. This is different from passing by _reference_
or _value_, although related. A _reference_ object handles equality using identity (pointer value). A _value_ object 
handles equality using the actual content of the object; is the content the same?

## When to apply?
When equality shouldn't be based of identity.