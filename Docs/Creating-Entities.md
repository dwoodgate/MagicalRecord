<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.2.0/jquery.min.js"></script>

# Creating Entities

To create and insert a new instance of an Entity in the default context, you can use:

```objective-c
Person *myPerson = [Person MR_createEntity];
```
<details><summary>Swift</summary>
```swift
let myPerson = Person.MR_createEntity()
```
</details>
To create and insert an entity into specific context:

```objective-c
Person *myPerson = [Person MR_createEntityInContext:otherContext];
```
<details><summary>Swift</summary>
```swift
let myPerson = Person.MR_createEntity()
```
</details>
