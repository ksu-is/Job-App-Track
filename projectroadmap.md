# Job-App-Track Project Roadmap

## Sprint 1 Codebase Review

**Reference project**  
[Job Application Tracker](https://github.com/difeigu/job_app_track)

**What I reviewed**  
I reviewed `build_applications_query()` in `app.py`. It builds a query that can filter applications by status and search by job title, company, location, or tags. I also took a look at `SORT_MAP`, which defines sorting options for applications by deadline or company.

**What happened when I tried to run it**  
I opened the project in VS Code, and tried to run the code in a Python 3.14 updated environment but since I was missing certain needed installments as shown in "requirements txt," the run failed. The installation stopped with `Failed building wheel for lxml`. I then tried running `app.py` and got `ModuleNotFoundError: No module named 'flask'`. The app did not launch.
**What I plan to use**  
I’ll use the idea of giving each application a status and showing saved applications in one place. For the first version of Job-App-Track, I’ll use Python, Flask, and basic HTML to add applications, display them in a table, and save status updates to a CSV file.
