.. _mmctl_system_getbusy:

mmctl system getbusy
--------------------

Get the current busy state

Synopsis
~~~~~~~~


Gets the server busy state (high load) and timestamp corresponding to when the server busy flag will be automatically cleared.

::

  mmctl system getbusy [flags]

Examples
~~~~~~~~

::

    system getbusy

Options
~~~~~~~

::

  -h, --help   help for getbusy

Options inherited from parent commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

::

      --config string                path to the configuration file (default "$XDG_CONFIG_HOME/mmctl/config")
      --insecure-sha1-intermediate   allows to use insecure TLS protocols, such as SHA-1
      --insecure-tls-version         allows to use TLS versions 1.0 and 1.1
      --json                         the output format will be in json format
      --local                        allows communicating with the server through a unix socket
      --quiet                        prevent mmctl to generate output for the commands
      --strict                       will only run commands if the mmctl version matches the server one
      --suppress-warnings            disables printing warning messages

SEE ALSO
~~~~~~~~

* `mmctl system <mmctl_system.rst>`_ 	 - System management

