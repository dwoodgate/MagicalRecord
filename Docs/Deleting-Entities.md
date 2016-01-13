# Deleting Entities

To delete a single entity in the default context:

```objective-c
[myPerson MR_deleteEntity];
```
<details><summary>Swift</summary>
```swift
let myPerson = Person.MR_deleteEntity()
```
</details>

To delete the entity from a specific context:

```objective-c
[myPerson MR_deleteEntityInContext:otherContext];
```
<details><summary>Swift</summary>
```swift
myPerson.MR_deleteEntityInContext(otherContext)
```
</details>

To truncate all entities from the default context:

```objective-c
[Person MR_truncateAll];
```
<details><summary>Swift</summary>
```swift
Person.MR_truncateAll()
```
</details>

To truncate all entities in a specific context:

```objective-c
[Person MR_truncateAllInContext:otherContext];
```
<details><summary>Swift</summary>
```swift
Person.MR_truncateAllInContext(otherContext)
```
</details>
