# Blog Post 1
------------

##Thus far...
-----------

Initially, this blog post was going to be intended for the open-source
forked repository of ipython/ipython.

This almost happened.

The reason that I am now posting this to this jupyter/notebook forked repo
is mainly due to events that have occured with the ipython project somewhat 
recently known as "the big split". There is documentation already available,
however, it had thus led me along to try in contribute to a Javascript-ed
project rather than python (which is primarily why I picked it in the first 
place but c'est la vie and I will try to stay sharp with it in another project
in the future).

###ARTIFACT#1
----------
An artifact that I would've liked to contribute to initially would have been 
limited to that of simply installing ipython onto the 2014 CS50(Ubuntu) VM, but
this does carry over into intalling the jupyter notebook with that of what was 
directly from the forked repo:

First and foremost, make sure that the CS50 2014 is up-to-date (this takes a while)

```
update50
```

next, update those recently downloaded/ outdated files

```
sudo apt-get install
```

(go drink more coffee) finally to get into the meat and bones of it all
IMPORTANT NOTE: this installs *npm*, *python* (v.2.7, and 3.4), *pip*
and a couple of other things that you will probably need later on. More
emphasis on the node.js stuff though since this project was clearly 
heading this direction

you may also need to plain get the nodejs-legacy version which would
also fix a ton of problems too with 
```
sudo apt-get install nodejs-legacy
```

and from there, simply go straight throught the already provided 
install instructions from the forked repo

```
sudo apt-get install nodejs-legacy npm python-virtualenv python-dev
# ensure setuptools/pip are up-to-date
pip install --upgrade setuptools pip
git clone https://github.com/jupyter/notebook.git
cd notebook
pip install --pre -e .
```

go drink more coffee.....

with a ...
```
jupyter notebook
```
....to run


###ARTIFACT#2
------

UPDATE!: This is now labelled as a question in the jupyter/notebook issue
          #1217
For my second artifact for this blog post I decided on testing the water
with the notebook and a feature that always annoyed me with text areas
(like this one) is the absence of a line character count. 

I try to keep consistant with coding discipline but every now and then I slip 
up and go over and it irks me to tweak stuff like this later on. I sent an
open issue to the upstream repo and am awaiting ~~to be shot down~~ a response 
from them on this minimal issue. (Yes I am minimal in general)

If received well, it would be a nice thing to try and install on the notebook,
aside from the fact that I've never actually done such collaborative coding.

I'm also thinking of maybe playing around with the notebook a bit more and adding
so of my old chemistry calibration data to plot a curve. I'll see to some of the
results in the next blog post.

Also, on the matter of jupyter itself, it is a language "agnostic" conglomeration.
This means that you don't have to solely know python to get things going ---but
I will stick to it anyway when testing out the page (I have not touched the language
since last summer and I am getting ansy with it)..
