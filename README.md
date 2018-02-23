# Tiny Anthems (planning repo)
Name of Student: Chris K Johnson

Name of Project: Tiny Anthems

![Tiny Anthems Interface](tiny-anthems-interface.png)

![Tiny Anthems Components](tiny-anthems-components.png)

*Store Data Structure:*
```
{
  users: {
    0: { // userId
      name: 'Joe Smith',
      questionnaires: [
        {
          status: 'pending',
          questions: {
            q1: 'a1',
            q2: 'a2',
          }
        }
      ],
      songs: [
        {
          title: 'a song for you',
          url: 'tiny-anthems.com/download/ta8hn345bkgs',
        }
      ]
    }
  }
}
```
ex: state.users.0.questionnaires[0].status

## Project’s Purpose or Goal:

A service for customers to commission musician Mike Long to create a song about a person after supplying information about them via questionnaire.

> As a user, I will be able to view the Welcome page, FAQ page, create an account, fill out a questionnaire on the form page, access/download the song from the song retrieval page after it has been produced, and leave reviews on the love-letters page.

> As an admin, I will be able to view pending and completed questionnaires, and upload songs to my client's account after producing them.

### List the absolute minimum features the project requires to meet this purpose or goal:

* Display welcome page with mock login form
* Navigate to FAQ page, questionnaire page, mock song retrieval page, and mock review page
* Save a demo song from a mock database inside mock login route

### What tools, frameworks, libraries, APIs, modules and/or other resources (whatever is specific to your track, and your language) will you use to create this MVP? List them all here. Be specific.

* React
* Redux
* Styled-JSX

### If you finish developing the minimum viable product (MVP) with time to spare, what will you work on next? Describe these features here: Be specific.

* User creation and sign-in authentication via database, to store completed questionnaires
* Admin login route for musician to access pending user (customer) questionnaires.
* Admin upload form to place song on database.
* User (signed in) download page to retrieve completed songs.
* User (signed in) review area to leave feedback about their experience.

### What additional tools, frameworks, libraries, APIs, or other resources will these additional features require?

* AWS database
