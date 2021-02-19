# updater
A joke version of the a famous updater plugin.\
Ok, a little serious "joke"... I guess...

Basically, I might or might not work a lot on this, but I will try?\
I dunno, we'll see...

**Here's what has changed from the original version:**
1. cURL, Socket and SteamTools have been removed, this plugin now depends on SteamWorks for updating.
2. Updated the syntax to the new style.
3. Fixed compilation errors.
4. Removed Windows line endings (CRLF) and replaced them with Unix style (LF).
5. Fixed the "updater-url" so this plugin can actually auto update itself without errors (hopefully).
6. Changed `sm_updater_check` delay from 1 hour to 10 seconds (Will probably increase it later, but for now, this allows for easier testing).
