TicketEase demo project
Files:
- User.html: user login, demo OTP, location prompt, movie/food/transport bookings, demo payment, My Bookings.
- Admin.html: admin login, dashboard, booking list, category filter, CSV export.

Run:
1. Open this folder in VS Code.
2. Install the Live Server extension.
3. Right-click User.html > Open with Live Server.
4. Open Admin.html using the same Live Server origin and browser.

Admin demo credentials:
Email: admin@ticketease.com
Password: Admin@123

Important:
- OTP is displayed in a browser alert; no SMS is sent.
- Google sign-in is a placeholder and requires OAuth/Firebase setup.
- Payments are simulated. Do not enter real card details, bank passwords, or UPI PINs.
- This is a front-end college demo. Admin credentials are in client-side code and are not secure for production.
- User and admin pages share bookings through browser LocalStorage on the same origin/browser.
