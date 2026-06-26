============================================================
  JANAKI PHOTOGRAPHY PORTFOLIO
  How to use this website
============================================================

FOLDER STRUCTURE
----------------
janaki-portfolio/
├── index.html        ← Open this in your browser to view the site
├── photos.js         ← Edit this to add your photo filenames
└── images/
    ├── hero/         ← 1 photo for the homepage background
    ├── sunset/       ← Your sunset photos go here
    ├── sunrise/      ← Your sunrise photos go here
    ├── nature/       ← Your greenery/nature photos go here
    ├── macro/        ← Your macro/insect/close-up photos go here
    ├── flowers/      ← Your flower photos go here
    └── sky/          ← Your sky/clouds/stars photos go here


HOW TO ADD YOUR PHOTOS — 3 EASY STEPS
--------------------------------------
STEP 1: Copy your photo into the right folder.
        Example: copy "sunset1.jpg" into the images/sunset/ folder

STEP 2: Open photos.js in Notepad (or any text editor).
        Find the matching category and add the filename like this:

          sunset: [
            'sunset1.jpg',
            'golden-sky.jpg',
          ],

        (Make sure each filename has quotes and a comma after it)

STEP 3: Save photos.js, then open index.html in your browser.
        Your photo will appear automatically!


TIPS
----
- Supported formats: JPG, JPEG, PNG, WEBP, HEIC
- You can add unlimited photos — no limit!
- For the hero background, put 1 image in images/hero/ and
  update the hero line in photos.js:  hero: 'your-image.jpg',
- To remove a photo, delete it from the folder and remove
  its filename from photos.js

VIEWING THE SITE
----------------
Simply double-click index.html to open it in your browser.
No internet connection needed (except to load fonts the first time).

============================================================
