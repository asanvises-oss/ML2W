MICHELIN Thailand Two-Wheel Dashboard — Netlify + OpenAI

Files:
- public/index.html
- netlify/functions/ai.mjs
- netlify.toml

Required Netlify environment variables:
1) OPENAI_API_KEY = your OpenAI API key
2) DASHBOARD_PASSWORD = Michelinthailand
Optional:
3) OPENAI_MODEL = gpt-5.4-mini

IMPORTANT:
- Do not put the OpenAI key in index.html.
- For Netlify Functions, deploy this project through Git (GitHub/GitLab/Bitbucket) or Netlify CLI/API.
- Simple drag-and-drop of a static folder does not build/deploy Functions.

Recommended no-install workflow:
1. Create a free GitHub repository in the browser.
2. Upload these files/folders to the repository.
3. In Netlify: Add new project > Import an existing project > GitHub.
4. Select the repository. Netlify reads netlify.toml automatically.
5. Add OPENAI_API_KEY and DASHBOARD_PASSWORD under Project configuration > Environment variables.
6. Trigger a new deploy after adding/changing environment variables.
