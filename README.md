# LunarScape

A modern web application with Ultraviolet proxy for bypassing internet censorship.

## Features

- Dark themed UI with purple accents
- Ultraviolet proxy functionality for accessing restricted websites
- Games section with various game options
- Tab cloaking functionality to disguise the site
- Panic key for quick exit
- Mobile-responsive design

## Tech Stack

- **Frontend**: React, Tailwind CSS, Shadcn UI Components
- **Backend**: Express.js, HTTP Proxy Middleware
- **Proxy Technology**: TompHTTP Bare Server
- **Build Tool**: Vite

## Deploying to Vercel

LunarScape is configured for easy deployment on Vercel. Follow these steps to deploy your own instance:

### Prerequisites

- [Vercel account](https://vercel.com/signup)
- [Git](https://git-scm.com/downloads) installed on your machine
- [Node.js](https://nodejs.org/) (v16 or higher)

### Steps to Deploy

1. **Fork or Clone the Repository**

   ```bash
   git clone <repository-url>
   cd lunarscape
   ```

2. **Install Vercel CLI (Optional)**

   ```bash
   npm install -g vercel
   ```

3. **Deploy to Vercel**

   **Option 1: Using Vercel CLI**

   ```bash
   vercel login
   vercel
   ```

   **Option 2: Using Vercel Dashboard**

   - Go to [Vercel Dashboard](https://vercel.com/dashboard)
   - Click "New Project"
   - Import your GitHub repository
   - Configure project settings if needed
   - Click "Deploy"

4. **Environment Variables**

   No environment variables are required for basic functionality. All APIs are self-contained.

5. **Vercel Configuration**

   The project includes a `vercel.json` file that configures:
   - Build settings
   - API routes
   - Serverless functions
   - Rewrites for proxy functionality

## Development

To run the project locally:

```bash
npm install
npm run dev
```

The application will be available at `http://localhost:5000`.

## Credits

- Made by Wilbert Sirleaf