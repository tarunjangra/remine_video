Installation
===========

#. Clone this plugin in redmine_root/plugins/
#. Go to redmine_root
#. rake redmine:plugins:migrate  RAILS_ENV=production

Uninstallation
=============

#. Go to redmine_root
#. rake redmine:plugins:migrate NAME=redmine_video VERSION=0  RAILS_ENV=production
#. Delete the plugin directory

Feature
=======

Currently it is supporting youtube and vimeo to embed videos in wiki. You can call macros {{youtube(id,width,height)}} and {{vimeo(id,width,heigh)}}


Compatible
==========

Tested with Redmine 3.2.0


