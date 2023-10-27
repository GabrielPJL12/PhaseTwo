---
# Configuration for the Jekyll template "Just the Docs"
parent: Decisions
title: UI Toolkit Selection for Android Calculator App

status: accepted
date: 2023-10-26
deciders: Benjamin Roskey
---

# Phase 2 - Group 10

## _UI toolkit: React Native Elements, Native Base, Shoutem UI, Ant Design Mobile, or, UI Kitten_

The goal of this project is to build a calculator app with Android OS. This document will focus on which UI toolkit will be used to build said app, while discussing pros and cons of the options provided to us to use.


## Decision Drivers
- **Compatability** We need our app to work with an Android.
- **Ease of Use** The toolkit that has the most amount of resources and allows us developers to use with ease will be important in the long run.
- **Costs** We are building a calculator which will most likely not provide financial return, thus time is all we want to put in.

## Considered Options

- **Option 1:** React Native Elements
- **Option 2:** Native Base
- **Option 3:** Shoutem UI
- **Option 4:** ANT Design Mobile
- **Option 5:** UI Kitten

## Decision Outcome

Chosen option: **Option 1:** React Native Elements. This UI toolkit allows the most customization out of all the options, shareable code, is cost effective, and has built in help features to aid us developers.

### Consequences

- Good, because it is a better user experience by using native components for the UI development.
- Good, because it uses JSW (a syntax) thta is used to embed XML with JavaScript.
- Good, because it uses a single codebase that is shareable amongst platforms, even though we are only focused on Android.
- Good, because it is has built in file extensions that can detect the OS supporting the app.
- Good, because it has hot reloading that deploys only files that have changes made to them, without refreshing entire app.
- Bad, because it is not suitable for complex apps.
- Bad, because certain platforms like Android Wears, and Smart TV's may not be compatible with React Native.

## Pros and Cons of the Options

### **Option 1:** React Native Elements

- Good, because it is a better user experience by using native components for the UI development.
- Good, because it uses JSW (a syntax) thta is used to embed XML with JavaScript.
- Good, because it uses a single codebase that is shareable amongst platforms, even though we are only focused on Android.
- Good, because it is has built in file extensions that can detect the OS supporting the app.
- Good, because it has hot reloading that deploys only files that have changes made to them, without refreshing entire app.
- Bad, because it is not suitable for complex apps.
- Bad, because certain platforms like Android Wears, and Smart TV's may not be compatible with React Native.
    *
### **Option 2:** Native Base
{example | description}

- Good, because it has reusable UI components to build multi-platform apps, thus making cross platform compatibility enabled with a single codebase.
- Good, because the ease of use allows newer developers to learn Native Base without much struggle.
- Good, no internet connection is required.
- Bad, because it allows limited customization, components must be created from scratch, thus less flexibility.
- Bad, because it has management dependencies that rely on the developers, and other libraries such as React Native.
- Bad, because it requires more necessary resources such as costs.

### **Option 3:** Shoutem UI

- Good, ease of use allowing for users to create mobile apps without any coding experience.
- Good, because it as cross platform compatibility.
- Good, because it has reusable components which lets the user build mobile apps more quickly.
- Bad, because it is not cost effective as we have React Native for to use for free.
- Bad, because customer service is slow and impatient.
- Bad, because it allows limited customization.

### **Option 4:** ANT Design Mobile
- Good, because it has user-friendly UI making it easy to use.
- Good, becasue it has support for TypeScript and ES6 making it easy to integrate with other libraries.
- Good, because it allows multi-platform usage.
- Good, because it has lots of components allowing users to build complex applications.
- Bad, because it has limited design options.

### **Option 5:** UI Kitten
- Good, because it is easy to use and has simple API.
- Good, because it is open source meaning it is free to use and contribute ideas.
- Bad because it has limited documentation.
- Bad, because it has limited design options.

## More Information

All UI's have pros and cons similar to each other, what stands out about React Native is we have most usage out of it compared to the other options, and it is free for us.
We can jump in without having to learn how to use a new UI toolkit.
