# Christopher Leo Mervyn- Project Portfolio
___
## Project: PropertyFree

Given below are my contributions to the project.

Overview:

This document is a project portfolio that documents all contributions made to PropertyFree's development by Christopher.
___

## Description of Project:

PropertyFree is a real estate management application meant for property agents to organize their properties and meetings more efficiently.
Other application can keep track of meetings and schedules but there are relatively few applications that help track properties 
and associate them with meetings with clients.

For our project we hope to make it more streamlined for agents to keep track of their property and have clear information about those properties
and there clients.
___

##Developers of PropertyFree:

PropertyFree is developed by a group of second year Computer Science Students from the School of Computing, National
University if Singapore. This was developed for the team projects assignment fro the module CS2103 and is a
brown-field project adapting from existing projects.
___

## My Contributions to PropertyFree

* **Sort Meeting Feature**: Added a command to sort meetings either ascendingly or descendingly based on the meeting date.
* What it does: allows the user to sort the meetings in the meeting book according to the date of the meeting.
  * Justification: This feature improves the product significantly because a user might want to sort the list of meetings that he has so that it is easier for him to identify his next meeting easily.
  * Highlights: This enhancement affects the existing meeting book as the meetings will have to be stored after being sorted. It required an in-depth analysis of design alternatives. The implementation of this command was challenging as it required the sorting of all 3 types of meeting according to the date object attribute it has.


* **Add Meeting Feature**: Added a command to add 3 types of meetings, paperwork, admin and viewing types with various parameters such as Bidder Id, Property Id, Venue, Date, Start Time, and End Time to the meeting book.
* What it does: allows the user to add meetings in the meeting book based on the type of meeting he has.
* Justification: This feature improves the product significantly because a user will want to add meetings to the meeting book so that he can have an easy reference of all the upcoming meetings with clients that he has.
* Highlights: This enhancement affects the existing meeting book as the meetings will have to be stored after being added. It required an in-depth analysis of design alternatives. The implementation of this command was challenging as it required the storing of all 3 types of meeting and the various attributes that a meeting object has.

* **Edit Meeting Feature**: Added a command to edit one or more parameters of an existing meeting in the meeting book.
* What it does: allows the user to edit an existing meeting in the meeting book based on one or more parameters.
* Justification: This feature improves the product significantly because a user will want to edit meetings in the meeting book so that he can easily change the meeting details if needed.
* Highlights: This implementation was straight forward, but I wanted to enable more than one parameter to be edited and this was more challenging but it would improve the user's convenience significantly as the user could input all the edits into one command line instead of multiple command lines.

* **Meeting Attributes**: Added the various attributes for the meeting objects.
* What it does: Allows the user to add the various parameters to create a meeting object.
* Justification: This feature allows the user to make the meeting object with the various parameters.
* Highlights: The team discussed heavily on the kinds of parameters we should include for a meeting object that would be beneficial for a typical property agent.

* **Design**: Lead the technical aspect for the meeting entity.
* What: Designed most of the methods in model, storage and logic for meeting so that the meeting entity is easily refactored or tested.

* **Test**: Made the Junit tests for meeting and meeting commands.  
* What: Implemented the various tests for all the MeetingCommandParser files and also for the meeting files under testutil.

* **Meeting Commands**: Added the commands for the meeting entity and also the tests that are associated with it.
* What it does: Creates the appropriate meeting command.

* **Code contributed**: [RepoSense link](https://nus-cs2103-ay2021s1.github.io/tp-dashboard/#breakdown=true&search=christopher&sort=groupTitle&sortWithin=title&since=2020-08-14&timeframe=commit&mergegroup=&groupSelect=groupByRepos&checkedFileTypes=docs~functional-code~test-code~other&tabOpen=true&tabType=authorship&tabAuthor=munharsha&tabRepo=AY2021S1-CS2103-W14-1%2Ftp%5Bmaster%5D&authorshipIsMergeGroup=false&authorshipFileTypes=docs~functional-code~test-code)

* **Project management**:
  * Managed releases `v1.1` - `v1.4` (4 releases) on GitHub

* **Enhancements to existing features**:
  * Updated the GUI color scheme (Pull requests [\#33](), [\#34]())
  * Wrote additional tests for existing features to increase coverage from 88% to 92% (Pull requests [\#36](), [\#38]())

* **Documentation**:
  * User Guide:
    * Added documentation for the features `edit` and `sort` [\#72]()
    * Did cosmetic tweaks to existing documentation of features `clear`, `exit`: [\#74]()
  * Developer Guide:
    * Added implementation details of the `delete` feature.

* **Community**:
  * PRs reviewed (with non-trivial review comments): [\#12](), [\#32](), [\#19](), [\#42]()
  * Contributed to forum discussions (examples: [1](), [2](), [3](), [4]())
  * Reported bugs and suggestions for other teams in the class (examples: [1](), [2](), [3]())
  * Some parts of the history feature I added was adopted by several other class mates ([1](), [2]())

* **Tools**:
  * Integrated a third party library (Natty) to the project ([\#42]())
  * Integrated a new Github plugin (CircleCI) to the team repo

* _{you can add/remove categories in the list above}_
