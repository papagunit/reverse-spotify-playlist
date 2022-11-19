
# Spotify Playlist Reverser

**Intro:**
I suppose there could be alternative use cases, but as a Tesla owner, and avid Spotify user since 2011, I had become accustomed to playing my starred playlist (back when that was a thing) in the order from most recently added down to last added. Even in future Spotify updates, you can usually change the sort order (but I do remember a dark time when that wasn't possible on mobile...anyways). Once we acquired a Tesla, we were beholden to the default interface provided to which I discovered that you cannot change the sort order on a playlist within the interface, forcing me to start with my oldest added tracks first and usually resort to shuffle play (you better love that first track you added 10 years ago!). This has always irked me, and I wondered if there was a solution for this. I found Fitzgerald's bash script, and was amazed at the simplicity of the solution and thought: what if I could schedule this to run daily? Sure, creating a reversed playlist is somewhat of a win, but I'm very much into music discovery and love adding new tracks. Must I fire up this script every time?

---
### Features:
✅Configure once and schedule for automation (cron job?)
✅No machine required, just fork and utilize GitHub actions with environment variables
✅Will always copy from the same playlist and reverse into the same reverse playlist. No new lists, no overwriting of source playlist.
---
### Inputs:
* Authentication?
* Playlist ID Reverse
* Playlist ID Result
* ---
### To do:

* [ ] Figure out authentication flow, then adapt it for the action- [ ] 
* [ ] Reverse engineer the other process- [ ] 
* [ ] Write the solution in TypeScript

---
##### References/Sources of inspiration
https://github.com/watsonbox/exportify - reference a JS project
https://github.com/FitzgeraldKrudde/spotify-reverse-playlist - Reverse engineering this reversal process
https://docs.getnacelle.com/deployment/scheduled-builds-github-actions.html#add-the-webhook-url
https://dev.to/anshuman_bhardwaj/free-cron-jobs-with-github-actions-31d6