This uses [mapnik-packaging](https://github.com/CartoDB/mapnik-packaging) to download, compile and package all dependencies requited to package the mapnik sdk.

# How to package and publish the mapnik sdk

```sh
vagrant up
vagrant ssh
cd /vagrant

source ./scripts/provision
cd /vagrant
./scripts/package
```

# Publish
Publishing the SDK to AWS S3 has to be documented yet.
