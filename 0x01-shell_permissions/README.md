0. su betty: to switch the current user to betty.
i. whoami: To print the effective username of the current user.
2. groups: to print all the group the current user is part of.
3. chown betty hello: change the owner of the file hello to betty.
4. touch hello: create an empty file.
5. chmod u+x hello :Add execute permission to the owner of the file hello.
6. chmod ug+x,o+r hello: add execute permission to owner and group owner while read permission to other userfor the file hello.
7. chmod ugo+x hello: add executeable permission to wner, group owner and other user of the file hello.
8. chmod 007 hello: set the file hello to, no permission, no permission all permission.
9. chmod 753 hello: set the permission of the file hello to rwxr-x-wx.
10. chmod --reference=olleh hello: set the mode of the file hello same as the olleh mode.
11. chmod ugo+x */: add executable permission to all subdirectories of the current directory, group and user.
12. mkdir -m 751 my_dir: script to create a directory with permission 751 called my_dir.
13. chgrp school hello: change the group for the file hello to school.
14. chown vincent:staff *: change the owner to vincent and group owner to staff for all files in the directory.
15. chown -h vincent:staff _hello:change the owner and group owner of hello to vincent and staff respectively.
16. chown --from=guilluame betty hello: change the ownership of hello to betty if its own by guilluame.
17. telnet towel.blinkenlights.nl: play the star war theme.
