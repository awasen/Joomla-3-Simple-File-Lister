Joomla-3-Simple-File-Lister
===========================

Joomla 3 Extension Module - Simple File Lister v1.0

The idea behind Simple File Lister is to use it in combination with Simple File Upload (http://extensions.joomla.org/extensions/core-enhancements/file-management/8424) to list the files in a directory.

It can also be used to list any directory with files beside an article.
Imagine you have a F.A.Q. and some PDF files that goes with it, then have your F.A.Q. article and add Simple File Lister as a module on that page and provide the directory for the directory with PDF's and Simple File Lister will automatically provide a list of URL's for each PDF.

Another use is to use it for a user so that they can keep track, and use, the files they have uploaded through Simple File Upload.

I have now worked a bit on the design and changed from using a UL/LI list which seemed to cause problems on several templates to instead use DIV's for the list.

Added the possibility to add icons and thumbnails.
Also added support to list directories.

Update 2011-02-13:
- Joomla 1.6 now also supported as parallel package.
- Swedish added to languages.

Update 2011-02-13:
- Added support for Ajax when stepping through directory list, i.e. the whole page don't need reloading if using Next/Previous buttons.
- Added jQuery conflict support between "Simple File Upload" and "Simple File Lister" (Technical: $app->set('jquery', 'true'))

Update 2011-02-17:
- Added functionality to browse sub-directories.
- Added setting for allowing browse of sub-directories.
- Added breadcrumb when browsing through sub-directories.

Update 2011-03-05:
- Added support for sorting files by name.
- Added setting for "user sort" and "default" sort order.
- Added Module Class Suffix property.

Update 2011-03-24:
- Bug fix, relative paths, like "./../tmp/" was not showing the correct links.

Update 2011-05-21:
- Bug fix, paths gone wrong if using a sub-domain like "http://sub.domain.com" instead of "http://domain.com/sub". Server base path must be set under advanced parameters!

EDIT 2011-05-22: Delete function added!
You can now set Simple File Lister to allow the user to delete files in the list. You can set it to allow delete for any user, even not logged in (NOT RECOMMENDED!) or on registered and logged in users or only those users who are set as "Editors" in your Joomla site.
I also fixed a bug that threw you back to default directory if changing the sort order inside a sub-directory.
Please use the delete function with care!

Joomla 3.0 version released in separate package!
