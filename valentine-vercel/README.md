# Valentine's Day Interactive Page 💖

A cute interactive Valentine's Day page with a playful "No" button that shrinks and moves away!

## Features
- 💕 Interactive "Yes" and "No" buttons
- ✨ Confetti animation on acceptance
- 💖 Floating hearts background
- 📱 Full mobile support with touch events
- 🎨 Beautiful gradient pink theme

## Deploy to Vercel

### Method 1: Deploy via Vercel CLI (Recommended)

1. Install Vercel CLI globally:
```bash
npm install -g vercel
```

2. Navigate to this directory:
```bash
cd valentine-vercel
```

3. Deploy:
```bash
vercel
```

4. Follow the prompts:
   - Set up and deploy? **Y**
   - Which scope? (select your account)
   - Link to existing project? **N**
   - Project name? (press enter or type a name)
   - Directory? **.**
   - Want to override settings? **N**

5. Your site will be live! 🎉

### Method 2: Deploy via Vercel Dashboard

1. Go to [vercel.com](https://vercel.com) and sign in
2. Click "Add New" → "Project"
3. Click "Import Git Repository" or drag & drop this folder
4. Click "Deploy"

### Method 3: Deploy via GitHub

1. Create a new GitHub repository
2. Push this folder to the repository:
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin YOUR_GITHUB_REPO_URL
git push -u origin main
```

3. Go to [vercel.com](https://vercel.com)
4. Click "Import Project" → "Import Git Repository"
5. Select your repository
6. Click "Deploy"

## Local Development

Simply open `index.html` in your web browser. No build process needed!

## Customization

Edit `index.html` to customize:
- Messages in the `noTexts` array
- Colors in the CSS gradient
- Success message text
- Date plan message

## Troubleshooting

**Issue: "No" button not shrinking**
- Already fixed! The button now properly shrinks with each click

**Issue: Not working on mobile**
- Already fixed! Full touch event support added

**Issue: Vercel deployment fails**
- Make sure you have `vercel.json` in the root directory
- Ensure `index.html` exists
- Try deploying via CLI instead of drag-and-drop

## License

Free to use for personal Valentine's projects! 💝
