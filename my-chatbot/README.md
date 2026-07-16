# My Chatbot

## Files
- `index.html` — the chat page visitors see
- `api/chat.js` — server code that talks to the AI model (keeps your API key hidden)
- `package.json` — tells Vercel this is a Node project

## Deploy steps (see full walkthrough in chat)
1. Create a free account at github.com, make a new repository, and upload
   this whole folder (drag and drop all 4 files/folders — keep `api` as a subfolder).
2. Create a free account at vercel.com, click "New Project," and import
   that GitHub repo.
3. Before deploying, go to Environment Variables and add:
   - Name: `ANTHROPIC_API_KEY`
   - Value: (your key from console.anthropic.com)
4. Click Deploy. You'll get a live URL like `your-project.vercel.app`.

If you ever change the environment variable, redeploy for it to take effect.
