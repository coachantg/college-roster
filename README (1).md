# Team Esface College Prep Elite - Roster

An interactive, searchable roster page for Team Esface's College Prep Elite basketball program. Coaches can view player profiles, contact information, and highlight videos.

## Features

- **Filterable roster** - Filter players by graduation year (2026, 2027, 2028) and team (16U Elite, 17U Elite)
- **Player profiles** - Click any player card to view full details including:
  - Photo and physical measurements
  - High school and coach contact info
  - GPA and test scores
  - Highlight videos (YouTube, Hudl, etc.)
  - Player and parent/guardian contact information
  - Social media handles (Instagram, X/Twitter)
- **Mobile responsive** - Works on phones, tablets, and desktops
- **Fast loading** - Single HTML file, no dependencies

## How to Update the Roster

To add new players or update existing player information:

1. Open `index.html` in a text editor (VS Code, Notepad, etc.)
2. Find the `const players = [` section (around line 400)
3. Add a new player object following this format:

```javascript
{
    id: 15,
    name: 'Player Name',
    team: '16U Elite',
    class: '2028',
    position: 'Point Guard',
    height: '6\'2"',
    weight: '180',
    wingspan: '75"',
    hs: 'High School Name, City',
    hsCoach: 'Coach Name',
    hsCoachPhone: '555-555-5555',
    gpa: '3.5',
    playerPhone: '555-555-5555',
    parent: 'Parent Name',
    parentEmail: 'parent@email.com',
    parentPhone: '555-555-5555',
    instagram: '@handle',
    twitter: '@handle',
    photo: 'https://drive.google.com/thumbnail?id=PHOTO_ID&sz=w400',
    videoType: 'youtube', // or 'hudl', 'drive', 'twitter', 'instagram', 'none'
    videoLink: 'https://youtube.com/watch?v=...' // or video URL
}
```

4. Save the file
5. Commit and push to GitHub (changes go live automatically)

## GitHub Pages Setup

This site is hosted on GitHub Pages. To set it up:

1. Create a GitHub account at github.com
2. Create a new repository named `college-roster`
3. Upload `index.html` and `README.md` to the repository
4. Go to **Settings** → **Pages**
5. Select **Deploy from a branch** and choose **main** branch
6. Your site will be live at: `https://yourusername.github.io/college-roster`

## Video Link Types

- **YouTube** - Full videos (not Shorts). Use the video ID from the URL.
- **Hudl** - Paste the full Hudl profile or highlight link
- **Google Drive** - Share the full drive link
- **Twitter/X** - Link to the post/video
- **Instagram** - Link to the post
- **None** - If no video is available yet

## Contact

For questions or to add/update players, contact the Team Esface College Prep Program.

---

**Last Updated:** April 1, 2026  
**Total Players:** 14
