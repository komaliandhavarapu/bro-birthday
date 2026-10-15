BROTHER BIRTHDAY WEBSITE — QUICK SETUP

PERSONALIZE THE WEBSITE
1. Open config.js in a text editor.
2. Change recipient.name, recipient.relation, and recipient.birthdayDate.
   Leave birthdayDate empty to hide the date on the birthday page.
3. Edit the copy, letter, and memories entries to change the page wording,
   birthday letter, memory cards, and final wishes.
4. Change siteTitle to update the browser tab title.

ADD PHOTOS AND MUSIC
- Put your own image files in the photos folder and set the matching file paths,
  alternative text, and captions in the photos list in config.js.
- Put an MP3 in the music folder and set music.src in config.js to its path.
- Adjust music.volume in config.js to a number from 0 to 1.
- The music starts only after the visitor taps Play, as required by browsers.
- Missing photos remain as designed placeholders. A missing song shows an error
  on the music control.

No photo or music files were included in the supplied project; the photos and
music folders contain setup instructions only. Add media you have permission
to use.

Open index.html in a browser, or upload the entire folder to a static host.
Keep config.js, index.html, and the photos/music folders together. The page's
existing seven-screen design, responsive layout, animations, and reduced-motion
accessibility support remain in place.
