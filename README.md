# Live at Opio · Club Med Makers · 9-12 November 2026

A responsive, static English website for the thirteen event listings supplied. Newsreader Bold/italic, Inter Medium/Semibold/Bold and the Makers palette. Original supplied photos are used as illustrative event imagery; the Korben listing does not claim to depict the performer.

## Publish
Upload ALL the contents of this folder to a new GitHub repository. Connect it to Netlify, leave the build command empty, and use `.` as the publish directory. Or drop the whole folder into Netlify Drop. Open index.html for a local preview.

## Easy updates
Open editor.html locally or on the site. Change dates, times, places, text or image selection. Click “Download updated events-data.js”. Upload that downloaded file over events-data.js in GitHub and commit. The editor does NOT update the live site automatically and does not save edits if you close it before downloading.

No Excel or Power Automate connection is active in this version. Everything displayed lives in events-data.js; this can later be supplied by a sync endpoint if required. There is no backend, login or private data in the editor.

## Schedule details
Events finishing before their start clock time end the following day. These show “+1 day” and the live indicator uses the correct overnight interval. Times use Europe/Paris. The page opens on the event day when that day is in the schedule, otherwise Monday 9 November. Specific-day links use `?day=2026-11-10`. Only one day is shown; there is no All view.

Provençal Lunch takes place at the Oliveraie. Closing Party takes place at Bar du Loup. Sportive Evening has no venue line: guests join their chosen sports activity. Photo cards display the time, event title, venue and short description directly. There is no flip or expand interaction. The day navigation shows only the selected date. The page uses an editorial navy layout, large photographs, cream Newsreader headings and lavender italic accents. All information remains visible without expanding or flipping.

All page copy is English. No emojis. Use the supplied programme and Hub links in events-data.js as references; the matching navigation URLs are in index.html.

The new supplied party photograph is used as the cover, with equal mobile side margins and a landscape crop focused on both faces. Event counts and category labels are hidden. Venue and time appear together below each title, with small SVG line icons; no emoji arrows are used.

Minimal edition: mobile cover uses 16:10, desktop 2:1. Intro slogans, dress-code display and the lower programme promotion have been removed. The footer includes a simple Your Programme link.
