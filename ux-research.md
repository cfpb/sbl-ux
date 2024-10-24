# UX Research and Design Questions
This doc captures our UX research and design questions so that we can better craft our research studies. These questions will be categorized under the following themes:
- Creating/Completing your user profile
- Filing for your institution
- Getting help
- Global design questions

The initial list of questions came from [215](https://github.com/cfpb/sbl-project/issues/215). This doc includes all of those questions in addition to a way to track when we've addressed them. V1 for this doc just captures the questions; the tracker will be added later.

# Shared Platform
- Is it easy to find the unauthenticated landing page from the CFPB public site?
- What content are we missing on the authenticated landing page that users expect to find?
- For form submissions, does the following alternate messaging work better: "Please allow 1-2 business days for a review of your financial institution information.  You will not be able to access the platform until your information is reviewed. You can close this window. If you need assistance or you feel you received this message in error, please contact SBL Help at sblhelp@cfpb.gov."?

# Creating/Completing your user profile
## User Profile
- When there is no institution match, how do we better communicate that a user is completing a support request rather than manually entering their FI information? (During the focus group, participants thought they were manually associating themselves and expected our system to perform validation checks on fields like LEI.)
- How easily can users update their profile?

## Financial Institution Details
- Should a filer be able to see who else is associated with their financial institutions?
- Can users easily find and update their financial institution's details?

# Filing for your institution
## Filing process navigation
- How much do users expect to be able to jump between steps, and to what degree should we accommodate those expectations? What impact would this have on completing the filing process?
- Should the step indicator afford another way to navigate between steps (in addition to the buttons)? 
- Would wayfinding be improved with button text that is more descriptive than "Go back" and "Save and continue"?
- When a filer hasn't completed the step that they are on, how should the design of "Save and continue" change to let them know that they can't move forward in the process? Currently the button is secondary until requirements have been met and then turns primary when requirements are met. 
- Where is the best/most expected place to ask for type of financial institution if it hasn't been provided? Is there a better way to ensure we have this information before a filer starts the filing process?
- When a filer is in the filing process, when would they need to view their financial institution profile?
- Currently we displate financial institution about the steps of the filing flow. If we made financial institution a link, where would filers expect to go by clicking on the link? 

## Filing home
- What dates and deadlines do filers need to see to understand what data they need to submit and by when?
- After a filer has submitted, what are the relevant actions and content to display? 
- When filers are on the resolve errors and review warnings steps, is it better to have the "Continue filing" button text be descriptive instead (e.g. "Resolve errors" or "Review warnings")?

## Upload file
- Does the revised design help filers understand that they need to replace their file after correcting errors? 
- Does the revised design help filers understand that there's more to filing that just uploading their file? (I.e. for those used to HMDA, do they understand how this process differs from HMDA?)
- Is the upload file page the best page to guide filers to when it's time to replace their file?
- What's the best language to use for the "Replace file" button: "replace file", "upload new file", or something else? Does one phrasing make it more likely that filer's will be able to successfully complete the filing process? 
- How do we keep filers from getting stuck on this page once they've corrected errors and need to replace their file?
- Do filers expect the upload summary to appear above or below the button for replacing their file? Does one design perform better than another?
- Is there a way to make it more obvious that "save and continue" will take you to where you can review what those errors were?

## Errors and warnings
- How do we better communicate the purpose of the errors and warnings pages so that filers don't expect to be able to edit their data in the UI? How do we make it more clear that data needs to be corrected outside of our system and then a revised file needs to be uploaded?
- Would users find it useful to see a total count and ratio for errors and warnings (e.g. "500 of 700 records have at least one error")?
- How often do filers use the links to the filing instruction guide to learn more about an error or warning? What additional information are they looking for? Could we improve what we show on these pages?
- Should we consider splitting errors into two separate steps? How would that help or hinder progress towards submitting a filing?
- What is a filer's typical or anticipated workflow for resolving errors and replacing their file? How does this affect the use of buttons and links for getting filers to download the report and upload a revised file once errors and warnings are addressed?
- How can we update the body text for resolve errors so that we avoid inaccurate language like "If applicable" when users must actually update their file?
- How can we improve the language for describing the validations performed for when a filer actually has an error/warning vs when it passes without any issues? Would a simple change like adding "if necessary" to the header text better serve filers?

## Point of contact
- Do filers expect to be able to provide their POC ahead of time? Should filers be able to provide this before they've corrected errors and verified any warnings?
- Is it clear to filers that the POC is associated with a filing and not the institution?
- Should POC be separate from other FI information? Or would it make more sense to have all FI information together? Where is the best spot in the filing flow to ask for this information?
- Should filers be able to navigate to FI details from here?

## Sign and submit
- Can we still assume that anyone associated with the financial institution is authorized to submit the filing? Or do we need additional controls to ensure that only authorized individuals can sign and submit?
- What do filers expect to see as a part of a submission receipt?
- Does our revised language for parent entity reduce confusion when this doesn't apply to a financial institution?
- Does adding dollar amount of loans and total number of loans to the "Confirm your register information" section help a filer feel more confident that they are submitting the correct data?
- Who should receive the email confirmation after a filer submits a filing? Should it be only the filer, the filer and POC, anyone who is associated with the institution in our system?

# Getting help
- Will there be any sort of data template that an institution can use?
- Other than email, what types of support will we offer (chatbot, video tutorials, etc)?
- How do we improve contextual help for things like RSSD ID and Parent Entity so that filers can learn what those things are and whether they are applicable?
- Where are there gaps in helping resolve support requests?

# Global design questions
- How do we handle multiple individuals working on the same filing? Especially when a filing is about to be submitted?
- What translations will be available and on which pages?
- How are we distinguishing the shared landing page (Home) from filing home (Filing) in a way that users expect?
- What are the metrics we are using to judge the design's performance?
- What do filers find useful in the header and footer? What is missing?
- Where do filers expect to go when they click on the CFPB logo at the top of the page?
