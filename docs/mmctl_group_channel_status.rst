.. _mmctl_group_channel_status:

mmctl group channel status
--------------------------

Show's the group constrain status for the specified channel

Synopsis
~~~~~~~~


Show's the group constrain status for the specified channel

::

  mmctl group channel status [team]:[channel] [flags]

Examples
~~~~~~~~

::

    group channel status myteam:mychannel

Options
~~~~~~~

::

  -h, --help   help for status

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

* `mmctl group channel <mmctl_group_channel.rst>`_ 	 - Management of channel groups

