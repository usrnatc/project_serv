# Home Web Server Project:
## Attempt to host media server from crappy laptop in my room

---

### Components:
- Server
    - needs to be able to run indefinitely
    - needs to be globally accessible
    - needs to be easy to maintain
    - needs to be locally reliant rather than many dependencies
---
- Client
    - needs to be portable, I would like to be able to access the server from Windows and \*nix
    - needs to be easily traversed
    - needs to be responsive, limited to no bloat (JS)
    - nice features:
        - thumbnails for files;
        - file info (size, metadata if available)
        - play media locally
    - webclient for normies, *this will be an extra feature and won't be implemented until after main functionality is completed*
---
- Data
    - store references to files within data structure with high lookup speed (RB trie, Hashmap, Trie, etc.)
    - reliable
    - not reliant on memory
---
# Absolutely no data to be logged whatsoever
