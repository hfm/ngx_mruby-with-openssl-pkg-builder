# ngx_mruby-with-openssl-pkg-builder

It builds the package of ngx_mruby with static-linked openssl using Docker. It's based on [hsbt/ngx_mruby-package-builder](https://github.com/hsbt/ngx_mruby-package-builder).

Run the following commands:

```console
# build RPMs
$ docker-compose build centos7
$ docker-compose run centos7
```
