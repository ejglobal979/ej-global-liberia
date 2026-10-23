# If you already have ej-global folder with frontend/backend:
cd ej-global

# Connect to your new GitHub repo
git init
git remote add origin https://github.com/ejglobal979/ej-global-liberia.git
git branch -M main

# Create proper structure
# Move your files like this:
# ej-global-liberia/
#   ├── frontend/src/App.tsx (your React file)
#   ├── backend/server.js (my v2 with pg-199e8856)
#   ├── backend/.env (with Aiven URI - DO NOT PUSH .env)
#   └── README.md

git add .
git commit -m "EJ Global Liberia - Platform v1 - Frontend + Backend + pg-199e8856 GPS + Call Transcripts"
git push -u origin main
