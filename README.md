# system-mariadb

Forked version of mariadb in a chroot with ClearOS changes applied

* git clone git+ssh://git@github.com/clearos/system-mariadb.git
* cd system-mariadb
* git checkout c7
* git remote add upstream git://git.centos.org/rpms/mariadb.git
* git pull upstream c7
* git checkout clear7
* git merge --no-commit c7
* git commit
