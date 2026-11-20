# Site__Startups__Sgit
sgit.startups.sovereignweb.site: A brochure for sgit, with links to its own site.

How it is built: `content/facts.json` holds every fact with its public source; `python3 tools/build.py` writes the five designs into `site/`; `node tools/shots.js` and `python3 tools/thumbs.py` make the design thumbnails and share card and check phone and desktop, light and dark. See `docs/how-to-add-a-startup.md`, `docs/sources.md` and `docs/questions.md`.
