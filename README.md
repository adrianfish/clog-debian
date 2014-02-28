CLOG Debian
===========

A debian package build for CLOG.

Build your CLOG source into this directory using the maven.tomcat.home
directive. Modify the debian/control file so you don't depend on the 'sakai'
package, modify the debian/install file so your CLOG artefacts go into the
right place, update debian/changelog to reflect the new version, then run:

debuild --no-lintian -us -uc

CLOG's .deb file will be be built into the directory above this one.
