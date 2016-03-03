# FrontEnd Recruiting Test

## First Question
As a customer I need an application to manage a TO DO LIST.

**Acceptance criterias**

* Use AngularJS and its best practices;
* To Do List must be able create, update, remove and mark items as done. Each item must follow the entity structure;
* Id must be handled automatically on item create and be unique;
* Item content must not be empty;
* Date must be handled automatically on item create or update;
* Store the items list on local storage;
* Mark item as done must be handle using a customized css3 checkbox; 

**Entity**
```
{
    "id": "1",
    "content": "Buy a new Sublime license",
    "is_done_": false,
    "date_created": 1456861750521 // milliseconds elapsed since 1 January 1970 00:00:00 UTC up until now
}
```

## Second Question
As a developer I want to refactor a existing code using the best practices on AngularJS development. It should keep the same behavior and appearance.

Tip:
* Use of components (directives) is a better practice;
