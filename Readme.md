## Instalar Compat-wireless-2010-07-26


Revisar donde se almacena el archivo:
```sh
$ cd Download
$ ls
```

* Ingresar como super usuario:

```sh
$ sudo su 
$ tar -xf compat-wireless-2010-07-26.tar.bz2
```

```sh
$ cd compat-wireless-2010-07-26
$ make unload
$ make load
$ ifconfig
$ wconfig
```

***Si todo esto no funciona, intenta revisar los proxys de tu navegador***

