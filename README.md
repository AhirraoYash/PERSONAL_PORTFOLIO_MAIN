# Personal Portfolio

A modern, responsive personal portfolio website built with Next.js, Tailwind CSS, and TypeScript. This portfolio showcases my projects, skills, education, and provides ways to contact me.

##  Features

- **Responsive Design**: Looks great on all devices (mobile, tablet, desktop)
- **Dark/Light Mode**: Theme toggle for user preference
- **Animated UI Elements**: Subtle animations for a modern feel
- **Interactive Project Showcase**: Highlight projects with technologies used
- **Contact Form**: Easy way for visitors to reach out
- **Smart Navigation**: Context-aware scroll button
- **Resume Viewer**: Embedded PDF viewer for resume/CV
- **Performance Optimized**: Fast loading times and optimized images

##  Technologies Used

- **Frontend**: Next.js, React, TypeScript
- **Styling**: Tailwind CSS, CSS Modules
- **Icons**: Lucide React
- **Deployment**: Vercel
- **Version Control**: Git, GitHub

##  Project Structure

```
src/
├── app/                # Next.js app directory
│   ├── components/     # Reusable UI components
│   ├── layout.tsx      # Root layout
│   └── page.tsx        # Home page
├── public/             # Static assets
│   ├── Project_UI/     # Project screenshots
│   └── Yash_ahirrao.pdf # Resume file
└── ...                 # Configuration files
```

##  Getting Started

### Prerequisites

- Node.js (v18 or later)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AhirraoYash/PERSONAL_PORTFOLIO_MAIN.git
   cd personal-portfolio
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Run the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

##  Deployment

This portfolio is deployed on Vercel. Any pushes to the main branch will automatically trigger a new deployment.

For manual deployment:

```bash
npm run build
# or
yarn build
```

##  Contact

- **Email**: yashahirrao204@gmail.com
- **GitHub**: [ahirraoYash](https://github.com/AhirraoYash)
- **LinkedIn**: [Piyush Yadav](https://www.linkedin.com/in/yash-ahirrao-57508b253)




```
personal-portfolio-main
├─ eslint.config.mjs
├─ next.config.ts
├─ package-lock.json
├─ package.json
├─ postcss.config.mjs
├─ public
│  ├─ favicon.svg
│  ├─ file.svg
│  ├─ globe.svg
│  ├─ next.svg
│  ├─ Piyush_Yadav_Resume.pdf
│  ├─ profilePhoto piyush.jpg
│  ├─ profilePhoto.jpeg
│  ├─ Project_UI
│  │  ├─ EduForum.jpg
│  │  ├─ FindMySpot.png
│  │  ├─ Sentilytics.png
│  │  ├─ SmartLedger.png
│  │  ├─ StudentExamPortal.jpeg
│  │  ├─ syllabus-deadline-optimizer.png
│  │  └─ text-to-speech.png
│  ├─ vercel.svg
│  ├─ window.svg
│  └─ Yash_Ahirrao.pdf
├─ README.md
├─ src
│  └─ app
│     ├─ components
│     │  ├─ About.tsx
│     │  ├─ Collaborate.tsx
│     │  ├─ Contact.tsx
│     │  ├─ Contact.tsx.new
│     │  ├─ Education.tsx
│     │  ├─ Footer.tsx
│     │  ├─ Header.tsx
│     │  ├─ Hero.tsx
│     │  ├─ Projects.tsx
│     │  └─ ThemeToggle.tsx
│     ├─ context
│     │  └─ ThemeContext.tsx
│     ├─ cv-viewer
│     │  └─ page.tsx
│     ├─ favicon.ico
│     ├─ favicon.svg
│     ├─ globals.css
│     ├─ layout.tsx
│     ├─ page.tsx
│     └─ providers.tsx
├─ tailwind.config.js
└─ tsconfig.json

```