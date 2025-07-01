#  HIREWAVE – Job Recruitment Website

_A fully responsive dynamic job portal connecting job seekers with employers, built using PHP and MySQL._

---

##  Features

- User registration and authentication (job seeker & employer)
- Job application and posting system
- Certificate and resume upload/download
- Profile dashboards and admin tools
- Database-driven job listings
- Secure login with session management
- Contact form for inquiries

---

##  Tech Stack

| Technology  | Description              |
|-------------|--------------------------|
| PHP         | Server-side scripting    |
| MySQL       | Database storage         |
| HTML/CSS    | Frontend layout & design |
| Bootstrap   | Responsive UI            |
| JavaScript  | Client-side interactivity|

---

##  Project Structure

```
HIREWAVE/
├── Database/
│   └── hw_database.sql               # MySQL database schema & seed data
├── System/
│   ├── *.php                         # Main PHP files for UI & logic
│   ├── app/                          # Application logic, routing, handlers
│   ├── constants/                    # Constant config values
│   ├── bootstrap/                    # Bootstrap framework files
│   ├── css/                          # Custom styling files
├── php/
│   ├── phpinfo.php                   # PHP environment info file
```


---

##  How to Run the Project

1. Install [XAMPP](https://www.apachefriends.org/) or WAMP.
2. Move the `HIREWAVE/` folder to your `htdocs/` directory.
3. Start Apache and MySQL from the XAMPP control panel.
4. Open phpMyAdmin and import the `hw_database.sql` file into a new database named `hirewave`.
5. Visit: `http://localhost/HIREWAVE/System/`

---

##  Screenshots

![Home Page](screenshots/1_2_3.jpeg)
![Login Page](screenshots/lp.png)

---

> 💬 *Connecting Careers with Code – HIREWAVE.*




