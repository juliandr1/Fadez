Original App Design Project - README Template
===

# Fadez

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
A social media app specifically designed to help people connect and interact with local barbers. Users can rate barbers and provide feedback to others who are looking for select styles. Both barbers and users can post images of their haircuts, in order to give others an idea of the type of styles they want. Through the search process, users can filter by location, style, and price.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:**
- **Mobile:**
- **Story:**
- **Market:**
- **Habit:**
- **Scope:**

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* Users can view and post images and reviews of different barbers.
* Users can message or book appointments with barbers from the app.
* Users can login, choosing between a regular account and a barber account.

**Optional Nice-to-have Stories**

* Users can get directions to the barber's location (barbershop or studio), via Google Maps.
* Barbers can connect their other social media pages to the app.
* Clean and accessible UI design.
* Notifications remind users of upcoming appointments.
* Users can create an account through linking external accounts: Google, Facebook, Snapchat, etc.

### 2. Screen Archetypes

* Login screen
   * Users can login
* Account registration screen
   * New users can create an account, choosing a regular account or a barber account.
* Search screen
   * Users can view barbers in their area
   * Barbers' ratings and location shown on their 
* Barber Detailed Screen
   * Users can view the gallery of barber images and  all reviews
* Appointment Screen
   * Users can book appointments with barber

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Home (Account information)
* Search Barbers
* Post image (Review)

**Flow Navigation** (Screen to Screen)

* Login
   => Registration (if not account created)
   => Home
* Registration
   => Login (if account already created)
* Search screen
   => Barber Detailed Screen 
   => Appointment Screen
   => Home
* Barber Detailed Screen
   => Appointment Screen
   => Search screen
   => Home
* Appointment Screen
   => Barber Detailed Screen
   => Search screen

## Wireframes
[Add picture of your hand sketched wireframes in this section]
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
