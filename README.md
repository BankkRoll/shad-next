# shad-next Documentation Template

Welcome to the `shad-next` documentation template. This template provides a flexible and easy-to-use structure for building documentation with Next.js and MDX.

## Getting Started

To get started with the `shad-next` template, follow the installation and setup instructions below.

### Installation

1. **Clone the repository**:
   \`\`\`\`bash
   git clone https://github.com/your-username/shad-next.git
   cd shad-next
   \`\`\`\`

2. **Install dependencies**:
   \`\`\`\`bash
   npm install
   \`\`\`\`

3. **Set up environment variables**:
   Rename the `.env.example` file to `.env` and fill in the necessary values.
   \`\`\`\`bash
   mv .env.example .env
   \`\`\`\`

   Example `.env` file:
   \`\`\`\`
   GITHUB_CLIENT_ID=your_github_client_id
   GITHUB_CLIENT_SECRET=your_github_client_secret
   GITHUB_REDIRECT_URI=your_github_redirect_uri
   \`\`\`\`

### Running the Development Server

To start the development server, run:
\`\`\`\`bash
npm run dev
\`\`\`\`

Open your browser and navigate to `http://localhost:3000` to see your documentation site in action.

## Editing Documentation Meta and Routing

To edit the meta information and routing for your documentation, modify the `shad-next.config.json` file located in the `src/components/docs` directory.

### Example `shad-next.config.json`

\`\`\`\`json
{
"title": "shad-next Documentation",
"companyName": "shad-next",
"fontFamily": "Inter, sans-serif",
"footerText": "© 2024 shad-next",
"routes": [
{
"slug": "",
"title": "Documentation",
"description": "Welcome to the documentation page of shad-next.",
"icon": "FileIcon"
},
{
"slug": "introduction",
"title": "Introduction",
"description": "Introduction to the documentation of shad-next.",
"icon": "BookIcon"
},
{
"slug": "",
"title": "Customization",
"description": "How to customize shad-next.",
"icon": "SettingsIcon",
"children": [
{
"slug": "customization",
"title": "Get Started",
"description": "Quick start guide for shad-next.",
"icon": "SettingsIcon"
},
{
"slug": "customization/accordion",
"title": "Accordion",
"description": "Quick start guide for the accordion.",
"icon": "RocketIcon"
},
{
"slug": "customization/callout",
"title": "Callout",
"description": "Quick start guide for the callout.",
"icon": "RocketIcon"
},
{
"slug": "customization/tabs",
"title": "Tabs",
"description": "Quick start guide for the tabs.",
"icon": "RocketIcon"
},
{
"slug": "customization/npm2yarn",
"title": "Npm2Yarn",
"description": "Quick start guide for the npm2yarn.",
"icon": "RocketIcon"
}
]
}
]
}
\`\`\`\`
