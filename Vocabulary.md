# A stack of useful definitions and phrases #
Pilled up in order of importance not alphabetically.

<br/>

### Object ###
A container of properties (or a single [property](#property)) describing a meaningful entity for the user within the application.

Examples:
*	Document --> object, Page count --> property as number
*	User --> object, Name --> property as string
*	Email --> object, Attachment --> property as bool

Objects are:
*	Displayed in views based on their properties.
*	Linked with each other via connections or property [extraction](#extract).
*	Complied into [actions](#ad-hoc-action).   

- [x] Add description
- [ ] Insert proper graphical representation here

<br/>

### User and System Object ###
Both are a special cases of the [object](#object) - if linked to the [account object](#account-object) they inherit executive function within the application and become an essential part of the [actions](#ad-hoc-action) functionality.  

Examples:
*	Morgan Summers --> user object 1, with Name --> property 1, and Surname --> property 2.
*	Robo 111 --> system object 1, with Name --> property 1, and ID number --> property 2.

User Objects are:
*	Not mandatory part of the application.
*	Same as objects, containers of properties with all, the same characteristics.

System Objects are:
*	Functions or preprogrammed processes, executing automated functions in the application.
*	Not mandatory part of the application.
*	Same as objects, containers of properties with all, the same characteristics.
*	Non interactive parts of the view as opposed to [properties](#property), the interactive part of the view.

- [x] Add description
- [ ] Insert graphical representation here

<br/>

### Account Object ###
Executive set of properties of the [user object](#user-and-system-object).

Example:
*	If [user object](#user-and-system-object) is like a profile, than the account object is a login functionality.

Account Objects are:
*	At least/usually constructed of the user name and password (but could include any number of other properties, like permissions, URLs...)
*	Applying executive right for users to perform actions and view properties in different [property modes](#property-mode).
*	Part of the [smalltalk](#smalltalk) process together with [actions](#ad-hoc-action) and [chained actions](#chained-actions).

- [x] Add description
- [ ] Insert graphical representation here

<br/>

### Ad hoc Action ###
Properties mode update as a result of user (or system) interaction with it.

Example:
*	User --> object 1 - is required to add number of cars --> property of object 2 - she or he owns --> ad hoc action. User is presented with Todo --> object 3 - and taken to view with input field in specific editing mode to complete the action. Once the update is saved the result is being logged and action is completed.

Ad hoc actions are:
*	Always compiled with use of [user object](#user-and-system-object) or it's special case, [system object](#user-and-system-object).
*	One of two ways (together with [views](#views)) to browse "Objective D" applications.
*	Triggers for new actions when completed, therefore ad hoc actions can be [chained](#chained-actions) with following up actions. 
*	Part of the [smalltalk](#smalltalk) (together with chained actions and within one use case).

- [x] Add description
- [ ] Insert graphical representation here

<br/>

### Chained Actions ###
When one action occurs as a result of another action being completed.

Example:
*	Action 1 --> User adds on number of cars she or he owns. This action is being logged as completed and next action is being created based on the [smalltalk](#smalltalk) rules. Now, his insurance supplier needs to attach offers for each car --> action 2.

Chained actions are:
*	Part of the [smalltalk](#smalltalk) together with [ad hoc actions](#ad-hoc-actions) and within one use case.

- [x] Add description
- [ ] Insert graphical representation here

<br/>

### Smalltalk ###
Flow of all actions (ad hoc and chained) within one [user story](#user-story).

Example:
*	Use case --> As a car owner I want to add cars I own to my profile to get suggested insurance offers from my supplier. I act on the action --> add number of cars I own to my profile (possibly with additional properties like a production year, engine power...etc). The supplier acts on his/her action - and adds on the insurance offers for each of my cars. I act on the new action created as a result of the supplied offers and choose the plan I want to go with. Supplier finally acts on the his/her action and verifies my choice.

Smalltalk is:
*	Set of rules applied to objects and it's properties creating new actions as a result of already completed actions.
*	It's always restricted to use case for clarity of consecutive actions.
*	It's a flow, therefore it has a beginning and the end.

- [x] Add description
- [ ] Insert graphical representation here

<br/>

### User Story ###

- [ ] Add description
- [ ] Insert graphical representation here


<br/>

### Property ###
Descriptive element of the object.

Examples:
*	Input field --> data element.
*	Submitted, Accepted state - status element, bool operator.
*	Created by User --> connection to another object.

Properties are:
*	Part of the objects, don't exist on their own.
*	Made of [property modes](#property-mode).
*	Interactive part of the [view](#view), [object](#object) and interface, because of the [property modes](#property-modes).

- [x] Add description
- [ ] Insert graphical representation here

<br/>

### Property Mode ###
State of the [property](#property).

Examples for:
*	Data element (input field) --> edit/published modes
*	Status element (bool operator) --> change to/locked modes
*	Connection (relation to another object) --> open access/private modes

Property Modes:
*	Determine the visual representation of the [property](#property) in the interface.
*	Are the ultimate interactive part of the [view](#view), [object](#object), [property](#property) - user interface.

- [x] Add description
- [ ] Insert graphical representation here

<br/>

### Views ###
Objects grouped by their properties.

Examples:
*	Show to user all the documents created by him --> show all the objects with property 1 (connection type)
*	Show to user all the photos from today --> show all the objects with property 1 (data type)

Views are:
*	Flexible.
*	Similar to filters in the results aspect.
*	Higher level of information organisation than objects.
*	Interactive parts of the application if there is more than one.

- [x] Add description
- [ ] Insert graphical representation here

<br/>

### Extract ###

- [ ] Add description
- [ ] Insert graphical representation here











