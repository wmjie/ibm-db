

# Contributing to the IBM\_DB\_Python project #

## Overview ##

This section provides the guidelines for contributing code to the IBM\_DB\_Python project.

1.	[Why Contribute?](http://code.google.com/p/ibm-db/wiki/Contributions#Why_Contribute?) section discusses the benefits of contributing code to  IBM\_DB\_Python project.

2.	[General Contribution Requirements](http://code.google.com/p/ibm-db/wiki/Contributions#General_Contribution_Requirements)  section discusses the conditions a contribution needs to satisfy in order to be considered for inclusion.

3.	[Legal Issues](http://code.google.com/p/ibm-db/wiki/Contributions#Legal_Issues)  section discusses the legal implications of your contribution.

## Why Contribute? ##

IBM\_DB Python project allows Python based applications to use DB2 and Informix (IDS) Data Servers. Our goal is to provide top of the line support on all widely used platforms. By contributing your code to IBM\_DB Python project, you will get the benefit of continuing improvement by the team and the community, as well as testing and multi-platform portability. In addition, it saves you from having to re-merge your own additions into IBM\_DB each time you upgrade to a new release.


## General Contributions Requirements ##
We will be glad to take a look at the code you wish to contribute to IBM\_DB Python project. We cannot guarantee that the code will be included. Contributions of general interest and written according to the following guidelines have a better chance of becoming a part of IBM\_DB Python project.
For any significant new functionality, contact the IBM\_DB Python project development team through IBM\_DB\_Python google-groups (http://groups.google.com/group/ibm_db) first, and discuss the features, design and scope of the possible contribution. This helps ensure that the contribution is expected and will be welcome, that it will fit in well with the rest of IBM\_DB Python project, and that it does not overlap with other development work that may be underway.
For Bug Fixes, open a defect in the IBM\_DB\_Python google-code issue database (http://code.google.com/p/ibm-db/issues/list) and attach your patch to it.
While you are considering contributing code to IBM\_DB Python project, make sure that the legal terms are acceptable to you and your organization.
Here are several things to keep in mind when developing a potential contribution to the IBM\_DB Python project:
1.	During implementation, try to mimic the style already present in the IBM\_DB Python project source code.
2.	Always provide enough test code and test cases. It is endeavor that  the drivers/adapters are well tested. Make sure that your tests are integrated into test suite. New tests and the complete test suite should pass or give expected results.
3.	Test on more than one platform. It is good to combine testing on Windows with testing on Linux, Mac OS X or another Unix platform. It is always good to try to mix big and little endian platforms.
4.	Each contribution should contain everything that will allow building, testing and running IBM\_DB with the contribution. This usually includes: source code, build files and test files.

## Legal Issues ##
> In order for your code to be contributed, you need to assign to IBM joint copyright ownership in the contribution. You retain joint ownership in the contribution without restriction. (For the complete set of terms, please see the forms mentioned below.)
The sections below describe two processes, for one-time and ongoing contributors. In either case, please sign the form(s) and send the scanned copy to IBM (opendev@us.ibm.com) for review. After review, IBM team will look at the code for evaluation.
Please consult a legal representative if you do not understand the implications of the copyright assignment.

### One-Time Contributors ###

If you would like to make a contribution only once or infrequently, please use the [IBM\_DB\_Python Joint Copyright Assignment – onetime contribution](http://ibm-db.googlecode.com/files/IBM_DB_Python%20Joint%20Copyright%20Assignment%20-%20onetime.pdf) form. The contribution will be identified by a bug ID which is unique to the contribution and entered into the form. Therefore, please make sure that there is an appropriate bug (or Request For Enhancement) in the IBM\_DB\_Python google-code issue database (http://code.google.com/p/ibm-db/issues/list), or submit one. You should also attach your contribution to the issue the bug/issue database (in patch format)

The code contribution will be evaluated by IBM team. The IBM team may request updates, for example for better conformance with the IBM design principles, coding and testing guidelines, or performance. Such updates can be contributed without exchanging another form: An IBM team member commits related materials into the google-code source code repository using the same bug ID that was entered into the copyright assignment form.

### Ongoing Contributors ###

If you are interested in making frequent contributions to the IBM\_DB\_Python project, then the IBM team may agree to invite you as an ongoing contributor. Ongoing contributors may be individuals but are more typically expected to be companies with one or more people (“authors”) writing different parts of one or more contributions.

In this case, the relationship between the contributor and the IBM team is much closer: One or more authors belonging to the contributor may have commit access to the IBM\_DB\_Python project’s google-code source code repository. With this direct access come additional responsibilities including an understanding that the contributor will work to follow the technical guidelines for contributions, and agreement to adhere to the terms of the copyright assignment forms for all future contributions.

The process for ongoing contributors involves two types of forms: Initially, and only once, an ongoing contributor submits a [IBM\_DB\_Python Joint Copyright Assignment – ongoing contributor](http://ibm-db.googlecode.com/files/IBM_DB_Python%20Joint%20Copyright%20Assignment%20-%20ongoing.pdf) form agreeing to essentially the same terms as in the one-time contributor form, for all future contributions.

The contributor must also send another form, [Addendum to IBM\_DB\_Python Joint Copyright Assignment for ongoing contributor: Authors](http://ibm-db.googlecode.com/files/IBM_DB_Python%20Joint%20Copyright%20Addendum%20-%20ongoing.pdf), for the initial set and each addition of authors to IBM\_DB\_Python contributions, before any contributions from these authors are committed into the IBM\_DB\_Python projects’ google-code source code repository. (Only new, additional authors need to be listed on each such form.) The contributor agrees to ensure that all of these authors agree to adhere to the terms of the associated Joint Copyright Assignment by Ongoing Contributor Agreement.

Some of an ongoing contributor's authors may be given commit access to the IBM\_DB\_Python project’s google-code source code repository. Their committer IDs need to be established before completing the Authors Addendum form, so that these committer IDs can be entered there. (The committer IDs will be activated only after the form is received.)

Committer authors commit materials directly into the appropriate parts of the IBM\_DB\_Python project’s google-code source code repository. Contributions from an ongoing contributor are identified by their association with the contributor's committer IDs.