# A stack of useful definitions and phrases #
Not in the alphabetical order, yet.

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

- [x] Add description
- [ ] Insert graphical representation here



### Account Object ###

- [ ] Add description
- [ ] Insert graphical representation here



### Ad hoc Action ###
Properties mode update as a result of user (or system) interaction with it.

Example:
*	User --> object 1 - is required to add number of cars --> property of object 2 - she or he owns --> ad hoc action. User is presented with Todo --> object 3 - and taken to view with input field in specific editing mode to complete the action. Once the update is saved the result is being logged and action is completed.

Ad hoc actions are:
*	Always compiled with use of [user object](#user-and-system-object) or it's special case, [system object](#user-and-system-object).
*	One of two ways (together with [views](#views)) to browse "Objective D" applications.
*	Triggers for new actions when completed, therefore ad hoc actions are usually [chained](#chained-actions) with following up actions. 
*	Part of the [smalltalk](#smalltalk) (together with chained actions and within one use case).

- [x] Add description
- [ ] Insert graphical representation here



### Chained Actions ###

- [ ] Add description
- [ ] Insert graphical representation here



### Smalltalk ###
Flow of all actions (ad hoc and chained) within one use case.


- [ ] Add description
- [ ] Insert graphical representation here



### Property ###

- [ ] Add description
- [ ] Insert graphical representation here



### Property Mode ###

- [ ] Add description
- [ ] Insert graphical representation here



### Views ###

- [ ] Add description
- [ ] Insert graphical representation here



### Extract ###

- [ ] Add description
- [ ] Insert graphical representation here