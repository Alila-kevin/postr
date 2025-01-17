This is a demo blogging application that will allow users to post text entries,
images, quotes, links, conversations, videos, and audio. Currently only the
basic text entries functionality is implemented. It is developed as an example
Zend Framework application for the January 28, 2010 meeting of the Burlington,
VT PHP Users Group.

http://btvphpug-2010-01.eventbrite.com/

Installation
============

This application requires that you have Zend Framework on your include_path. If
you do not yet have Zend Framework then you can get it from one of the following
sources:

 * Official Release:
   http://framework.zend.com/download/latest

 * Subversion; use either the current trunk or the 1.10 release branch:
   svn checkout http://framework.zend.com/svn/framework/standard/trunk/library/Zend

   svn checkout http://framework.zend.com/svn/framework/standard/branches/release-1.10/library/Zend

 * PEAR:
   pear channel-discover pear.zfcampus.org
   pear install zfcampus/zf

Once Zend Framework is installed, configure your server's document root to be
the "public" directory within this application.

To setup the SQLite database:

    cd scripts
    php load.sqlite.php

REQUEST
========

If you have any feature requests, please send them to:

    Bradley Holt <bradley.holt@foundline.com>

Alternatively, you can fork this project on GitHub and add whatever features
you want:
http://github.com/bradley-holt/postr

Zend Framework Components
=========================

Zend Framework components used include:

 * Zend_Tool
 * Zend_Application
 * Zend_Layout
 * Model–View–Controller (MVC) components
 * Zend_Test
 * Zend_Form
 * Zend_Db_Table
 * Zend_Date
 * Zend_Markup
 * Zend_Paginator
 * Zend_Navigation
 * Controller Plugins

LICENSE
=======

Please see LICENSE.txt 
