# Apache Http Server for SPAship
![Docker Cloud Automated build](https://img.shields.io/docker/cloud/automated/spaship/httpd)
![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/spaship/httpd)

This a runtime image for SPAship apps

## Usage

### Docker Pull

```
docker pull spaship/httpd
```

### OpenShift 
```
oc import-image spaship/httpd --from=spaship/httpd --confirm
```

### Base Image

#### Red Hat Universal Base Image (UBI)

https://www.redhat.com/en/blog/introducing-red-hat-universal-base-image

### Server Side Includes (SSI)

#### Apache httpd SSI
https://httpd.apache.org/docs/2.4/howto/ssi.html


## License

[MIT licensed](./LICENSE).
