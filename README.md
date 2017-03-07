# MD5_DirectoryChecker.sh
Used for making an MD5 hash of a directory

Verifies the validity of files in a folder by listing all files in that directory, of which an md5 sum is computer for each.
# AWK is used to pick off the MD5 sums, ignoring filenames.  The sums are then sorted, and an md5 sum of the sorted list is returned.
