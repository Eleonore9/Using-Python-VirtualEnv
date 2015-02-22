Hooray for virtualenv! \\|^-^|/
=========

virtualenv suits all kinds of projects!
-----

Virtual environments are super useful!

When learning Python I remember being taught to
use virtualenv for web projects. This way I could
use different versions of the same framework/tool/library
in different projects on the same computer.

While starting a data science project recently
I was glad to see virtual envs are widely used
for any kind of Python projects!

I also picked up virtualenvwrapper which makes it
much easier to interact with virtualenv.
I know, I was skeptical too as virtualenv is not
hard to use. But I tried virtualenvwrapper and
I'm not going back!


What is it all about? 
----

If you wonder what virtualenv is and whether you need to use it for
your Python projects there are several docs and blog posts on the web.

Here's a link to [The Hitchhiker's guide to Python](http://docs.python-guide.org/en/latest/dev/virtualenvs/) and an [intro to pip and virtualenv](http://www.dabapps.com/blog/introduction-to-pip-and-virtualenv-python/).


Installing virtualenv & virtualenvwrapper.
-----
I started installing both packages using pip:
```
pip install virtualenv
pip install virtualenvwrapper
```
And then I found a [nice blog post] (http://chrisstrelioff.ws/sandbox/2014/09/04/virtualenv_and_virtualenvwrapper_on_ubuntu_14_04.html) that helped
me configure and use them!

*Note: this post targets Ubuntu 14.04 users.*

My .bashrc file now looks like that:

![My .bashrc file](https://raw.github.com/eleonore9/using-python-virtualenv/master/img/bashrc_virtenvs.png)

I created ~/virtenvs/ and ~/Projects-Active/ directories
and applied the changes with ```source ~/.bashrc```.

Useful virtualenvwrapper commands:
------

For most of what you'll need to do, those few
commands are enough:

* **mkvirtualenv env_name** -> creates the virtualenv env_name
* **workon** -> lists all the virtualenvs created
* **pip list** -> lists of packages installed
* **deactivate** -> leaves a virtualenv
* **workon env_name** -> switches to env_name virtualenv
* **rmvirtualenv env_name** -> deletes the virtualenv