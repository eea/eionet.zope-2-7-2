Zope 2.7.2 installation
========================

The installation expects the Zope instance to be located in /var/local/website
in the container namespace.

In the zope.conf set the port of the embedded HTTP service to 8080.
```
<http-server>
  # valid keys are "address" and "force-connection-close"
  address 8080
  # force-connection-close on
</http-server>
```
