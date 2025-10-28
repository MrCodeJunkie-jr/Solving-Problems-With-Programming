**1. Problem Description**

Students often struggle to keep track of multiple assignment deadlines across different courses. Missing deadlines can lead to poor performance and unnecessary stress.
Currently, most students use manual methods such as notebooks, notes apps, or reminders on their phones. These methods are inconsistent and can become confusing when managing many tasks simultaneously.

**2. Aspects Solved by the Program**

The program (website) directly solves the following aspects of the problem:

Centralized storage of all assignment details in one place.

Visual overview of upcoming and completed assignments.

Automatic notifications and reminders before deadlines.

Easy access from any device using a web browser.

**3. How Solving the Problem with a Program Changes the Original Process**

Before: Students manually write or remember deadlines, leading to missed or forgotten tasks.
After: The program automatically reminds users of upcoming deadlines and helps organize assignments clearly by course and date.

This automation reduces human error and makes the reminder process efficient and stress-free.

**4. Requirements the Problem Places on the Program**

To solve this problem effectively, the program must:

Allow users to add, edit, and remove assignment details easily.

Store assignment data locally (or on the cloud, optionally).

Send notifications 24 hours before the deadline.

Display assignments in an organized, readable table format.

Work reliably on both desktop and mobile browsers.

**5. How Using the Program Changes the Operating Model**

The program changes the way students manage their studies:

Instead of relying on personal notes or memory, they use a structured digital planner.

Time management improves since reminders prevent last-minute panic.

The focus shifts from remembering deadlines to completing tasks efficiently.

**6. Situations Where the Program Will Be Used**

At home or school, when students are studying and want to add or check assignments.

On the go, when students quickly check upcoming deadlines on their phone.

Before exams, when they review pending submissions.

**7. Requirements from These Situations**

The program must run entirely in a web browser (no installation required).

It should be a local web application that stores data in the browser’s local storage (no external server needed).

It should work offline once opened.

Notifications must work as long as the browser tab is open and permissions are granted.

**8. Planned Software Architecture**

Frontend: HTML, CSS, and JavaScript (single-page application).

Storage: Browser Local Storage (JSON format).

Notifications: Browser Notification API.

Libraries used: Flatpickr (for the calendar input).

Reason for this architecture:
It’s lightweight, server-free, and perfect for educational or small personal projects. It minimizes complexity while providing full functionality directly in the browser.

**9. Ensuring Correct Functioning**

To ensure the program works properly:

Each function (add, edit, delete, notify) will be tested manually.

Date and time inputs will be validated to avoid incorrect entries.

Notifications will be tested to confirm they trigger at the right time.

The layout will be checked on both desktop and mobile devices.

**10. Usability Aspects Considered**

Simple, clean, and visually appealing interface.

Dark background with blue highlights for better readability.

Clear table structure to show assignments at a glance.

Responsive design (works on mobile and desktop).

Minimal input fields to keep data entry quick and easy.

Confirmation before deleting assignments to prevent accidental loss.

**11. How the Program Should Be Used**

Open the website in any browser (Chrome, Edge, Safari, Firefox).

Add assignment details (title, course, and due date).

The program will display all assignments in a table.

A reminder notification will appear 24 hours before the deadline.

Once completed, the user can mark the assignment as “done” or remove it.
