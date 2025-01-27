.. _mmctl_channel_search:

mmctl channel search
--------------------

Search a channel

Synopsis
~~~~~~~~


Search a channel by channel name.
Channel can be specified by team. ie. --team myteam mychannel or by team ID.

::

  mmctl channel search [channel]
  mmctl search --team [team] [channel] [flags]

Examples
~~~~~~~~

::

    channel search mychannel
    channel search --team myteam mychannel

Options
~~~~~~~

::

  -h, --help          help for search
      --team string   Team name or ID

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

* `mmctl channel <mmctl_channel.rst>`_ 	 - Management of channels

