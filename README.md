# aci-caddy-php

This repo includes the acibuild scripts that are needed to build an ACI image that includes Caddy and php.

Before you build this aci, you should update the environment variables in the `environment` file accordingly.

To build this aci and sign it with pgp execute the following commands (the .aci file will be compiled to your $BUILDDIR which defaults to /bin)

```sh
$ sudo ./build-aci && ./sign-aci
```
