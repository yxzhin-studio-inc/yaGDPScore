# yaGDPScore
## yet another geometry dash private server emulator

## note: still in development
## currently only gd 2.2 is supported

## features
1. various exploits fixed (spam, user stats multiplying, invalid data inserting, etc.)
2. some small security features (account/level ID randomizer, strict data filter, etc.)
3. working level reupload using proxy (optional)
4. better discord integration (optional)
5. accounts/reuploads limit per ip (configurable)
6. better dashboard (configurable)
7. auto creator points (configurable)
8. email verifying (optional)
9. better logs (configurable)
10. song reupload by file (configurable)

## requirements
1. php >7 (tested on 8.2)
2. discord webhook/bot for discord integration (if enabled)
3. smtp server for email verifying (if enabled)

## setup
1. upload all from `src\your_gd_version` on the webserver
2. edit `yacore\config\connection.php` & other configs
3. import `src\your_gd_version.sql` into the database

## updating
1. check updates using dashboard
2. delete required files
3. upload new files from `src\your_gd_version`
