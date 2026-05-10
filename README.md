# Student Financial Request Portal

A web-based portal developed for organizations to manage and track student financial requests digitally.  
The system reduces paperwork and manual administrative effort by automating request submission, tracking, and approval processes.


## Features

- Student financial request submission
- Automated Request ID generation
- Admin dashboard for managing requests
- Request status tracking
- Secure data storage using Google Sheets
- Responsive and user-friendly interface


## Tech Stack

- HTML
- CSS
- JavaScript
- Google Apps Script
- Google Sheets


## Modules

### Student Module
- Submit financial requests
- Track request status
- View request details

### Admin Module
- View all requests
- Approve or reject requests
- Manage student records


## Project Structure

```bash
Code.gs          # Google Apps Script backend
index.html       # Main landing page
student.html     # Student dashboard
admin.html       # Admin dashboard
script.js        # Frontend functionality
admin.js         # Admin operations
style.css        # Styling
```
## How It Works

1. Students submit financial requests through the portal.
2. Request data is stored in Google Sheets using Google Apps Script.
3. Unique Request IDs are generated automatically.
4. Admin reviews and updates request status.
5. Students can track their request progress.

## Future Enhancements

- Email notifications
- Authentication system
- Role-based access control
- PDF report generation
- Database integration



