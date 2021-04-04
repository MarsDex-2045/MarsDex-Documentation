# MarsDex
Welcome to the MarsDex Project. This README.md is a starting point through the MarsDex project and will guide you through the project.
## Index
- [Documentation](https://github.com/BT-Creator/MarsDex-Documentation)
- [Client](https://github.com/BT-Creator/MarsDex-Client)
- [Server](https://github.com/BT-Creator/MarsDex-Server)
  
## Introduction
MarsDex is a monitoring & index service to keep track of resources on Mars. 

Because of the harsh environmental factors on Mars, resource usage needs to be optimized, and the exchange of these needs to be easy.
MarsDex gives Mars Residents, company and government workers the tools to manage, exchange and keep track of resources on Mars.
With our extensive map of Mars & Transports routes, detailed lists of resources and easy-to-use marketplace, you can manage your resources with ease and enjoy the Martian view.

![MarsDex Overview](markdown/MarsDex%20Overview.gif)
## (Proof Of) Concept
Below you'll find a table, detailing which parts are implemented in the POC and which are conceptual.

### General
|Feature|Included in wireframes?|Included in POC?|
|---|---|---|
|Global Map|✅|✅|
|Colony Listing|✅|✅|
|Colony Details|✅|✅|
|Contact From|✅|✅|
|About us|✅|✅|

### Mars Resident exclusive
|Feature|Included in wireframes?|Included in POC?|
|---|---|---|
|N/A|N/A|N/A|

### Company exclusive
|Feature|Included in wireframes?|Included in POC?|
|---|---|---|
|Company Overview|✅|✅|
|Shipment Listing|✅|✅|
|Resource Listing|✅|✅|
|Home Colony Resource Listing|✅|✅|
|My Resource Listing|✅|✅|
|Adding resource|✅|✅|
|Editing resource|✅|✅|
|Deleting resource|✅|✅|
|Request Resource|✅|❌|
|Placing Bid on Resource request|✅|❌|
|Choosing order deliverer|✅|❌|
|Viewing bids on Resource Request|✅|❌|
|Viewing Resource Request to complete|✅|❌|
|Marking order as in transit|✅|❌|

### Government exclusive
|Feature|Included in wireframes?|Included in POC?|
|---|---|---|
|Viewing Transports|✅|❌|
|Viewing Alerts|✅|❌|
|Sending Alerts|✅|❌|
|Modifying colony policies|✅|❌|

### Bonus features
In addition to these features, the following bonus features were also implemented in the POC:
- Geolocation ("You are here" marker on the global map)
- CSS animations (Found throughout the project)
- Service Worker (  `sw.js`), you'll also find that it's registered in your dev tools)
- Push Notifications (This triggers if a resource is lower than 500 KG, a push notification will send to the server)

## Deliverables
The Documentation repository contains all our deliverables of the project, such as:
- [Flowcharts](https://github.com/BT-Creator/MarsDex-Documentation/tree/master/deliverables/Flowcharts)
- [User Case Diagrams](https://github.com/BT-Creator/MarsDex-Documentation/tree/master/deliverables/UCD)
- [User Tests](https://github.com/BT-Creator/MarsDex-Documentation/blob/master/deliverables/User%20Testing/User%20tests.md)
- [UX Reports](https://github.com/BT-Creator/MarsDex-Documentation/tree/master/deliverables/User%20Testing)
- [C4 Diagrams](https://github.com/BT-Creator/MarsDex-Documentation/tree/master/deliverables/c4)
- [Wireframes](https://xd.adobe.com/view/68533c7b-e53d-4526-bacd-679ff922f22b-3d00/)
- [User Stories](https://github.com/BT-Creator/MarsDex-Documentation/wiki/User-Stories)
- [Business Case](https://docs.google.com/document/d/1x_26O2OHVEUT6JJ8yd2VA0xuL1GM5yeQH7PRJpdIDbM/edit?usp=sharing)

All of these items are located in the `deliveries` directory.

*The `markdown` directory is used to load resources to this README.md*

***Note:** We have chosen to save most of the deliverables in SVG format. This was because Git liked this more and there was less quality loss. But GitLab's preview will render our SVG wrong. Because of this, you'll need to open the SVG image in raw 
(You'll find this button in the right-hand side of the preview window, the button besides download.)*  

### Application requirements
In order to improve clarity, we've decided to summirize our [application requirements](https://github.com/BT-Creator/MarsDex-Documentation/wiki/Concept-Application-Requirements)
## What now?
In order to set up the application, you'll need to set up the server & the client locally. You'll need to [configure the server](https://github.com/BT-Creator/MarsDex-Server) and after that, you'll need [configure the client](https://github.com/BT-Creator/MarsDex-Client).

## Credits
This project has been made by the following people:
- Yarne Savaete *(Discord-ID: `Derp.#8570`)*
- [Benjamin Robbe](https://www.facebook.com/profile.php?id=100012320041578)
- Rutger Heyvaert
- [Bo Robbrecht](https://www.linkedin.com/in/borobbrecht/)
