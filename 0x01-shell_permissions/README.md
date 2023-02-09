File ./0-iam_betty: It runs the su command to switch the current user to "betty".

File ./100-change_owner_and_group: It changes the owner and group of all files in the current directory to "vincent" and "staff", respectively, using the chown command.

File ./101-symbolic_link_permissions: It changes the owner and group of the symbolic link "_hello" to "vincent" and "staff", respectively, using the chown command with the -h option.

File ./102-if_only: It changes the owner of the file "hello" from "guillaume" to "betty", using the chown command with the --from option.

File ./103-Star_Wars: It opens a Telnet connection to the address "towel.blinkenlights.nl" using the telnet command.

File ./10-mirror_permissions: It changes the permissions of the file "hello" to match the permissions of the file "olleh", using the chmod command with the --reference option.

File ./11-directories_permissions: It grants execute permission to all directories (recursively) in the current directory, using the chmod command with the -R and a+X options.

File ./12-directory_permissions: It creates a directory named "my_dir" with permissions 751, using the mkdir command with the -m option.

File ./13-change_group: It changes the group of the file "hello" to "school", using the chgrp command.

File ./1-who_am_i: It prints the current user name, using the whoami command.

File ./2-groups: It prints the groups the current user belongs to, using the groups command.

File ./3-new_owner: It changes the owner of the file "hello" to "betty", using the chown command.

File ./4-empty: It creates an empty file named "hello", using the touch command.

File ./5-execute: It grants execute permission to the owner of the file "hello", using the chmod command with the u+x option.

File ./6-multiple_permissions: It grants execute permission to both the owner and the group of the file "hello", and grants read permission to others, using the chmod command with the ug+x,o+r options.

File ./7-everybody: It grants execute permission to all users for the file "hello", using the chmod command with the a+x option.

File ./8-James_Bond: It sets the permissions of the file "hello" to 007 (rwx for the owner, no permissions for the group and others), using the chmod command with the 007 argument.

File ./9-John_Doe: It sets the permissions of the file "hello" to 753 (rwx for the owner, r-x for the group and others), using the chmod command with the 753 argument.
