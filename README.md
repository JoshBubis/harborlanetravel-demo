# Harbor Lane Travel (sample)

Fictional independent cruise-advisor site for Josh.Menu demos — especially
useful when talking with travel agents. Positioned as **Galveston specialists**
who book Royal / Carnival / Disney (and elsewhere), not a Liberty-only brochure.

**Not a real client.** Footer and ribbon say so on purpose.

**Live demo (share this):** https://josh.menu/samples/harbor-lane/

Canonical working copy: this folder. After edits, re-copy public files into
`josh.menu/samples/harbor-lane/` and push josh.menu so the cruise URL stays fresh.
(Avoid leading with `joshbubis.github.io/…` — surname in the host.)

```bash
cd /Users/jbair/Projects/clients/harborlanetravel.com
python3 -m http.server 4173
# open http://127.0.0.1:4173
```

Public files only for deploy: `index.html`, `style.css`, `script.js`,
`favicon.svg`, `robots.txt`, `images/`, `fonts/`. Never ship `AGENTS.md`.
