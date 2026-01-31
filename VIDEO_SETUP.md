# How to Add Your Google Drive Videos

## Step 1: Get Video File IDs

You have 9 videos in your Google Drive folder. To use them in the portfolio:

1. **Open the folder**: https://drive.google.com/drive/folders/1n6eRTxIbjfBUNqDWc0NYLHOIhI5X7dUL

2. **For each video file**:
   - Right-click on the video
   - Select "Get link" or "Share"
   - Make sure sharing is set to "Anyone with the link can view"
   - Copy the link (it will look like: `https://drive.google.com/file/d/FILE_ID_HERE/view`)
   - Extract the **FILE_ID** from the middle of the URL

3. **Example**:
   - Full link: `https://drive.google.com/file/d/1abc123XYZ456def/view`
   - File ID: `1abc123XYZ456def`

## Step 2: Video Mapping

Based on your folder, here are the videos to map:

| Portfolio Project | Video File | Current Placeholder |
|-------------------|------------|---------------------|
| Project 1 - Brand Campaign 2026 | AM portfolio | placeholder1 |
| Project 2 - Tech Startup Explainer | Am portfolio 2 | placeholder2 |
| Project 3 - Instagram Reels Series | AM Portfolio 3 | placeholder3 |
| Project 4 - Short Film "Moments" | AM portfolio 4 | placeholder4 |
| Project 5 - Product Launch Video | AM portfolio 5 | placeholder5 |
| Project 6 - Logo Animation Pack | AM portfolio 6 | placeholder6 |
| Project 7 - TikTok Viral Series | AM portfolio 7 | placeholder7 |
| Project 8 - Music Video "Echoes" | AM portfolio 8 | placeholder8 |
| Project 9 - Corporate Overview | AM PORTFOLIO.mp4 | placeholder9 |

## Step 3: Update index.html

Once you have the File IDs, search for each placeholder in `index.html` and replace:

**Find**: `data-video="https://drive.google.com/file/d/placeholder1/preview"`
**Replace with**: `data-video="https://drive.google.com/file/d/YOUR_FILE_ID_HERE/preview"`

## Quick Replace Template

Replace these lines in index.html:

```html
<!-- Line 123 -->
data-video="https://drive.google.com/file/d/placeholder1/preview"
→ data-video="https://drive.google.com/file/d/YOUR_FILE_ID_1/preview"

<!-- Line 144 -->
data-video="https://drive.google.com/file/d/placeholder2/preview"
→ data-video="https://drive.google.com/file/d/YOUR_FILE_ID_2/preview"

<!-- Line 165 -->
data-video="https://drive.google.com/file/d/placeholder3/preview"
→ data-video="https://drive.google.com/file/d/YOUR_FILE_ID_3/preview"

<!-- Line 186 -->
data-video="https://drive.google.com/file/d/placeholder4/preview"
→ data-video="https://drive.google.com/file/d/YOUR_FILE_ID_4/preview"

<!-- Line 207 -->
data-video="https://drive.google.com/file/d/placeholder5/preview"
→ data-video="https://drive.google.com/file/d/YOUR_FILE_ID_5/preview"

<!-- Line 228 -->
data-video="https://drive.google.com/file/d/placeholder6/preview"
→ data-video="https://drive.google.com/file/d/YOUR_FILE_ID_6/preview"

<!-- Line 249 -->
data-video="https://drive.google.com/file/d/placeholder7/preview"
→ data-video="https://drive.google.com/file/d/YOUR_FILE_ID_7/preview"

<!-- Line 270 -->
data-video="https://drive.google.com/file/d/placeholder8/preview"
→ data-video="https://drive.google.com/file/d/YOUR_FILE_ID_8/preview"

<!-- Line 291 -->
data-video="https://drive.google.com/file/d/placeholder9/preview"
→ data-video="https://drive.google.com/file/d/YOUR_FILE_ID_9/preview"
```

## Need Help?

If you provide me with the individual file links for each video (right-click > Get link on each video in the folder), I can update them automatically for you!

Just share:
1. Link to AM portfolio
2. Link to Am portfolio 2
3. Link to AM Portfolio 3
... and so on
