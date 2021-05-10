# How to Build Docker R with Prophet Package inside example


Example of how to build a docker container with Prophet package. There wasn't too obivous how to add it to make sure it runs with all the dependencies

# Points of Contact

Alexey Butirev, Ken

# How to install

```{bash}
 git clone git@gitlab.eng.roku.com:abutyrev/dockerrprophet.git
 cd dockerrprophet
 docker build -t rprophet .
```

# How to run

```{bash}
  docker run -ti --rm rprophet
```
