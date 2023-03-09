su username: switches to that user
whoami: shows the current user
groups: lists all groups the user is part of
chown: changes the owner of a file
touch: creates a file
chmod u+x filename: adds an execute permission to the user for filename
chmod u+x g+x o+r filename: adds execute permissions to owner,group and read permissions to other
chmod a+x adds execute permissions to everyone
chmod 007: owner,group >> no permissions and all permissions for others
chmod --ref file: mirrors the permissions
