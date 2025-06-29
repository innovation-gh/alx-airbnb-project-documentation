 Airbnb Clone  Data Flow Diagram (DFD)

This document explains the Data Flow Diagram (DFD) that represents how data moves within the Airbnb Clone backend system. It covers the flow of information between external entities, internal processes, and data stores.

 Directory Structure




  Purpose of the DFD

The DFD provides a highlevel overview of:
 External entities like users and payment gateways
 Core processes like registration, property listing, booking, and payment
 Data stores such as user profiles, property listings, bookings, and payments
 Data flow between all components of the system



  Key Components in the DFD

 1. External Entities
 Guest: Registers, logs in, searches, books, and pays
 Host: Manages properties and bookings
 Admin: Oversees listings and user activity
 Payment Gateway: Handles external payment processing



 2. Processes
 User Authentication
 Property Listing Management
 Booking Management
 Payment Processing
 Review System
 Admin Moderation



 3. Data Stores
 User Database: Stores user credentials, roles, and profiles
 Property Database: Contains listings with details and images
 Booking Database: Tracks booking records and statuses
 Payment Records: Stores transaction logs and statuses
 Review Store: Holds guest feedback and ratings



 4. Data Flow Summary
 A guest inputs registration data → stored in User DB
 A host lists property info → stored in Property DB
 A guest books a listing → Booking info saved in Booking DB
 Payment details sent to Payment Gateway → confirmation returned
 Review input → saved in Review Store



 Diagram

See the visual representation here:

 `dataflowdiagram/dataflow.png`



 Notes

 The DFD was created using [Draw.io](https://draw.io) and exported in `.png` format.
 This diagram helps visualize how the backend handles and routes data.



 Version Control

 Last updated: `June 29, 2025`
 Author: `Destiny Felix`
