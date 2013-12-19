learnGit
========

following tutorial: http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1#awesm=~opzx0XktDVGJmx

my prev git learning stuff is gone, feeling so frustrated!!!

20131219
--------
how to pull a specific version of git code (with SHA)?

1. clone current master copy from github into a directory, named as the specific version you want to revert to:

git clone git://github.com/redpony/cdec.git bbe13be2591301d52475d270cc74ea560763c595

2. cd to the dir, then do a checkout to revert to the desired version:

cd bbe13be2591301d52475d270cc74ea560763c595/

git checkout bbe13be2591301d52475d270cc74ea560763c595
