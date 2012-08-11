# add time point

Sean Soong suggested he wanted to get the point he want quickly
I want a minified version of Asciicasts, not show noting
so how are sth like this

  1. give a brief intro 00:00
     ...
  2. talk about feature 1 05:00
     ...
  3. talk about seconde feature 07:22
     ...


# Do not try to repeat some tech terms to stress on sth, try to make it
cleared expressed.
DONT:
  - "this is important, this is important"
  - "this is very important"
  - "Note here we need to get a filename, not pathname, not pathname"
  - no need to repeat "not pathname"
  - "later, after some time"
  - this is just brain damaged
  - things like "prompt" "compile" should be in Chinese
 
try to pronunce each word clearly, try to use more formal lanaugage,
# railscasts also tech basics A LOT
check intro to sass asset-pipeline and so on, good inspiration 
# real code first

if I want to show some detail to people, I do not go to repeat the book
concept over and over again, instead I will show people working code(try to
make the code example simple, but it should not be just concept code, it
should be code that get some real work done, so that it will make more sense
to people)

# make a new casts out of this
http://limingth.github.com/ # the git big pic
http://blog.sanctum.geek.nz/vim-anti-patterns/
# setup happycasts machine in virtuabox with ubuntu1104
now sth to install
    
    git tig vim openssh-server ctags curl apache2

first disable Unity, by logout and choose "gnome classic". theninstall
vm-addon.

right-click the top panel, choose auto-hide, to save space for firefox(not
avaiable on 1110)
then go to firefox, hide menubar.

### screencasts spec

have a  ubuntu gnome-terminal profile named "happycasts", use "black on white", "font: monospace 17", set this profile as defualt.

then have a command "gohappycasts"

    gnome-terminal --full-screen --hide-menubar

fullscreen the vm, that will make my later work in screenflow to make the video 1024x768, a lot easier.

Turn keycastr background color to "Teal"(looks like the blackboard), it is more comfortable to look, and clearer.

make it 10 mins, try to show people as much as I can, lead them step by step towards getting the job done.
10 mins means the audience's time is cherished, and 10mins means not too much works for myself, so limit does bring goodies.

termial -> edit profile -> disable scrollbar


# how to resize a Virtualbox .vdi disk
 http://www.my-guides.net/en/content/view/122/26/
# vm install ubuntu 
what is true love to newbies is teaching them to have a VMware ubuntu

http://www.danscourses.com/Linux-Fundamentals/installing-ubuntu-1110.html

# happycasts
a gdb happycast will make gdb so friendly and lovely to newbies
    
    we only show you the most useful tips
    we do not just tell, we show you how to use it
    we explain a bit about whatever confused ourselves while we were tyring to
    use it
    
so happycasts is some sugure.
it is sweet, it is lovely, it does not scare you away but showing you tons of
advanced fetures of softwareX. Instead, it just gives you the most useful and
tips you will be most interested about softwareX. After finishing one cast,
you will say, he this software will be useful, and it is not difficult to
learn at the same time.

# my youku frontpage
I need sth like guodegang

    http://i.youku.com/u/id_UMTg1NTYwOTI4.html

# ssh key
I cp my .ssh to my VM, but I can not use it. so I add a new ssh-key, but
failed to add it to github, then I tried `ssh-keygen -t dsa`, this time it
works.

now I adduser kk on my VM, so I can cp the dsa key I generated for peter and
use it. all I needed was 

    "chown kk:kk .ssh/*"


# microphone
the side with buttons are the back of it!!!

xptemplate is more powerful than sinpmate, as they say
http://www.casparant.com/posts/how-to-update-your-git-patches.html

# mouse on the screen
if the mouse positions are differnet on two adjacent clips, it is ugly.
the fix is simple, click on the vm screen once, then move the mouse out of vm
screen. the terminal will just work, and firefox will just work, when you move
the mouse in, you don't need to click again.

# do not cut one screenshot into two clips
