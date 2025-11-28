# Backend API (Demo)

This backend is a simplified API for the VTU Examination Results System.
It is used only for assignment demonstration purposes.

## Endpoints

### 1. GET /api/results?usn={USN}
Returns the semester result for the given USN.

**Sample Response:**
{
  "usn": "4MW23CS001",
  "studentName": "Demo Student",
  "semester": 6,
  "results": [
    {"code": "CS601", "name": "DBMS", "marks": 89, "grade": "A", "gradePoint": 9},
    {"code": "CS602", "name": "ADA", "marks": 76, "grade": "B", "gradePoint": 8}
  ],
  "sgpa": 8.5,
  "cgpa": 8.1
}

### 2. POST /api/faculty/upload
Used by faculty to upload results (CSV/JSON).
This is a dummy placeholder for assignment demonstration.

### 3. POST /api/auth/login
Dummy login endpoint for faculty/admin.

---

## Tech Used
Node.js (Express) – For demonstration only.
No real backend logic is implemented in this assignment.
