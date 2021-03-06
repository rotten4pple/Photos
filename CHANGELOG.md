<a name="1.4.0"></a>
# 1.4.0 (2014-05-24)

## Bug Fixes

- **Admin**
  - Fix album items hides count
  - Move global counts commented code into true api command named "counts"

- **Common**
  - Remove back homepage button on homepage

- **Featured**
  - Fix Featured animation in Responsive mode

- **API**
  - Increase API PHP time limit to prevent banners generation fails

- **Worker**
  - Re-sync all counts in all folders and global counts at the end of a Worker processing


## Breaking Changes

- **Videos**
  - Add possibility to define the thumbnail of a video from a frame number

- **Admin**
  - Add loading animation when administrator changing view mode

- **Worker**
  - Now, administrators start Worker manualy
  - Administrators can't start Worker on mobiles

- **New browsers support**
  - ✔ Chrome desktop
  - ✔ IE 10+ desktop
  - ✔ Firefox desktop
  - ✔ Safari desktop
  - ✔ Opera desktop

  - ✔ iPhone
  - ✔ iPad
  - ✔ IE 10+ Windows Phone
  - ✔ Chrome Android

  - User can zoom photos/video on mobile devices



<a name="1.2.0"></a>
# 1.2.0 (2014-04-27)

## Bug Fixes

- **Common**
  - Display true favicons when no logged user
  - Fix broken folders access with utf8 special characters

- **Admin**
  - Update global count when hidding albums, photos or videos

- **Search**
  - Fix broken tags and identities with spaces
  - Remove tiny white bar when no result

- **User logout**
  - Go back to index on user logout

## Breaking Changes

- **First use**
  - Generate cache folder and copy default banner and logo inside
  - Add gitignore config to remove cache/ and photos/ folders

- **Common**
  - Add back button on logo picture hover

- **Worker**
  - Optimize perfs to generate thumbnails in 10sec max per item!
  - Optimize synchro to remove old folders quickly!
  - Generate newer folders first to optimize perfs
  - Increase script timeout to 120sec

- **Featured**
  - Better featured items transition and pictures quality
  - Sort items to newer first

- **Videos**
  - Generate videos thumbnails from frame number 100 instead of 1

<a name="1.1.0"></a>
# 1.1.0 (2014-04-17)


## Bug Fixes

- **Security**
  - Fix replace photo by access denied picture for no logged user

- **Explorer**
  - Fix reset photo/video global counts

- **Worker**
  - Fix Worker process PHP time limit

- **Viewer**
  - Hide menu button on videos


## Breaking Changes

- **Explorer**
  - Can reset entire folder to reprocess it

- **Worker**
  - Add more stats informations in Worker progress bar only in _admin_ mode
  - Add stop process button in Worker progress bar
  - Thumbnails generation performances improvement

- **Customize**
  - Move customize files to samples usable by adminsys

<a name="1.0.0"></a>
# 1.0.0 (2014-04-11)

First project stable version.