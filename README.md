# IMODS landing page staging area.

* [Original Weebly](http://imod-asu.weebly.com/)
* [Staging Ground](https://imod-asu.github.io/)
* [Live Landing Page](http://imod.poly.asu.edu/)

This repo is to keep a copy of the weebly site, and to have a testing ground to ensure the pages work before they are loaded onto the server.

### How to Update
1. Open the [weebly editor](http://www.weebly.com/weebly/userHome.php)
2. Click `settings`
3. Scroll down to `archive`
4. Enter your email address and click `Email Archive`
6. Open your email
7. Download the attached archive
8. Open GIT client
9. Clone https://github.com/IMOD-ASU/IMOD-ASU.github.io.git
10. Open the cloned folder
11. Unzip the Archive
12. Paste the contents of the archive in the git folder
13. `add`, `commit` files in git client
14. `push` file up to this repo
15. Open https://imod-asu.github.io/ and click around to make sure nothing is broken
16. Login to the IMODS server
17. `clone` this git repo on the server
18. move the contents of the repo to `/var/www`
19. Open http://imod.poly.asu.edu and make sure nothing is broken
