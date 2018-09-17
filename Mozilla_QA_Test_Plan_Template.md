'''Approvals Required / Received'''

The following individuals are required to/have approved this Test Plan:

{| class="wikitable"
|-
! Name !! Title !! Department !! Approval Date !! Method
|-
|  || QA Reviewer || Product Integrity || Date || Email
|-
|  || Software Engineer || Engineering || Date || Email
|-
|  || EPM || Product Management || Date || Email
|}


'''Revision History'''

This section describes the modifications that have been made to this wiki page. A new row has been completed each time the content of this document is updated (small corrections for typographical errors do not need to be recorded).  The description of the modification contains the differences from the prior version, in terms of which sections were updated and to what extent.

{| class="wikitable" style="width:60%"
|-
! Date !! Version !! Author !! Description 
|-
| 11/23/2015 || 1.0 || Brindusa Tot || Created first draft
|-
| 10/05/2016|| 1.1 || Adrian Florinescu ||  Added point : 3.2 Channel dependent settings (configs) and environment setup 
|-
| 02/28/2017|| 1.2 || Brindusa Tot ||  Move Risk Assessment and Coverage upper in the test plan, under the Test Strategy chapter
|-
| 05/09/2017|| 1.3 || Brindusa Tot ||  Update content based on new train model (without Aurora)
|-
| 06/08/2017|| 1.4 || Rares Bologa ||  Added 'Approvals' area
|}

= Overview =
== Purpose ==
Detail the purpose of this document. For example:
* The test scope, focus areas and objectives
* The test responsibilities
* The test strategy for the levels and types of test for this release
* The entry and exit criteria
* The basis of the test estimates
* Any risks, issues, assumptions and test dependencies
* The test schedule and major milestones
* The test deliverables

== Scope ==
This wiki details the testing that will be performed by the project team for the <project name> project. It defines the overall testing requirements and provides an integrated view of the project test activities. Its purpose is to document:
* What will be tested
* How testing will be performed

== Ownership ==
 What resources are needed, and when (developers, QA, PMs working on the feature)
 
= Testing summary = 
== Scope of Testing ==
=== In Scope ===
Detail what is in scope from a testing perspective for the project team.

=== Out of Scope ===
Detail what is out of scope from a testing perspective for the project team. Note: if usability testing is not in the scope of testing feature.

= Requirements for testing =
== Environments ==
 Specify OSes that need to be covered
 Specify Devices that need to be covered
 Specify other configuration/environmental setup needed


== Channel dependent settings (configs) and environment setups ==
<div class="toccolours mw-collapsible mw-collapsed" style="width:auto">

=== Nightly ===
<div class="mw-collapsible-content">
text
</div>

=== Beta ===
<div class="mw-collapsible-content">
text
</div>

=== Post Beta / Release ===
<div class="mw-collapsible-content">
text
</div>
</div>

= Test Strategy = 
== Risk Assessment and Coverage ==

{| class="wikitable"
|-
! ID !! Description / Threat Description !! Covered by Test Objective !!  Magnitude !! Probability !! Priority !! Impact Score 
|-
| RAC-1 || Risk description 1 || TO-1 || 2-Moderate || 1-Unlikely || 3-High || 6
|-
| RAC-2 || Risk description 2 || TO-1 || 3-High || 3-Almost Certain || 3-High || 27
|-
| RAC-3 || Risk description 3 || TO-2 || 2-Moderate || 2-Possible || 3-High || 12
|}

'''Values:'''

* '''Magnitude:''' 1- Low , ''2-Moderate'', '''3-High''' 

* '''Probability:''' 1-Unlikely, ''2-Possible'', '''3-Almost Certain'''

* '''Priority:''' 1 - Low, ''2-Medium'', '''3-High'''

'''Impact Score Breakdown:''' 
* An impact value of 1, 2, 3, 4 would describe an area which although should be covered there aren't expected any discoveries of critical issues.
* An impact value of 6, 8, 9, 12 would describe an area in which we expect to find issues but those issues are not expected to be critical.
* An impact value of 18 or 27 would describe an area on which it is likely to find issues and those issues to be critical or blockers.

== Test Objectives ==
This section details the progression test objectives that will be covered. Please note that this is at a high level. For large projects, a suite of test cases would be created which would reference directly back to this master.
This could be documented in bullet form or in a table similar to the one below.

{| class="wikitable"
|-
! Ref !! Function !! Test Objective !! Evaluation Criteria !! Test Type !! RAC !! Owners 
|-
| 1 || Name of the feature or sub-function being tested || The objective the test is trying to demonstrate || The criteria that will be evaluated to demonstrate the test is successful || Manual/ Automation/ Regression/ Performance/ Usability/ Security/ Telemetry || RAC-1, RAC-2, RAC-3 || Eng Team
|-
| 2 || Repeat for each feature/sub-function || || || || ||
|-
| 3 || || || || || ||
|}

== Builds ==
This section should contain links for builds with the feature - 
* Links for Nightly builds
* Links for Beta builds

== Test Execution Schedule ==
The following table identifies the anticipated testing period available for test execution.
{| class="wikitable" style="width:60%"
|-
! Project phase !! Start Date !! End Date
|-
| Start project 
|style="text-align:center;" |  || 
|-
| Study documentation/specs received from developers
|style="text-align:center;" |  || 
|-
| QA - Test plan creation 
|style="text-align:center;" |  || 
|-
| QA - Test cases/Env preparation 
|style="text-align:center;" |  || 
|-
| QA - Nightly Testing 
|style="text-align:center;" |  || 
|-
| QA - Beta Testing 
|style="text-align:center;" |  || 
|-
| Release Date 
|style="text-align:center;" | || 
|}

== Testing Tools ==
Detail the tools to be used for testing, for example see the following table:
{| class="wikitable" style="width:50%"
|-
! Process !! Tool
|-
| Test plan creation || Mozilla wiki
|-
| Test case creation || [https://testrail.stage.mozaws.net/index.php TestRail]/ Google docs
|-
| Test case execution || [https://testrail.stage.mozaws.net/index.php TestRail]
|-
| Bugs management || Bugzilla
|}

= Status = 
== Overview ==
 Track the dates and build number where feature was released to Nightly
 Track the dates and build number where feature was merged to Release/Beta


= References =
* List and links for specs
  List and links for available specs - documents, user stories, specifications
* Meta bug
 
= Testcases = 
== Test Areas ==
{| class="wikitable" style="width:80%"
|-
! Test Areas !! Covered !! Details
|-
| Private Window 
|style="text-align:center;" | || 
|-
| Multi-Process Enabled 
|style="text-align:center;" |  || 
|-
| Multi-process Disabled 
|style="text-align:center;" |  || 
|-
| Theme (high contrast) 
|style="text-align:center;" |  || 
|-
| '''UI''' 
||  || 
|-
| Mouse-only operation  
|style="text-align:center;" |  || 
|-
| Keyboard-only operation  
|style="text-align:center;" |  ||
|-
| Display (HiDPI) 
|style="text-align:center;" | || 
|-
| Interaction (scroll, zoom) 
|style="text-align:center;" | || 
|-
| Usable with a screen reader  
|style="text-align:center;" |  || e.g. with NVDA
|-
| Usability and/or discoverability testing   
|style="text-align:center;" |  || Is this feature user friendly
|-
| RTL build testing   
|style="text-align:center;" |  ||
|-
| '''Help/Support''' 
||  || 
|-
| Help/support interface required   
|style="text-align:center;" |  || Make sure link to support/help page exist and is easy reachable.
|-
| Support documents planned(written)  
|style="text-align:center;" |  || Make sure support documents are written and are correct.

|-
| '''Install/Upgrade''' 
||  || 
|-
| Feature upgrades/downgrades data as expected   
|style="text-align:center;" |  ||
|-
| Does sync work across upgrades   
|style="text-align:center;" |  || 
|-
| Requires install testing    
|style="text-align:center;" |  || separate feature/application installation needed (not only Firefox)
|-
| Affects first-run or onboarding     
|style="text-align:center;" |  || Florin/Lawrence are investigating if there is a dedicated QA for this, or we should test? Should be an yes/no and if is yes should add in detail column the team/person assigned.
|-
| Does this affect partner builds? Partner build testing  
|style="text-align:center;" |  || yes/no options, add comment with details about who will lead testing

|-
| ''' Enterprise ''' 
||  ||  Raise up the topic to developers to see if they are expecting to work different on ESR builds
|-
| Enterprise administration   
|style="text-align:center;" |  || 
|-
| Network proxies/autoconfig   
|style="text-align:center;" |  || 
|-
| ESR behavior changes   
|style="text-align:center;" |  || 
|-
| Locked preferences  
|style="text-align:center;" |  ||

|-
| ''' Data Monitoring ''' 
||  || 
|-
| Temporary or permanent telemetry monitoring   
|style="text-align:center;" |  || List of error conditions to monitor
|-
| Telemetry correctness testing   
|style="text-align:center;" |  || 
|-
| Server integration testing   
|style="text-align:center;" |  || 
|-
| Offline and server failure testing   
|style="text-align:center;" |  ||
|-
| Load testing   
|style="text-align:center;" |  ||

|-
| ''' Add-ons ''' 
||  || If add-ons are available for testing feature, or is current feature will affect some add-ons, then API testing should be done for the add-on.
|-
| Addon API required?   
|style="text-align:center;" |  || 
|-
| Comprehensive API testing   
|style="text-align:center;" |  || 
|-
| Permissions   
|style="text-align:center;" |  || 
|-
| Testing with existing/popular addons
|style="text-align:center;" |  || 

|-
| ''' Security ''' 
||  || Security is in charge of Matt Wobensmith. We should contact his team to see if security testing is necessary for current feature.
|-
| 3rd-party security review   
|style="text-align:center;" |  || 
|-
| Privilege escalation testing
|style="text-align:center;" |  || 
|-
| Fuzzing   
|style="text-align:center;" |  || 

|-
| ''' Web Compatibility ''' 
||  || depends on the feature
|-
| Testing against target sites   
|style="text-align:center;" |  || 
|-
| Survey of many sites for compatibility   
|style="text-align:center;" |  || 

|-
| ''' Interoperability  ''' 
||  || depends on the feature
|-
| Common protocol/data format with other software: specification available. Interop testing with other common clients or servers.   
|style="text-align:center;" |  || 
|-
| Coordinated testing/interop across the Firefoxes: Desktop, Android, iOS   
|style="text-align:center;" |  || 
|-
| Interaction of this feature with other browser features   
|style="text-align:center;" |  || 
|}

== Test suite ==
 Full Test suite - Link to test rail - testcases should be added under Firefox Desktop project [https://testrail.stage.mozaws.net/index.php?/suites/overview/17 link]
 Smoke Test suite - Link with the tests - if available/needed.
 Regression Test suite - Link with the tests - if available/needed.

= Bug Work =
Meta bug: [https://bugzilla.mozilla.org/show_bug.cgi?id=12345 12345 - bug summary]

<div class="toccolours mw-collapsible mw-collapsed" style="width:auto">
====== Logged bugs ( blocking [https://bugzilla.mozilla.org/show_bug.cgi?id=12345 12345] )======

<div class="mw-collapsible-content">
<bugzilla>
    {
        "blocks":[12345],
        "include_fields": "id, priority, component, assigned_to, summary, status, target_milestone"
    }
</bugzilla>

</div>
</div>

<div class="toccolours mw-collapsible mw-collapsed" style="width:auto">
====== Bug fix verification ======
<div class="mw-collapsible-content">
<bugzilla>
    {
        "blocks":[12345],
        "resolution":"FIXED",
        "include_fields": "id, priority, component, assigned_to, summary, status, resolution, target_milestone"
    }
</bugzilla>
</div>
</div>

= Sign off =
== Criteria ==
Checklist
* All test cases should be executed
* Has sufficient automated test coverage (as measured by code coverage tools) - coordinate with RelMan
* All blockers, criticals must be fixed and verified or have an agreed-upon timeline for being fixed (as determined by engineering/RelMan/QA)

== Results ==
'''Nightly testing'''<br />

List of OSes that will be covered by testing<br />
*Link for the tests run
** Full Test suite, link to TestRail - Tests Runs and Results [https://testrail.stage.mozaws.net/index.php?/runs/overview/17 link]
** Daily Smoke, if needed/available
** Regression Test suite, if needed/available
<br />

'''Merge to Beta Sign-off'''<br />
List of OSes that will be covered by testing<br />
*Link for the tests run
** Full Test suite

== Checklist ==
{| class="wikitable" style="width:60%"
|-
! Exit Criteria !! Status !! Notes/Details
|-
|  Testing Prerequisites (specs, use cases) 
| style="text-align:center;" |   
| style="text-align:center;" | 
|-
|  Testing Infrastructure setup 
|style="text-align:center;" |   || 
|-
|  Test Plan Creation 
| style="text-align:center;" |   || 
|-
|  Test Cases Creation 
|style="text-align:center;" |   || 
|-
|  Automation Coverage ||
|style="text-align:center;" | 
|-
|  Performance Testing 
|style="text-align:center;" |  || 
|-
|  All Defects Logged || || 
|-
|  Critical/Blockers Fixed and Verified || || 
|-
|  Metrics/Telemetry|| 
|style="text-align:center;" | 
|-
|  Basic/Core functionality Nightly testing
|style="text-align:center;" |  
|style="text-align:center;" |  
|-
|  QA mid-Nightly Signoff|| 
|style="text-align:center;" | Email to be sent 
|-
|  QA Nightly - Full Testing 
|style="text-align:center;" |  || 
|-
|  QA pre-Beta Signoff|| 
|style="text-align:center;"| Email to be sent 
|-
|  QA Beta - Full Testing
|style="text-align:center;" |  || 
|-
|  QA pre-Release Signoff || 
|style="text-align:center;" | Email to be sent 
|}
