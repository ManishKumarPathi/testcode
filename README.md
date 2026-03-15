# Birthday Page Setup Instructions

## Step 1: Add Your Photos

1. Put 4 photos in the same folder as `birthday.html`
2. Name them: `photo1.jpg`, `photo2.jpg`, `photo3.jpg`, `photo4.jpg`
3. Edit the captions in the HTML file if you want (or keep them as is)

## Step 2: Test It Locally

- Just double-click `birthday.html` to open it in your browser
- Make sure the photos show up correctly

## Step 3: Host It Online (Choose ONE option)

### OPTION 1: Python Server (Simplest - Works for 1 day)
1. Open Terminal in this folder
2. Run: `python3 -m http.server 8000`
3. Use a service like **ngrok** to make it accessible:
   - Install ngrok: https://ngrok.com/download
   - Run: `ngrok http 8000`
   - Share the URL it gives you

### OPTION 2: Netlify Drop (Super Easy - Free)
1. Go to https://app.netlify.com/drop
2. Drag and drop ALL files (birthday.html + all photos)
3. Get your link instantly - it stays online forever

### OPTION 3: GitHub Pages (Free - Permanent)
1. Create a GitHub account if you don't have one
2. Create a new repository (make it public)
3. Upload birthday.html and all photos
4. Go to Settings → Pages → Enable GitHub Pages
5. Share the link

### OPTION 4: Surge.sh (Quick)
1. Install: `npm install -g surge`
2. Run: `surge`
3. Follow prompts, get your link

## Personalization Tips

- Edit the birthday message in the HTML file
- Change colors by modifying the CSS gradient
- Add more or fewer photos (remember to update the dots too)

Enjoy! 🎉
