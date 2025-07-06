1. Install the GitHub Pages package (if using Create React App):
npm install gh-pages --save-dev
2. Add the following lines to your package.json:
"homepage": "https://yourusername.github.io/repo-name",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}

3. Initialize a Git repository (if not done already):
   git init
git remote add origin https://github.com/yourusername/repo-name.git

4. Deploy the app to GitHub Pages:
   npm run dev



   🚀 Features
🎯 Select a number between 1 and 6.

🎲 Roll a dice and get a random value.

✅ Gain points if selected number matches dice roll.

❌ Lose 2 points if it doesn't match.

🔁 Reset functionality to restart the game.

⚠️ Error handling if dice is rolled without selection.
