================================================================================
        MYSURU SMART BUS INFORMATION SYSTEM
        README & SETUP INSTRUCTIONS
================================================================================

PROJECT OVERVIEW
--------------------------------------------------------------------------------
Complete multi-page website for Mysuru city bus information including routes, 
timings, fares, and contact details for your VTU 1st year IDT project.

TECHNOLOGIES USED
--------------------------------------------------------------------------------
• HTML5 - Structure and content
• CSS3 - Styling and responsive design
• JavaScript - Interactivity and form validation

FILES INCLUDED
--------------------------------------------------------------------------------
1. index.html          - Home page
2. routes.html         - Routes with search/filter
3. timings.html        - Bus timing schedules
4. fare.html           - Fare calculator
5. contact.html        - Emergency contacts and feedback
6. style.css           - Complete stylesheet
7. script.js           - JavaScript functionality
8. PROJECT_DOCUMENTATION.txt - Full documentation
9. README.txt          - This file

HOW TO RUN
--------------------------------------------------------------------------------
METHOD 1: OPEN DIRECTLY (Easiest)
1. Locate all files in one folder
2. Double-click "index.html"
3. Website opens in your browser
4. Navigate using the menu

METHOD 2: USING CODE EDITOR
1. Open folder in VS Code
2. Right-click "index.html"
3. Select "Open with Live Server" or "Open with Browser"

IMPORTANT: Keep all files in the SAME folder!

FILE STRUCTURE:
Your_Project_Folder/
├── index.html
├── routes.html
├── timings.html
├── fare.html
├── contact.html
├── style.css
├── script.js
├── PROJECT_DOCUMENTATION.txt
└── README.txt

FEATURES
--------------------------------------------------------------------------------
✓ Fully Responsive (works on all devices)
✓ Modern Blue & White Theme
✓ Search Functionality
✓ Source/Destination Filters
✓ Fare Calculator
✓ Form Validation
✓ Interactive Tables
✓ Mobile Menu
✓ User-Friendly Navigation

TESTING THE WEBSITE
--------------------------------------------------------------------------------
1. HOME PAGE: Try quick search, view stats
2. ROUTES PAGE: Search "201", filter by source/destination
3. TIMINGS PAGE: Select routes, view timing tables
4. FARE PAGE: Calculate fare (try 10 km with Student type = ₹8)
5. CONTACT PAGE: Test feedback form validation

FOR VIVA/PRESENTATION
--------------------------------------------------------------------------------
SAMPLE Q&A:

Q: What technologies did you use?
A: HTML5 for structure, CSS3 for styling with responsive design, and 
   JavaScript for interactivity and form validation.

Q: What is the main feature?
A: Complete bus information with search functionality, responsive design, 
   fare calculator, and feedback system.

Q: How does the search work?
A: Filters routes by matching search term with route number, name, source, 
   destination, or stops using JavaScript.

Q: Explain fare calculator.
A: Calculates fare based on distance with different rates for different 
   ranges. Applies 50% discount for students and free for senior citizens.

Q: What validation does feedback form have?
A: Name (min 3 chars, letters only), Email (proper format), Phone (10 digits),
   Feedback type (must select), Message (min 10 chars).

Q: What is responsive design?
A: Website automatically adjusts layout for different screen sizes - desktop,
   tablet, and mobile phones.

Q: Future enhancements?
A: GPS tracking for real-time bus location, mobile app, journey planner, 
   digital ticketing, multi-language support.

CUSTOMIZATION
--------------------------------------------------------------------------------
TO CHANGE COLORS:
1. Open style.css
2. Find: #1e3c72 and #2a5298
3. Replace with your preferred colors

TO ADD ROUTES:
1. Open routes.html
2. Add to busRoutes array following same structure

TROUBLESHOOTING
--------------------------------------------------------------------------------
PROBLEM: Page looks unstyled
SOLUTION: Ensure style.css is in same folder

PROBLEM: Menu doesn't work on mobile
SOLUTION: Check script.js is linked correctly

PROBLEM: Form doesn't validate
SOLUTION: Check browser console (F12) for errors

FINAL NOTES
--------------------------------------------------------------------------------
✓ Complete, working website ready for submission
✓ All features functional and tested
✓ Well-commented code for viva
✓ Responsive design for all devices
✓ Professional appearance

Good luck with your project! 🚌✨

================================================================================
