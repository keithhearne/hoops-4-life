# Source for Hoops 4 Life

- `game-source.html` is the master game file (the preview build: `TEST_UNLOCK=true`).
- To make the site: set `TEST_UNLOCK=false`, then `python3 -I tools/build_site.py game-source.html .. <version>`.
- `tools/` has the build script, the sound builders (`make_sounds.py`, `make_crowd_loops.py`, `make_rim.py`; they need the CC0 recordings listed in the main README) and the patch scripts used along the way.
