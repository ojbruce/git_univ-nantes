Git Univ-Nantes
===============

> A simple way to access GitHub repositories

Connect to bastion (ssh):

```$ ssh -f -N -L:9418:github.com:9418 <e+n°etu>@bastion.etu.univ-nantes.fr```

Go to your wanted repository:

```$ cd <wanted-repository>```

Clone:

```$ git clone git://localhost/ojbruce/BDD_project.git```

Push:

```$ git push -v https://github.com/ojbruce/BDD_project.git``` 

```This command also works without bastion (just for pushing), but be carefull to correctly setup the proxy (git config http.proxy)```


Pull:

```$ git pull -v git://localhost/ojbruce/BDD_project.git```

Disconnect from bastion (kill the process) :

```$kill -9 <processus ssh>```
