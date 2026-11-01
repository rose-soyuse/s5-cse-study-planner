# S5 CSE Study Planner

Static HTML study planner for Vercel. No build command or framework required.

## Deploy
1. Create a new GitHub repository.
2. Upload `index.html` to the repository root.
3. In Vercel, choose **Add New → Project**, import the repository, and deploy.
4. Framework preset: **Other**; build command: leave blank; output directory: `.` (or leave defaults if detected as static).

The app stores checklist progress and edited tasks in the browser's local storage, so progress is device/browser-specific. Notifications require the page to stay open in this simple version.
