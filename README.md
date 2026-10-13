# CampusHub — Student Management Dashboard

**Live Demo:** [Add your live website link]

**GitHub Repository:** [Add your GitHub repository link]

## About the Project

CampusHub is a responsive student management dashboard built with HTML and Tailwind CSS v4. It helps users view student information, monitor payments, and track course progress.

## Features

- Responsive sidebar and top navigation bar.
- Four statistics cards.
- Student table with six records and colored status badges.
- Recent activity and course progress panels.
- Add New Student form.
- Responsive layouts for mobile, tablet, and desktop.
- Hover, focus, and transition effects.

## Technologies Used

- HTML5
- Tailwind CSS v4
- Tailwind CSS CLI
- npm

## How to Run Locally

1. Clone the repository.
2. Open the project folder in your terminal.
3. Install dependencies:

   ```bash
   npm install
   ```

4. Start Tailwind:

   ```bash
   npx @tailwindcss/cli -i ./src/input.css -o ./output.css --watch
   ```

5. Open `index.html` using VS Code Live Server.

## How I Customized Tailwind

I customized Tailwind using an indigo brand color palette and a custom font to create a consistent dashboard design. I used responsive utilities such as `md:` and `xl:` to adapt the layout to different screen sizes.

I also created reusable component classes using `@apply` inside `@layer components`, including `.btn-primary`, `.card`, and `.badge`. These classes reduce repeated utility styles and make the HTML easier to maintain.

## Screenshots

**Mobile View (375px)**

![Mobile dashboard](screenshots/mobile.png)

**Desktop View (1440px)**

![Desktop dashboard](screenshots/desktop.png)

## What I Learned

I practised responsive design, Flexbox, CSS Grid, Tailwind theme customization, reusable components, and accessible form design.

## Author
