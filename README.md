# Email Notification Templates




### Templates

We support plain-text and HTML email notifications. Each template could be customized to fit your exact needs.

View the default templates within the *text* or *html* directories.


<br />
### Using Variables


Embed variables in message templates by wrapping them with **\*|** and **|\***

**Example:** \*|COMPANYNAME|\*


<br />
Each type of notification has it's own set of available variables.

---


#### Incident

  - COMPANYNAME

  - STATUSPAGENAME

  - STATUSPAGEURL

  - AFFECTEDCOMPONENTS

  - AFFECTEDCONTAINERS

  - INCIDENTTITLE

  - CURRENTSTATUS

  - CURRENTSTATE

  - PREVIOUSSTATUS

  - PREVIOUSSTATE

  - UPDATEMESSAGE

  - TIMESTART

  - TIMERESOLVE

  - USERFULLNAME

  - USEREMAIL


---

#### Maintenance Reminder

  - COMPANYNAME

  - STATUSPAGENAME

  - STATUSPAGEURL

  - AFFECTEDCOMPONENTS

  - AFFECTEDCONTAINERS

  - MAINTENANCETITLE

  - MAINTENANCEDETAILS

  - TIMESTART

  - TIMEEND

  - USERFULLNAME

  - USEREMAIL


---

#### Maintenance

- COMPANYNAME

- STATUSPAGENAME

- STATUSPAGEURL

- AFFECTEDCOMPONENTS

- AFFECTEDCONTAINERS

- MAINTENANCETITLE

- UPDATEMESSAGE

- TIMESTART

- TIMEEND

- USERFULLNAME

- USEREMAIL




