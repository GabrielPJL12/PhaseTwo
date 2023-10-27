---
parent: Decisions
title: Navigation Strategy Solution for Android Calculator App

status: accepted
date: 2023-10-26
deciders: Gabriel Leclerc
---

# Navigation Strategy

## Context and Problem Statement

The goal of this project is to create a calculator app capable of multiple things such as arithmetic operations, graphing, and unit conversion. The problem is to decide what navigational strategy we should select taking into account user experience.

## Decision Drivers

- **Screen Space:** We do not want out calculator app looking too cluttered.
- **Ease of Use:** We would like the navigation method to be intuitive to allow easy access to all parts of the app.

## Considered Options

- Tabs
- Hamburgers Menu
- Bottom Navigation
- Top Navigation
- Cards for Navigation
- Gesture-Assisted Navigation
- Full Screen Navigation
- 3D Touch

## Decision Outcome

Chosen option: "Tabs", because Tabs aren't too different from a navigation bar, allowing intuitive navigation of the application while allowing the developers to blend the navigation system into the calculator app seamlessly.

### Consequences

- Good, because it allows for intuitive use of the navigation system as it does not introduce any new concepts to the user.
- Good, because the navigation system will not take up very much space.
- Good, because it allows for simple implementation of the navigation strategy.
- Bad, because it may not be the most efficient use of space.

## Pros and Cons of the Options

### Tabs

- Good, because it allows for intuitive use of the navigation system as it does not introduce any new concepts to the user.
- Good, because the navigation system will not take up very much space.
- Good, because it allows for simple implementation of the navigation strategy.
- Bad, because it may not be the most efficient use of space.

### Hamburgers Menu

- Bad, because not well-known.
- Good, because it can hide complex navigational systems.
- Bad, because obscures navigational options. May influence user experience.

### Bottom Navigation

- Good, because it allows for easy thumb access to the navigation system.
- Good, because it is well-known.
- Bad, because it may make the functionality of the app more difficult to access.

### Top Navigation

- Good, because it is well-known.
- Good, because it may make the functionality of the app easy to access.
- Bad, because phones are getting larger and the top of the screen is becoming harder to reach while operating a mobile device with one hand.
- Bad, because it is recommended to be used with other navigation strategies.

### Cards for Navigation

- Good, because it can come in varying shapes and sizes.
- Bad, because it is not intuitive.
- Good because it can be personalized.

### Gesture-Assisted Navigation

- Good, because users can swipe quickly in the direction they want to navigate to, allowing for simple navigation.
- Good, because very well-known and has been popular in past years.
- Neutral, because it may be old-school.
- Bad, because some users may have difficulty using the navigation system.
- …

### Full Screen Navigation

- Good, because it allows for the organization of large amounts of information in a system.
- Good, because it can be learned quite quickly.
- Bad, because it initially hides information from the user.

## More Information

We may need to go over navigational transitions.
options:

- Hierarchical Transitions
- Peers Transitions
- Flat Navigation
- Experience-Driven or Content-Driven Navigation.

We will be using Peers Transitions and Flat Navigation as out navigational transitions. As they allow for lateral navigation through similar screens and different categories.
