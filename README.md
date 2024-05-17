# rCore Developer API

Welcome to the rCore Developer API, the core of ranks for your project.

# Get main API class
```kotlin
  CoreAPI.{system}
```
In Java: 
```kotlin
  CoreAPI.INSTANCE.{system}
```

# Profile System

In kotlin:
```kotlin
  val profile = CoreAPI.profileManager.findById(uniqueId)
```
In Java: 
```kotlin
  Profile profile = CoreAPI.INSTANCE.getProfileManager().findById(uniqueId);
```

# Rank System
In kotlin:
```kotlin
  val rank = CoreAPI.rankManager.findById(rankName)
```
In Java: 
```kotlin
  Rank rank = CoreAPI.INSTANCE.getRankManager().findById(rankName);
```

# Tag System
In kotlin:
```kotlin
  val tag = CoreAPI.tagManager.findByName(tagName)
```
In Java: 
```kotlin
  Tag tag = CoreAPI.INSTANCE.getTagManager().findByName(tagName);
```

## This complete README provides an introduction to the project, followed by usage examples for the main functionalities of the API, and a footer indicating that the documentation may not be complete, but efforts are being made to add more functions.
