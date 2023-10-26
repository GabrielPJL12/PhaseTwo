---
# Configuration for the Jekyll template "Just the Docs"
parent: Decisions
title: Hardware Selection for Android Calculator App

status: accepted
date: 2023-10-26
deciders: Cyril Dizon
---
# Hardware Selection for Android Calculator App

## Context and Problem Statement

We are developing an Android calculator app that aims to provide a high-performance and user-friendly experience. Our target audience uses a variety of Android devices with different hardware specifications. The app includes standard calculator functions, scientific computations, and graph plotting. The problem is: How do we select the right hardware for testing and optimizing our app to ensure that it performs well across a wide range of Android devices?

## Decision Drivers

* **Device Variety**: Ensuring the app performs well on both low-end and high-end devices.
* **Performance**: The app should have fast response times, especially for complex calculations and graph plotting.
* **Cost**: Minimizing the cost of acquiring multiple devices for testing.
* **Market Share**: Prioritizing testing on devices that have significant market share to reach a larger audience.
* **Future-Proofing**: Ensuring the selected hardware remains relevant for app testing in the foreseeable future.

## Considered Options

* **Option 1: Use Emulators for Testing**
* **Option 2: Purchase a Variety of Physical Devices**
* **Option 3: Combination of Emulators and Select Physical Devices**

## Decision Outcome

Chosen option: "Option 3: Combination of Emulators and Select Physical Devices", because it strikes a balance between cost, performance testing, and covering a wide range of devices.

### Consequences

* Good, because we can simulate a variety of devices and Android versions using emulators.
* Good, because testing on physical devices ensures real-world performance validation.
* Bad, because maintaining physical devices and keeping them up to date can incur additional costs and efforts.
* Bad, because emulators might not perfectly replicate the performance characteristics of real devices.

## Pros and Cons of the Options

### Option 1: Use Emulators for Testing

Leverage Android emulators to simulate a variety of devices and Android versions.

* Good, because it’s cost-effective; no need to purchase physical devices.
* Good, because we can quickly switch between different device profiles and Android versions.
* Bad, because emulators might not provide accurate performance metrics.
* Bad, because certain hardware-specific issues might go undetected.

### Option 2: Purchase a Variety of Physical Devices

Acquire a range of Android devices for testing.

* Good, because testing on real hardware ensures accurate performance metrics.
* Good, because it helps in detecting hardware-specific issues.
* Bad, because it can be expensive to acquire a wide variety of devices.
* Bad, because devices can quickly become outdated, requiring further investment.

### Option 3: Combination of Emulators and Select Physical Devices

Use a mix of emulators and a select number of physical devices for testing.

* Good, because it provides a balance between cost and testing accuracy.
* Good, because we can cover a wide range of devices and Android versions.
* Bad, because there is still a cost associated with acquiring and maintaining physical devices.
* Neutral, because while it provides a comprehensive testing approach, it might require more setup and management efforts.

## More Information

This decision should be revisited annually to ensure that our testing hardware remains relevant and adequately covers the range of devices used by our target audience. This decision was validated through a cost-benefit analysis and a review of market share data for Android devices. The team has agreed to allocate budget for acquiring new physical devices as needed and to regularly update emulator profiles to reflect the current Android device landscape.

