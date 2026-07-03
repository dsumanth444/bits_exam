# Question 3 Explanation

I created an original file, a hard link, and a symbolic link to observe how Linux handles file references. The experiment showed that hard links share the same inode and remain available after the original name is removed, while symbolic links depend on the target path and break when that path no longer exists.
