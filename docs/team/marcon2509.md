# Marcus Duigan Xing Yu - Project Portfolio

___

## Project: PropertyFree

Given below are my contributions to the project.

Overview:

This document is a project portfolio that documents all contributions made to PropertyFree's development by Marcus.

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
University if Singapore. This was developed for the team projects assignment for the module CS2103 and is a
brown-field project adapting from existing projects.

___

## My Contributions to PropertyFree

### New Features

* **Add Bid Feature**: Added the ability to add a bid to a list of bids.
  * What it does: allows the user to add a bid for a property with a link to a property Id and a bidder Id.
  * Justification: This feature is a necessary feature to allow the user to manage bids for a property.
  * Highlights: The add-bid feature will automatically slot the bid in Alpha numeric order so the displayed list is always organized.
  * Pull request: [#76](https://github.com/AY2021S1-CS2103-W14-1/tp/pull/76)
  
* **Edit Bid Feature**: Added the ability to edit a bid in the list of bids.
  * What it does: allows the user to edit a bid by changing the details of the bid.
  * Justification: This feature greatly improves the user convenience by allowing the user to correct mistakes in a bid rather than deleting the bid.
  * Highlights: The edit-bid feature will automatically slot the bid in Alpha numeric order so the displayed list is always organized.
  * Pull request: [#161](https://github.com/AY2021S1-CS2103-W14-1/tp/pull/161)
  
* **Find Bid Feature**: Added the ability to find a specific bid in the list of bids.
  * What it does: allows the user to find a bid based on keywords specified.
  * Justification: This feature greatly improves the user convenience by allowing the user easily find a specific bid.
  * Highlights: the find bid command can find a bid using the property id, bidder id or the bid amount.
  * Pull request: [#161](https://github.com/AY2021S1-CS2103-W14-1/tp/pull/161)
 
* **Tab Feature**: Added tabs to the UI to better display all the lists.
  * What it does: displays the property, bidder, seller, bid lists in a presentable manner.
  * Justification: This feature greatly improves the user convenience by allowing the user to easily switch between lists.
  * Highlights: the tabs automatically switch to a tab if the command used is related to the tab.
  * Pull request: [#76](https://github.com/AY2021S1-CS2103-W14-1/tp/pull/76)
  
* **Delete Bid Feature**: Added the ability to delete a specific bid from the list of bids.
  * What it does: allows the user to delete a bid based on the index in the list.
  * Justification: This feature is a necessary feature to allow the user to remove a bid once it is not necessary.
  * Highlights: the delete bid command can only delete based on the index.
  * Pull request: [#161](https://github.com/AY2021S1-CS2103-W14-1/tp/pull/161)
  
* **List Bid Feature**: Added the ability to display the list of bids.
  * What it does: allows the user to display the list of bids.
  * Justification: This feature is a necessary feature to allow the user navigate to the list of bids or clear the filtered bids list.
  * Highlights: the list bid command will change the tab to the bid list.
  * Pull request: [#76](https://github.com/AY2021S1-CS2103-W14-1/tp/pull/76)
  
* **Auto-Sort Feature**: Added the ability to automatically sort the bid list without the need of a command.
  * What it does: allows the user to always obtain a sorted bid list
  * Justification: This feature greatly improves the user convenience by allowing the user to always have a sorted list.
  * Highlights: It will auto sort when a bid is added or edited.
  * Pull request: [#200](https://github.com/AY2021S1-CS2103-W14-1/tp/pull/200)

<div style="page-break-after: always;"></div>

* **Code contributed**: [RepoSense link](https://nus-cs2103-ay2021s1.github.io/tp-dashboard/#breakdown=true&search=marcon&sort=groupTitle&sortWithin=title&since=2020-08-14&timeframe=commit&mergegroup=&groupSelect=groupByRepos&checkedFileTypes=docs~functional-code~test-code~other&tabOpen=true&tabType=authorship&tabAuthor=Marcon2509&tabRepo=AY2021S1-CS2103-W14-1%2Ftp%5Bmaster%5D&authorshipIsMergeGroup=false&authorshipFileTypes=docs~functional-code~test-code~other)

* **Project management**:
  * Managed releases `v1.1` - `v1.4` (4 releases) on GitHub
  * Integration of `CodeCov` 
  * Managed overall UserGuide.md to ensure standardization and proper formatting

* **Enhancements to existing features**:
  * Wrote additional tests for existing bid features to increase coverage. Pull requests: [#262](https://github.com/AY2021S1-CS2103-W14-1/tp/pull/262), [#150](https://github.com/AY2021S1-CS2103-W14-1/tp/pull/150), [#200](https://github.com/AY2021S1-CS2103-W14-1/tp/pull/200/files?file-filters%5B%5D=.java&file-filters%5B%5D=.json)
  * Wrote tests for other features. Pull requests: [#262](https://github.com/AY2021S1-CS2103-W14-1/tp/pull/262)

* **Documentation**:
  * User Guide:
    * Added documentation for the bid features
    * Added table of command summary for easier reference
    * Did cosmetic tweaks to existing documentation of all bid features
    * Reviewed and standardized entire user guide. Pull requests: [#283](https://github.com/AY2021S1-CS2103-W14-1/tp/pull/283), [#286](https://github.com/AY2021S1-CS2103-W14-1/tp/pull/286/files)
  * Developer Guide:
    * Added implementation details for the general `add` and `list` feature. Pull request: [#297](https://github.com/AY2021S1-CS2103-W14-1/tp/pull/297)
    * Added implementation details for the specific bid auto sort feature and bids/meetings validity check feature. Pull request: [#297](https://github.com/AY2021S1-CS2103-W14-1/tp/pull/297)
    * Updated Overall Architecture model and description. Pull request: [#297](https://github.com/AY2021S1-CS2103-W14-1/tp/pull/297)

* **Community**:
  * PRs reviewed (with non-trivial review comments) outside of practical exams for other teams (pull requests [#245](https://github.com/AY2021S1-CS2103T-W16-4/tp/issues/245),
   [#247](https://github.com/AY2021S1-CS2103T-W16-4/tp/issues/247), [#248](https://github.com/AY2021S1-CS2103T-W16-4/tp/issues/248)).
  * Reported bugs and suggestions for team mates (pull request [#153](https://github.com/AY2021S1-CS2103-W14-1/tp/pull/153)).
  * Participated in forum discussion. Related Issues: [#214](https://github.com/nus-cs2103-AY2021S1/forum/issues/214), [#132](https://github.com/nus-cs2103-AY2021S1/forum/issues/132)
  , [#95](https://github.com/nus-cs2103-AY2021S1/forum/issues/95), [#67](https://github.com/nus-cs2103-AY2021S1/forum/issues/67), [#95](https://github.com/nus-cs2103-AY2021S1/forum/issues/95#issuecomment-682431502)

