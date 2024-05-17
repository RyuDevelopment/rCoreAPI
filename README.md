# rCore Developer API

Welcome to the rCore Developer API, the core of ranks for your project.

# Get main API class
```
In kotlin:
  CoreAPI.{system}
In java:
  CoreAPI.INSTANCE.{system}
```

# Profile System
```
In kotlin:
  val profile = CoreAPI.profileManager.findById(uniqueId)
In Java: 
  Profile profile = CoreAPI.INSTANCE.getProfileManager().findById(uniqueId);
```

# Rank System
```
In kotlin:
  val rank = CoreAPI.rankManager.findById(rankName)
In Java: 
  Rank rank = CoreAPI.INSTANCE.getRankManager().findById(rankName);
```

# Tag System
```
In kotlin:
  val tag = CoreAPI.tagManager.findByName(tagName)
In Java: 
  Tag tag = CoreAPI.INSTANCE.getTagManager().findByName(tagName);
```

This complete README provides an introduction to the project, followed by usage examples for the main functionalities of the API, and a footer indicating that the documentation may not be complete, but efforts are being made to add more functions.
