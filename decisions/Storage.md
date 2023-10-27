---
parent: Decisions
title: Storage Solution for Android Calculator App

status: accepted
date: 2023-10-26
deciders: David Adesegun
---
# Storage for Android Calculator App

## Context and Problem Statement

Our graphing calculator app needs a storage system to efficiently manage and store user data such as equations, saved graphs and user preferences. The problem is to decide which storage system we should select considering factors such as efficiency, simplicity, and data integrity.

## Decision Drivers

* **Data Storage and Retrieval Efficiency**: Ensuring that the chosen database system can efficiently store and retrieve graph data.
* **Simplicity**: The solution should be easy to implement and maintain.
* **Platform Compatibility**: The solution should be available and reliable on Android.
* **Data Integrity**: The solution should provide mechanisms to ensure data integrity and prevent data loss.

## Considered Options

* **Option 1: Cloud-based Storage**
* **Option 2: SQLite**
* **Option 3: Local Device Storage**

## Decision Outcome

Chosen option: "Option 2: SQLite is a lightweight embedded database system which works well as our calculator does not need extensive database capabilities and its good for mobile applications. It provides efficient data storage and requires minimal overhead.

### Consequences

* Good, because SQLite is lightweight and optimized for mobile apps, which will result in faster data retrieval and improved user experience.
* Bad, because SQLite may have limitations in handling extremely large datasets.

## Pros and Cons of the Options

### Option 1: Cloud-Based Storage

* Good, because it has high scalability and can handle large datasets.
* Good, because allows data access from multiple devices.
* Good, because it is easy to synchronize data across multiple devices.
* Neutral, because it might require subscription costs for cloud services.
* Neutral, because it requires ongoing support.
* Bad, because it relies on an internet connection.

### Option 2: SQLite

* Good, because it is lightweight and embedded.
* Good, it provides fast data retrieval and good for managing user-generated graphs.
* Neutral, because it doesn’t scale well with extremely large datasets.
* Bad, because it is not good for complex table structures.

### Option 3: Local Storage

* Good, because it allows for offline usage and quick access to data stored directly on the user's device.
* Good, because it’s not dependent on external services, which will improve data security and privacy.
* Good, because it has a simple implementation.
* Neutral, because data capacity depends on the device's storage capabilities.
* Bad, because data may be lost if the device is damaged or lost.

## More Information

Choosing SQLite as the team’s storage solution, we can ensure the completion of that portion of the app in the required time frame and with minimal costs.
