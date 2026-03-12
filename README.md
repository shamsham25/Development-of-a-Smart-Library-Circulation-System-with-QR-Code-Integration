Development of a Smart Library Circulation System
with QR Code Integration
Updated User Stories

US■01 — Admin Login and Logout
As an Admin, I want to log in using my username and password so that I can securely access the
Admin Dashboard, and log out to end my session safely.
1 Admin opens the system homepage.
2 Admin enters username and password and clicks Login.
3 If credentials are valid, the system redirects to the Admin Dashboard.
4 Admin can click Logout at any time.
5 The system ends the session and redirects to the homepage.

Epic B – Book Import and Library Database Management (MVP)

US■02 — Import Books from Excel
As an Admin, I want to import book data from an Excel file so that books can be quickly added to
the system database.
1 Admin logs in to the Admin Dashboard.
2 Admin clicks Import.
3 File Explorer opens.
4 Admin selects the Excel file.
5 System processes the file and displays 'Import Successfully'.

US■03 — View Imported Books
As an Admin, I want to view imported books so that I can confirm they were successfully added.
1 Admin clicks Imported Books.
2 System displays all books imported from the Excel file.

Epic C – Student Borrowing and QR Code Generation (MVP)

US■04 — Browse Available Books
As a Student, I want to browse available books so that I can select books to borrow.
1 Student clicks Borrow on the homepage.
2 System opens Student Choose Books page.
3 Page shows search bar, list of books, and Borrow buttons.
4 If book is unavailable, the system shows 'Not Available'.

US■05 — Add Books to Shelves
As a Student, I want to add selected books to my shelves so that I can review them before
submitting.
1 Student clicks Borrow beside books.
2 Selected books appear in Add to Shelves page.

US■06 — Submit Borrowing Information
As a Student, I want to enter my information so that my borrowing request can be recorded.
1 Student fills out Name, Student ID, Course, Section, Email.
2 Student ID and Email must be unique.
3 Maximum of 3 books allowed.

US■07 — Generate QR Code
As a Student, I want to generate a QR code containing my borrowing request so the admin can
process it quickly.
1 Student submits the form.
2 System generates a QR code with student information and selected books.
3 Student can download or capture the QR code.

Epic D – Admin Dashboard and Borrowing Monitoring (MVP)

US■08 — View Borrowing Requests
As an Admin, I want to view all borrowing requests so that I can manage transactions.
1 Dashboard displays student name, ID, course, section, email, books borrowed, and quantity.

US■09 — Verify Book Availability
As an Admin, I want to check if books are available so I can approve valid requests.
1 Admin opens Available Books page.

2 System shows book status as Available or Not Available.

US■10 — Approve Borrowing Request
As an Admin, I want to approve requests so students can claim their books.
1 Admin verifies book availability.
2 Admin clicks Available.
3 System sends email notification to student.

Epic E – QR Code Scanning and Book Claiming (MVP)

US■11 — Scan QR Code for Claiming
As an Admin, I want to scan the student's QR code so that I can retrieve the request instantly.
1 Student presents QR code.
2 Admin scans it using QR Scan.
3 System opens Review Page.

US■12 — Confirm Book Claim
As an Admin, I want to confirm book claiming so that the borrowing transaction is recorded.
1 Admin reviews student information.
2 Admin gives books.
3 Admin clicks Claimed.
4 Record moves to Claimed Page.

Epic F – Book Return Process (MVP)

US■13 — Return Borrowed Books
As an Admin, I want to scan the QR code when books are returned so the system records the
return.
1 Student returns books within 3 days.
2 Admin scans QR code.
3 System redirects to Return Page.

US■14 — Automatic Record Deletion
As a System, I want to automatically delete return records after 2 days so the database remains
organized.

1 System removes return records after two days automatically.
