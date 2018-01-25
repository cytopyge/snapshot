# snapshot
bash script for snapshotting with rsync

This script can be added to a cronjob. It then creates rsync snapshots of a source folder.

Saving space; only changed files are copied, identical are hard-linked to the inode.
Being save; the script makes a full backup of the snapshot at a customisable interval.

Enjoy and please let me know if you have any improvements!
