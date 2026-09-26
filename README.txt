SHARMILA BIRTHDAY COUNTDOWN WEBSITE ❤️

FOLDER STRUCTURE
----------------
Sharmila_Birthday_Countdown/
│
├── index.html
├── happy-birthday.mp3   <-- PUT YOUR HAPPY BIRTHDAY MP3 HERE
├── song.mp3             <-- OPTIONAL: put "Amar name er roddure" here
└── images/
    ├── sharmila-1.jpg
    └── sharmila-2.jpg


HOW TO ADD THE HAPPY BIRTHDAY SONG
-----------------------------------
1. Take your Happy Birthday MP3.
2. Rename it exactly:
       happy-birthday.mp3
3. Put it in the SAME folder as index.html.

The final structure should look like:

Sharmila_Birthday_Countdown
   index.html
   happy-birthday.mp3
   song.mp3
   images
      sharmila-1.jpg
      sharmila-2.jpg


HOW IT WORKS
-------------
Before midnight:
- Sharmila sees the countdown.
- She clicks "Open Your Surprise".
- This user interaction helps the browser permit audio playback.

At exactly 12:00 AM on September 27, 2026:
- Countdown reaches zero.
- Full-screen "Happy Birthday Sharmila" appears.
- Confetti starts.
- happy-birthday.mp3 starts playing.
- Clicking "Open My Birthday Message" takes her back to the page.


HOW TO RENDER / TEST
--------------------
OPTION 1 - SIMPLE:
Double-click index.html.

OPTION 2 - VS CODE:
1. Open this folder in VS Code.
2. Install the "Live Server" extension.
3. Right-click index.html.
4. Click "Open with Live Server".
5. Your browser will open the website.


IMPORTANT:
The real countdown targets:
September 27, 2026, 12:00 AM India time (UTC+05:30).

To test the midnight screen immediately, temporarily change:
const birthday = new Date("2026-09-27T00:00:00+05:30").getTime();

to a time a few minutes in the future.


DEPLOYMENT:
Upload the folder to GitHub Pages, Netlify, or Vercel.
