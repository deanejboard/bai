# Customer story template — internal preview

Password-protected prototypes of the customer story page: the September options (root) and the v2 adaptive template (`v2/`), built on board.com's own stylesheet.

The page HTML is AES-256-GCM encrypted (PBKDF2-SHA256, 310k iterations); the copy and markup are only readable with the access password.

Files under `assets/` and `v2/assets/img/` are **not** encrypted — that is board.com's public stylesheet plus images already published on board.com and Vimeo thumbnails. v2's own CSS, scripts and data are inside the encrypted pages.

Built from a separate source folder. Do not edit these files by hand.
