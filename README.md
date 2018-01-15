# Kibana without xpack

When xpack is disabled by environment variables the plugins are optimized.
The optimization takes quite some time and are not suitable for HA clusters like kubernetes.

In this image the xpack plugin has been removed, any xpack configuration removed from configuration and all plugins has been pre-optimized for fast startup.

View the container at https://hub.docker.com/r/mskjeret/kibana-without-xpack/

Install the container using:
```script
docker pull mskjeret/kibana-without-xpack
```
