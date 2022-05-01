1. npx create-react-app planner
2. npm install styled-components
3. npm install gh-pages --save-dev
4. npm run build
5. `package.json`:
	- "homepage": "https://github.com/Vincenzofdg/Planner/",
	- "post": "npm run build && ./node_modules/.bin/gh-pages -d build",
