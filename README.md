# IEEE DIU SB SIGHT Group Website

A responsive static website for the IEEE DIU SB SIGHT Group Idea Competition.

Published site: https://ea-arnob-07.github.io/IEEE-DIU-SB-SIGHT-WEBSITE/

## Pages

- `index.html` - competition overview, focus areas, awards, eligibility, fees, submission process, timeline, judging criteria, and contact details.
- `registration/index.html` - participant registration form.
- `reg/index.html` - idea submission form.

## Assets

- `assets/css/site.css` - shared responsive styles.
- `assets/js/site.js` - mobile navigation, hero slideshow, reveal effects, and back-to-top control.
- `assets/ceremony/` - event photographs used in the home-page hero slideshow.

## Local preview

Run a local web server from the project folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/` in a browser.

The registration and idea-submission pages embed their existing Google Forms.
