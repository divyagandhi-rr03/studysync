# StudySync — Student Productivity Dashboard

StudySync is a responsive student study planner concept designed to help students organise academic work, manage deadlines and monitor progress.

## UX and interface highlights
- Clear information hierarchy with an overview, task management and insights views
- Consistent colour palette, typography, spacing, cards and interaction states
- Responsive desktop, tablet and mobile layouts
- Task creation with category and due date
- Search and category/status filters
- Mark tasks complete/incomplete and delete tasks
- Live completion metrics and progress indicators
- Local browser storage so tasks remain after refresh on the same browser/device
- Accessible labels and keyboard-friendly form controls

## Run locally
Open `index.html` in a modern browser. No build tools or backend are required.

## Publish with GitHub Pages
1. Upload `index.html` and `README.md` to the root of your GitHub repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`, then save.
5. Wait for GitHub Pages to publish and open the website URL shown on the Pages settings screen.

## Scope and limitations
This is a front-end prototype. Tasks are stored in the browser's `localStorage`; they are not synced between devices or users. A production release would need authentication, a backend database, data validation, privacy/security review and usability testing with real students.
