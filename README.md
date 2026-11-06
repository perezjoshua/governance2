# ISKOLAR LINK

A responsive, accessible scholarship management frontend built with HTML, CSS, and vanilla JavaScript.

## Features
- Student and faculty login role selection with interface validation
- Mobile navigation menu and responsive desktop/tablet/mobile layouts
- Scholarship search and status filtering
- Scholarship details, eligibility, deadlines, and amounts
- Student application form with document/image file uploads
- Application status tracking: Approved, Pending, or Rejected
- Faculty review queue with approve, pending, and reject actions
- Dashboard summaries, payout schedule, and announcement board
- Keyboard-accessible controls, semantic landmarks, labels, focus states, dialogs, and live status notifications

## Accessibility
- Semantic HTML and a skip-to-content link
- Visible keyboard focus and radio-button focus styling
- ARIA labels for icon controls, modal behavior, and notification updates
- Form labels, validation messages, and accessible file inputs
- Reduced-motion support and adequate text/background contrast

## Responsive Design
The layout uses CSS Grid and Flexbox, with breakpoints for large screens, tablets, and phones. Navigation becomes a fixed slide-out menu below 800px, and scholarship/application panels rearrange into single columns where needed.

## Testing Procedure
1. Open `index.html` in a modern browser or serve the folder with a local static server.
2. Enter a valid email and a password of at least four characters.
3. Sign in as Student, browse/search/filter scholarships, open a scholarship, and submit the form with two files.
4. Check the dashboard, My Applications, payout schedule, and announcements.
5. Log out and sign in as Faculty to test review actions.
6. Test tablet/mobile widths and use Tab/Shift+Tab to verify keyboard navigation.
7. Open the browser console and confirm that no JavaScript or resource-loading errors occur.

## Run Locally
```powers
python -m http.server 8080
```
Then visit `http://localhost:8080`.

> This is a frontend prototype. Authentication, documents, application data, and status changes are simulated in the browser and reset when the page reloads.
