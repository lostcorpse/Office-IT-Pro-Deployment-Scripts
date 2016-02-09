# Office IT Pro Deployment Scripts
This repo is a collection of useful PowerShell scripts to make deploying Office 2016 and Office 365 ProPlus easier for IT Pros and administrators. 

Read more about it here: [Office Blogs](https://blogs.office.com/2015/08/19/introducing-the-office-it-pro-deployment-script-project/)

## Update branch name change

Based on customer feedback, we’ve changed how we refer to our update branches. The name changes are as follows:
<UL>
<LI>Current Branch is now called Current Channel
<LI>Current Branch for Business is now called Deferred Channel
<LI>First Release for Current Branch is now called First Release for Current Channel
<LI>First Release for Current Branch for Business is now called First Release for Deferred Channel
</UL>
Only the names are changing. The servicing model for each of these channels remains the same. 

We are in the process of updating our content, so you will continue to see the previous naming during this transition. 


## Scripts
For more detailed documentation of each script, check the [Wiki](https://github.com/OfficeDev/Office-IT-Pro-Deployment-Scripts/wiki) or the readme file in the corresponding folder

## XML Editor
Tired of manually editing the Office Click-To-Run Configuration XML File?  Try our online XML Editor.

[Office Click-To-Run Configuration XML Editor](http://officedev.github.io/Office-IT-Pro-Deployment-Scripts/XmlEditor.html)

## New to PowerShell and Office 365?
Check out [PowerShell for Office 365](http://powershell.office.com) for advice on getting started, key scenarios and script samples.  

##Questions and comments
If you have any trouble running this sample, please log an issue.
For more general feedback, send an email to o16scripts@microsoft.com.

## How to Contribute to this project
This is high level plan for contributing and the structure that we have in place for pulling changes.
<UL>
<LI>There will be 3 main levels of branches: 1 master branch, 1 development branch, feature and bug branches
<LI>Each powershell script will have its own branch and changes will be made at that level
<UL>
<LI>The 3rd level naming conventions will be as follows - Feature-FeatureName or Bug-BugName</UL>
<LI>Pull requests will be made from the feature branches into the development branch and a code review will be completed in the development branch
<LI>Pull requests should only be made from the feature branch after the script is tested and useable
<LI>After the code review is complete a pull request will be made from the development branch into the master branch
<LI>Changes to scripts (new functionality or bug fix) should be done at the thrid level (feature branches) by cloning the development branch using the naming conventions above
<LI>Requests for changes to scripts can be made by submitting an issue and using the appropriate tag
<UL>
<LI>For additional features to an existing script, use the label "enhancement"
<LI>For bugs, use the label "bug"
<LI>All issues will be reviewed and prioritized each day as we work to add new scripts and improve existing ones</UL>
</UL>
