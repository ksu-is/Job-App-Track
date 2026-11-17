# Job-App-Track

Job-App-Track is a web app for college students who want to keep track of internship and entry-level job applications in one place. It helps students remember where they applied, when an application is due, and which companies have responded.

## Planned Features

- **Add an application.** Enter the company name, job title, application deadline, and current status using a form.
- **View saved applications.** See all applications in a single table so it’s easy to check deadlines and see where each application stands.
- **Update an application’s status.** Change the status as it moves through stages such as Interested, Applied, Interviewing, Offer, or Closed.
- **Keep applications between sessions.** Save the entries to a CSV file so they’re still there after the app closes.

## Example

A student finds a business analyst internship and adds it to the tracker as Interested. After submitting the application, they change its status to Applied. If the company reaches out for an interview, they update the same entry to Interviewing.

## Technology

The app will use Python and Flask to process forms and save application records. Basic HTML will display the form and application table. The app will run locally in a web browser without JavaScript.

## Project Goals

The goal for the first version is to let a student add an application, find it in the table, and update its status. We’ll test that both the application and its updated status are still there after restarting the app. If time allows, we may add recruiter notes and a view for upcoming follow-up dates.
