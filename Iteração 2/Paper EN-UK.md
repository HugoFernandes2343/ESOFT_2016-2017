# Project Paper (EN-UK)

## Answers to open questions
* A new user is valid and unique if the following two conditions are meet:
  a. the _email_ address is valid and no other user is using it,
  b. the _username_ is not used by by any other user.
* All system's users are identified by the user's _email_ address or _username_.
* The event managers are defined by other event managers. At the begin of the system operation, there is at least one event manager.
* At each event creation, at least two organizers must be defined for the event.
* In the same event, the same user cannot act as organizer and FAE.
* The assignment process consists in assigning each submitted application to one or more FAE for evaluation.

## New requirements

There are 2 types of events:

- Expositions, in which the goal is participants to make commercial transactions;
- Congresses, is a forum for exchange of knolwedge and competencies between participants.

The organizers which to organize workshops in scope of congresses.

Near the application submission deadline, the system may be overloaded, hence scalability should be addressed.

At the application submission deadline (defined), the organizers trigger the application assignment process. Once finished, the evaluation process starts.

As a way to support the assignment process, several algorithms are provided, considering the characteristics of the event and FAE (e.g. the number of FAE requested for each application, the maximum number of applications per FAE, similar distribution of evaluation load per FAE, the expertise of the FAE in organizing events at the fair center, the number of applications reviewed by the FAE at the fair center).

All the algorithms are capable to deal with events, but some of them are specific for expositions and other for congresses. The assignments can be changed by choosing diferent decision support algorithms, until the result is accepted by the organizer.

It sould be possible to add new algorithms throughout the life of the software, with minimum effort.

The software must be developed iteratively and incrementally, as well as to adopt design patterns (e.g. GRASP, SOLID patterns) and good coding practices (e.g. Camel case) and version control systems.
