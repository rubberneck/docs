.. _dev-setup:

Developer Machine Setup
=======================

Setup your developer machine for building and testing the Mattermost server and web client. You can choose to not install the Docker container but you must use it for developing and contributing to Mattermost. The container has an Inbucket email server and both MySQL and PostgreSQL databases, all of which are required for running unit tests.

If you don't plan on contributing code to the Mattermost open source project, then you don't need to install Docker. If you're not installing Docker, you can safely skip the Docker installation parts of the setup instructions. However, the ``make run`` and ``make test`` commands won't work.

Moreover, come `join our "Contributors" community channel <https://pre-release.mattermost.com/core/channels/tickets>`_ on our daily build server, where you can discuss questions with community members and the Mattermost core team. Join our `"Developers" channel <https://pre-release.mattermost.com/core/channels/developers>`_ for technical discussions and our `"Integrations" channel <https://pre-release.mattermost.com/core/channels/integrations>`_ for all integrations and plugins discussions.

  .. toctree::

    Setting up Ubuntu 16.04 <dev-setup-ubuntu-1604.rst>
    Setting up CentOS 7 <dev-setup-centos-7.rst>
    Setting up macOS <dev-setup-osx.rst>
    Setting up Archlinux <dev-setup-archlinux.rst>
    Setting up Windows <dev-setup-windows.rst>
    dev-setup-compiling.rst
    dev-setup-troubleshooting.rst
