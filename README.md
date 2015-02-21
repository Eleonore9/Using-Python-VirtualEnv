Hooray for Python Virtualenvs!
=========

Virtualenvs are for all kind of projects!
-----

Virtual environments are super useful!
I remember being taught to us them for web projects
so I could use different versions of different
frameworks for different projects for example.

While starting a data science project recently
I was glad to realise that virtual envs are used
for any find of Python projects!
I also picked up virtualenvwrapper which makes it
much easier to interact with virtualenv.
I know, I was skeptical too before as virtualenv is not
hard to use. But I tried virtualenvwrapper and
I'm not going back!


What's it all about? 
----

If you wonder what virtualenv is and whether you need to use it for
your Python projects there are several docs and blog post.
Here's a link to [The Hitchhiker's guide to Python](http://docs.python-guide.org/en/latest/dev/virtualenvs/) and an [intro to pip and virtualenv](http://www.dabapps.com/blog/introduction-to-pip-and-virtualenv-python/).


Installing virtualenv & virtualenvwrapper.
-----
I started installing both packages using pip:
```
pip install virtualenv
pip install virtualenvwrapper
```
And then I found a [nice blog post] () that helped
me configure and use them!

My .bashrc file now looks like that:
![My .bashrc file](https://raw.github.com/eleonore9/using-python-virtualenv/master/img/bashrc_virtenvs.png)
I created ~/virtenvs/ and ~/Projects-Active/ directories
and applied the changes with ```source ~/.bashrc```.