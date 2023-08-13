# Description 

Because of Yakui The Maid being displayed as YAKUITHEMAID on bandcamp (and therefore in tracks metadata too), scrobbling services might not recognize the artist properly. This script renames every album folder, every track file, and, most importantly, edits metadata of every FLAC, which is supposed to solve the problem with misscrobbling.

# Usage (requires node.js)

1. Download/copy the main.js file and place it somewhere.
2. Open it and place the root path to albums into "dir" const.
3. `node path/to/main.js`.
