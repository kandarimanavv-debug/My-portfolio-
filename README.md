# Manav Kandari — Portfolio

<div align="center">

![Project Banner](./public/demo.png)

### Midnight Liquid Glass Portfolio
*A premium, responsive video editing portfolio built with modern web technologies.*

[![Next.js](https://img.shields.io/badge/Next.js_16-black?style=for-the-badge&logo=next.js&logoColor=white)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Framer Motion](https://img.shields.io/badge/Framer_Motion-black?style=for-the-badge&logo=framer&logoColor=white)](https://www.framer.com/motion/)

</div>

## ✨ Design Philosophy: Midnight Liquid Glass

This project implements a unique **"Midnight Liquid Glass"** aesthetic, focusing on deep blacks, neon accents, and organic fluidity.

- **Frosted Glass 2.0**: Premium `backdrop-blur-3xl` with milky-white tint for distinct separation.
- **Unified Liquid Navigation**: A shapeshifting navbar that fluidly expands to contain mobile menus.
- **Dynamic Interactions**: Mouse-following gradients and spotlight effects.
- **YouTube Integration**: Custom light-weight players with high-quality playback enforcement.

## 🚀 Getting Started

### Prerequisites

- Node.js 22+
- npm (or bun/pnpm)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/kandarimanavv-debug/My-portfolio-.git
   cd My-portfolio-
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   ```
   Add your environment variables:
   ```env
   RESEND_API_KEY=your_resend_api_key_here
   NEXT_PUBLIC_SITE_URL=your_site_url_here
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

### Building for Production

```bash
npm run build
npm start
```

### Running Tests

```bash
npm test
npm run test:watch
```

## 🚀 Deployment

### Vercel (Recommended)

1. Push code to GitHub.
2. Connect repository to Vercel.
3. Add environment variables in the Vercel dashboard.
4. Deploy automatically.

### Other Platforms
- **Netlify**: Static site deployment with form handling.
- **AWS Amplify**: Full-stack deployment with API integration.
- **Docker**: A `Dockerfile` is included for containerized deployment.

## 📂 Project Structure

```plaintext
📦portfolio
 ┣ 📂public
 ┃ ┣ 📂companies
 ┃ ┣ 📂project-images
 ┃ ┣ 📂tools
 ┃ ┗ 📜manavprofile.jpeg
 ┣ 📂src
 ┃ ┣ 📂app
 ┃ ┃ ┣ 📂about
 ┃ ┃ ┣ 📂api
 ┃ ┃ ┣ 📂contact
 ┃ ┃ ┣ 📂project
 ┃ ┃ ┣ 📂skills
 ┃ ┃ ┣ 📜layout.tsx
 ┃ ┃ ┗ 📜page.tsx
 ┃ ┣ 📂components
 ┃ ┣ 📂db
 ┃ ┣ 📂hooks
 ┃ ┣ 📂lib
 ┃ ┗ 📂types
 ┣ 📜Dockerfile
 ┣ 📜package.json
 ┗ 📜tsconfig.json
```

### 📝 Adding New Video Projects

To add a new project, simply edit `src/db/projects.ts`. No new code required!

## 🛠️ Tech Stack

- **Core**: Next.js 16, TypeScript
- **Styling**: Tailwind CSS, Shadcn/ui
- **Animation**: Framer Motion
- **Backend**: Resend (Email)
- **Testing**: Vitest
