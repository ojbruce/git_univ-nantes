Git Univ-Nantes
===============

> A simple way to access GitHub repositories inside the University of Nantes

Connect to bastion (SSH)
------------------------

```$ ssh -f -N -L:9418:github.com:9418 <e+n°etu>@bastion.etu.univ-nantes.fr```

Clone
-----

```$ git clone git://localhost/ojbruce/BDD_project.git```

Push
----

```$ git push -v https://github.com/ojbruce/BDD_project.git``` 

_This command also works without bastion (just for pushing), but be carefull to correctly setup the proxy (git config http.proxy)_


Pull
----

```$ git pull -v git://localhost/ojbruce/BDD_project.git```

Disconnect from bastion
-----------------------

You have to kill the SSH process

```$kill -9 <processus SSH>```

**Enjoy :octocat: !**
