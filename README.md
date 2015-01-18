Glade Rom
---------------

To get started with GLADE ROM, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To Initialize your local repository using the Glade Rom trees, use a command like this:

    repo init -u git://github.com/TeamGlade/android.git -b <branch>

Then to sync up:

    repo sync

Then to build:

     cd <source-dir>; . build/envsetup.sh; brunch <device_name>

