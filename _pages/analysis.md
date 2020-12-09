---
permalink: /analysis/
title: "Analysis"
---

## Background

The Ohio State University Medical Center is part of the Ohio State Health Network, a major health network throughout the state, including 16 health centers. OSUMC provides a wide variety of healthcare services and is a major source of healthcare for many Ohio residents.  
<br>
Healthcare is undergoing a transition.  Care is more patient-specific and tailored to an individual’s needs.  When healthcare professionals fail to recognize, acknowledge, or respect important aspects of cultural norms then they have not provided the most patient-focused care that they can.

## Problem

Cultural awareness is not something that is intuitive to all healthcare professionals.  When cultural aspects of a patient’s life are shown to be of high importance, then it reflects the high level of compassion that our organization aims to provide.  
<br>
Providers will be more comfortable approaching situations where they are unsure about how to interact, thus improving their ability to provide care.  
<br>
The organization will be viewed positively by a wide range of cultural groups, small and large, and members of those groups will likely seek care at the said organization because of positive word of mouth reviews. 


## Proposed Solution

An application that healthcare professionals can use to search for different cultural preferences/norms so they can meet the cultural needs of their client/patient. This will be a collection of information with different explanations, definitions, terms, and any other pertinent information that would enhance patient care.  
<br>
This app will improve the experiences of different cultural groups when they receive healthcare, but also serve as a teaching/learning tool that can help grow cultural awareness outside of healthcare.


## Software Requirements

### Functional Requirements
- The system must be able to show users a snapshot of and detailed information about a selected culture’s medical norms
- The system must allow administrators to create and remove new cultural groups
- The system must allow administrators to create, update and remove cultural norm information
- The system must be able to allow users to download a selected culture’s medical norm information
- The system must be usable offline
- The system must be usable on the move
- The user interface of the system must be able to clearly communicate with users cultural norm information

### Non Functional Requirements
#### Availability
- The application must be available round the clock, if there is downtime the application should be back up and running within ten minutes

#### Performance
- The application must support many concurrent users: 50 requests per minute
- The system should take no more than 5 seconds to load data after an API request

#### Modifiability/Scalability
- The application should remain responsive at 100 requests per minute. (performance guarantees do not apply at these rates)
- A selected culture’s data should be easily modifiable by an administrator

#### Security
- All data should be archived and stored for at least one month
- User/Admin data must be kept private

#### Testability
- Components of the system should be tested with unit tests and integration tests where applicable to ensure components are functional and prevent regression
- The system should be tested with end-to-end tests to verify the components work as a whole

#### Usability
- Must support multiple platforms (latest iOS, latest Android OS, and modern web browsers)
- User interface should be intuitive
