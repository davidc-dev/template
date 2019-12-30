============
Installation
============

Install the package with pip::

    $ pip install read-the-docs-template
    
.. code-block:: yaml
    apiVersion: extensions/v1beta1
    kind: Ingress
    metadata:
      annotations:
        nginx.ingress.kubernetes.io/rewrite-target: /
      name: plat-ingress
      namespace: plat-system
