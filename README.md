Symfony Demo for Mager Deploy
===

Init local environment first in order to use dev preview

```shell
mager init --local
mager prepare local
```

To preview deployment on local, `mager.yaml` configuration will be override by `mager.dev.yaml`

```shell
mager dev
```

To deploy on remote server, you have to add new namespace

```shell
mager namespace:add prod
mager prepare prod
```

Lastly you can deploy app to specified namespace
````shell
mager deploy prod
````