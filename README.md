2 Hands PHX – Employee Schedule Builder
A mobile-first web app built for a real small business to automate weekly employee scheduling across two restaurant locations. What used to take hours of manual work now takes under 10 minutes.
🔗 Live App: https://2handsschedule.netlify.app/
The Problem
A restaurant owner with two locations was spending hours every week manually writing out employee schedules, tracking availability, shift rules, hours limits, and station assignments by hand. This tool solves that.
What It Does
Auto-generates a full 7-day schedule in one click, with a different variation every time. Supports two locations (PHX and Mesa) switchable from the same interface. Respects business rules like opener/closer restrictions, max hours per employee, station assignments, day-specific shift times, and minimum 2 closers per night. Balances hours across the team so no one gets over-scheduled. Tap any cell to manually edit a specific shift. Mark who is unavailable for the week without changing their default schedule. Export as CSV, copy to clipboard for Google Sheets, or open a print-ready PDF view.
Features
🔀 Randomized auto-generation — tap multiple times to get different schedule options
📱 Mobile-first responsive design, works as a home screen app on iPhone
🖨 Print and PDF export with clean formatted layout
📊 CSV export compatible with Excel and Google Sheets
👥 Full employee management — add, edit, delete staff with shift rules and availability
🟢 Visual closer coverage indicators per day (green, yellow, red)
⏱ Hours tracking bar per employee with over-hours warnings
Tech Stack
Vanilla HTML, CSS, JavaScript — no frameworks, no dependencies, no build step. Single .html file that runs in any browser and deploys anywhere. Deployed on Netlify.
The Challenge
The core challenge was translating real-world business logic into a scheduling algorithm — shift structures, employee constraints, station codes, hour balancing, and producing valid but randomized outputs every time. The app also had to be simple enough for a non-technical user to use on their phone in under 10 minutes.
How to Use
	1.	Open the app
	2.	Select your location (PHX or Mesa)
	3.	Hit ⚡ Auto-Generate — tap again for a different schedule
	4.	Tweak any shift by tapping a cell
	5.	Export as CSV or print when done
