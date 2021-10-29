Upark - Parking at UB

# UPark

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
This app relies on its target audience (students / faculty that park at the University at Buffalo) to help a user determine where they might be able to park on campus.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Utility
- **Mobile:** Yes
- **Story:** Parking at UB is terrible
- **Market:** People that need to park at the University at Buffalo's North Campus
- **Habit:** Daily use
- **Scope:** By Bulls, for Bulls

## Product Spec

### 1. Business Problem and User Base
The user base is anyone that needs to park on UB's North Campus. The problem is that parking is difficult during certain periods of the day. Lots fill up at different times, and unless someone is willing to get to campus early, they might not know which parking lots still have open spots. Spending time looking for a spot, potentially across lots, is frustrating, time consuming, and might make someone late for an obligation.

### 2. Description
This app relies on its users to track the relative status of each lot (empty, mostly empty, somewhat empty, less empty, full). It will use either incentives (badges) and/or push notifications to encourage users to participate in tracking the lots.


### 3. User Stories

**Required User Stories**

* Driver can select a parking lot using a list or tiles
    * Reason: There is more than one parking lot on campus
* Driver can view how full a parking lot is
    * Reason: To inform a driver's decision about where to park
* Driver can input data about the status of a parking lot
    * Reason: Data input is how the app tracks the status of each parking lot
* Driver can record their parking spot by lot
    * Reason: Drivers might forget where they park

**Optional User Stories**

* Search bar to search for lots on campus
    * Reason: Faster than scrolling through a list if the driver knows the name of the lot they want to park in
* Driver can see a map of the campus with the parking lot names
    * Reason: Driver might not know where a lot is
* Map uses coloring to show the rough emptiness of a lot
    * Reason: Driver can quickly see if a lot has potential spots
* Driver can place a tack on the map of where they parked
    * Reason: More specific than lot-based parking memory
* App collects data about lots to predict business at a time
    * Reason: Can inform driver about best time to leave their location
* Parking lot tiles are colored to show busyness
    * Reason: The driver can see which lots are busy or less busy quickly on the app's starting page
* Dark mode
    * Reason: Every1 <3's dark mode
* Settings
    * Reason: Allow driver to adjust preferences

### 2. Screen Archetypes

What screens will the user see?
* Loading screen with app icon
    * Reason: No one wants to see a blank screen when their app is starting
* Initial screen with tiles, one per lot
    * Reason: Need a way to show the lots, tiles look better than a list
* Lot-specific screen for each tile/lot
    * Reason: This screen will show more information about a given lot, and allow the user to contribute to the data on that lot

**Screens for Optional User Stories**
* Map showing UB's campus with parking lots accentuated
    * Reason: Some drivers might like to see the lots visually, as opposed to tile-y
* Settings
    * Reason: Convenient place for drivers to access their preferences

### 3. Navigation

* App logo (launch screen)
* Tile screen (tab nav)
    * Lot-specific page (flow nav)
* Map (OPTIONAL, tab nav)
* Settings (OPTIONAL, tab nav)

## Wireframes
![](https://i.imgur.com/W9Moc9O.png)



## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
