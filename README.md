# JSON

1. Create an external repository called JSON.
- `Create a new repository`
 2. Clone the JSON repository to the local machine.
- `git clone https://github.com/NeonilaH/JSON.git`
 3. Inside the local JSON, create a “new.json” file.
- `touch new.json`
 4. Add file under git.
- `git add new.json`
 5. Commit the file.
- `git commit -m "add the file"`
 6. Submit the file to an external GitHub repository.
- `git push`
 7. Edit the content of the “new.json” file - write information about yourself (full name, age, number of pets, future desired salary). Write everything in JSON format.
- `nano new.json`
```json
{
"first_name": "Neonila",
 "last_name": "Hlovatska",
 "age": 34,
 "number_of_pets": 1,
 "desired_salary": 1000
}
```
 8. Push changes to an external repository.
- `git commit -m "add changes"`
---> `git push`
 9. Create preferences.json file.
- `touch preferences.json`
 10. In the preferences.json file, add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, side you would like to visit) in JSON format.
- `nano new.json`
```json
{
      "favourite_movie": "None",
      "favourite_tv_series": "None",
      "favourite_food": "Ice cream",
      "favourite_season": "Summer",
      "country_you_would_like_to_visit": "Thailand"
}
```
 11. Create a file sklls.json and add information about the skills that will be studied on the course in JSON format.
 - `nano new.json`
 ```json
{
    "01": "Basic theory. SDLC, STLC.",
    "02": "What is a client-server architecture.",
    "03": "HTTP request methods to the server and response codes.",
    "04": "Structures of HTTP requests and responses.",
    "05": "What is JSON, XML. Their structure.",
    "06": "API testing via Postman (JS, API autotests).",
    "07": "Removing and reading logs from an external server.",
    "08": "Dev Tools of web browsers (Google Chrome).",
    "09": "VPN (How it works, why you need it, how to use it, tool options)",
    "10": "Mobile testing.",
    "11": "Feature iOS, Android, guidelines.",
    "12": "Building Android applications on Android Studio.",
    "13": "ADB (android device management).",
    "14": "Command line (terminal) Linux (copying, creating, viewing, moving files on servers without a graphical interface).",
    "15": "Basics of bash scripting, automation of routine tasks on the server.",
    "16": "Access to remote servers.",
    "17": "SQL basics (Create, Delete, Drop, Insert Into, Select, Where, Join).",
    "18": "Database Postgres (installation, configuration and use).",
    "19": "Scrum development methodology."
 }
```
 12. Send 2 files at once to an external repository.
- `git add .`
---> `git status`
---> `git commit -m "at 2 files at once"`
---> `git push`
 13. On the web interface, create the bug_report.json file.
- `Add file`
---> `Create new file`
---> `Commit new file`
 14. Make Commit changes (save) changes on the web interface.
- `Open file`
---> Go to the pencil button `Edit this file`
---> `Commit changes`
 15. Modify the bug_report.json file on the web interface, add a bug report in JSON format.
- `Open file`
---> Go to the pencil button `Edit this file`
```json
{
    "Bug_id": "1111",
    "Title": "Missing white lines on the widget",
    "Severity": "Major",
    "Priority": "Medium",
    "Environment": "Xiaomi Redmi 8A, MIUI Global 12.5.2, 10 QKQ1.191014.001",
    "Precondition": "Desktop grid 5x5, font size Medium, zoom Medium",
    "STR": [
     {
     "1": "Add 6 widgets",
       "2": "Arrange widgets as in the attachment"
       }
    ],
   "AR": "The widget in the center has a missing white bottom line",
    "ER": "All widgets should have four white lines",
    "Attachments": "https://bit.ly/3NOFgrJ"
}
```
 16. Make Commit changes (save changes) on the web interface.
- `Commit changes`
 17. Synchronize external and local JSON repository.
- `git pull`
