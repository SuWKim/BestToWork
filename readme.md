#Overview
---
BestToWork uses the Glassdoor API and lets users search for a company name, and see a profile with the Glassdoor ratings. Users can also sign in, save the profile and add their own notes on the company.

#UI Draft
---
The application will have the following views:
1. Main page that explains what the application does,  sample profile, and search bar
2. Search results view that lists company names
2. Profile view that will render the searched company's information
3. Sign up view (for new users)
4. Log in view (for returning users)
5. User profile page that has saved company profiles that lists all profiles saved

#Technical Requirements
---
The application will rely on the following:

- express
- mongo
- mongoose
- express-handlebars
- passport
- passport-local-mongoose

#Features
---
**Search for Company by Name**
Users can search for companies by name.  The application will take the name parameter and find companies that fit the criteria.  It will then render the search results view that lists company names

**View Company Profile**
Selecting a company from the search results view will render the company's profile with detailed information on ratings & reviews

**Authorization**
Users can sign up using their email and password.

**Save Company Profile**
Users that are logged in can save a company profile. Saving a profile will save the company profile to the user's profile page
