Troubleshooting
===============

* Unable to install **pycurl** library, getting **main.ConfigurationError: Could not run curl-config**?

    Luckily, we have faced this issue. If you ran the install script and still got this error, you can let us know. If not,
    check `this issue <https://github.com/owtf/owtf/issues/330>`_ on how to fix it.

* Unable to run OWTF because of **ImportError: No module named cryptography.hazmat.bindings.openssl.binding**?

    This actually means you donot have cryptography python module installed. It is recommended to rerun the install script (or)
    to just install missing python libraries use the following command.

    .. code-block:: bash

        pip2 install --upgrade -r install/owtf.pip
