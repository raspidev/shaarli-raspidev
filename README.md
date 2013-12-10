shaarli-raspidev
================

Shaarli modified by Raspidev.  
The personal, minimalist, super-fast, no-database delicious clone by sebsauvage

You want to share the links you discover ? Shaarli is a minimalist delicious clone you can install on your own website.  
It is designed to be personal (single-user), fast and handy.

My project on bitbucket :

https://bitbucket.org/raspidev/shaarli-raspidev

demo : http://raspidev.fr.nf/

Original : http://sebsauvage.net/wiki/doku.php?id=php:shaarli

### Original features:  
 * Minimalist design (simple is beautiful)  
 * FAST  
 * Dead-simple installation: Drop the files, open the page. No database required.  
 * Easy to use: Single button in your browser to bookmark a page  
 * Save url, title, description (unlimited size). Classify links with tags (with autocomplete)  
 * Tag renaming, merging and deletion.  
 * Automatic thumbnails for various services (imgur, imageshack.us, flickr, youtube, vimeo, dailymotion…)  
 * Automatic conversion of URLs to clickable links in descriptions. Support for http/ftp/file/apt protocols.  
 * Save links as public or private  
 * 1-clic access to your private links/notes  
 * Browse links by page, filter by tag or use the full text search engine  
 * Permalinks (with QR-Code) for easy reference  
 * Tag cloud  
 * Picture wall (which can be filtered by tag or text search)  
 * “Links of the day” Newspaper-like digest, browsable by day.  
 * “Daily” RSS feed: Get each day a digest of all new links.  
 * RSS and ATOM feeds (which can be filtered by tag or text search)  
 * PubSubHubbub protocol support  
 * Easy backup (Data stored in a single file)  
 * Compact storage (1315 links stored in 150 kb)  
 * Mobile browsers support  
 * Can import/export Netscape bookmarks (for import/export from/to Firefox, Opera, Chrome, Delicious…)  
 * Automatic ban of IP address upon too many failed logins  
 * Protected against XSRF, session cookie hijacking.  
 * Automatic removal of annoying FeedBurner/Google FeedProxy parameters in URL (?utm_source…)  
 * Shaarli is a bookmarking application, but you can use it for micro-blogging (like Twitter), a pastebin, an online notepad, a snippet repository, etc.  
 * You will be automatically notified by a discreet popup if a new version is available  
 * Pages are easy to customize (using simple RainTPL templates)  
  
### More feature add by Raspidev :  
 * Search by term or tags in picwall  
 * Integration of a Tag cloud 3D (http://www.goat1000.com/tagcanvas.php)  
 * Partially modified to bootstrap (http://getbootstrap.com/)  
 * Theme responsive bootstrap with compact Admin menu and nice mobile design  
 * Add link to go to top  

### Screenshot :  

![http://raspidev.files.wordpress.com/2013/10/capture-public-index.png](http://raspidev.files.wordpress.com/2013/10/capture-public-index.png)  

 * Mobile view:  
![http://raspidev.files.wordpress.com/2013/10/capture-public-index-mobile1.png](http://raspidev.files.wordpress.com/2013/10/capture-public-index-mobile1.png)  

### TODO :  
 * add traduction system  
 * share links to twitter, google...  
 * pdf snapshot page system  
 * include pic in desciption link  
 * more...  
  
------------------------------------------------------------------------------

Requires php 5.1 (php 5.2 required for autocomplete.)

More information on the original project page:
http://sebsauvage.net/wiki/doku.php?id=php:shaarli

------------------------------------------------------------------------------

Shaarli is distributed under the zlib/libpng License:

Copyright (c) 2011 Sébastien SAUVAGE (sebsauvage.net)

This software is provided 'as-is', without any express or implied warranty.
In no event will the authors be held liable for any damages arising from
the use of this software.

Permission is granted to anyone to use this software for any purpose,
including commercial applications, and to alter it and redistribute it 
freely, subject to the following restrictions:

  1. The origin of this software must not be misrepresented; you must not 
     claim that you wrote the original software. If you use this software
     in a product, an acknowledgment in the product documentation would
     be appreciated but is not required.

  2. Altered source versions must be plainly marked as such, and must
     not be misrepresented as being the original software.

  3. This notice may not be removed or altered from any source distribution.

------------------------------------------------------------------------------
