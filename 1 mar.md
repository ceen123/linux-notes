
$cd home
//to navigate to the home directory

$cd -
//to change back to the previous working directory

$cd ~
//to navigate back to the home directory

$su
//to activate the super user, with using password of the root

$hostnamectl
//to see current host name


$mkdir /media/VirtualBoxGuestAdditions
$mount -r
//to create and mount the cd drive


$yum install httpd
$yum update kernel
$yum install gcc
//install and update

systemctl start httpd

ls 
//use to see file in current folder

mv filename /var/www/html
//to move to a this current directory “filename”

echo "hello" > filename
//print out “hello” in the terminal

curl http:// ip.port
curl https://www.gnu.org/gnu/gnu.html
//is a command line tool that enables data transfer over various network protocols


