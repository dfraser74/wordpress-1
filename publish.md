## Instructions

cd wordpress-org

To update the svn trunk:
* svn ci -m "My comment"

To update a new version
* svn ci -m "Tagging v1.0.5"
* svn cp trunk tags/1.0.5
* svn ci -m "Tagging v1.0.5"


To update only the README -> make sure you tag the version in the trunk as trunk (not the actual version)