
Installation
============

Installation of Rockstor is a short and straight forward process. For all types
of installations, see :ref:`quickstartguide` to get started.

Hardware recommendations:
-------------------------

At the bare minimum, see :ref:`minsysreqs` for a basic recommendation. This
translates to most commodity servers with more than a couple of disk
drives. Based on your cost constraints and performances requirements, several
hardware configurations are possible as described below.

Home NAS
^^^^^^^^
Coming soon...

Small office NAS
^^^^^^^^^^^^^^^^
Coming soon...

All Flash NAS
^^^^^^^^^^^^^
Coming soon...


Initial setup
-------------

Rockstor needs to be setup initially using the WebUI. Once the installation is
complete, go to https://<appliance_ip> using the Firefox browser.

1. cert download screenshot

2. initial setup screens screenshot

3. dashboard screenshot

Upgrading Rockstor
------------------

Rockstor is under heavy development. However, we strive to make most updates
non-disruptive. You can safely update Rockstor anytime with the following
command::

    [root@localhost ~]# yum update rockstor

If an update is disruptive, the update process prompts for user action and
provides necessary information to choose to update or not. You can safely
decide not to update if that makes sense for your environment.


Installation in a virtual environment
-------------------------------------

coming soon...

Quick evaluation
------------------

Before proceeding with a serious installation that may require hardware
procurement, you can evaluate Rockstor on Amazon AWS. `Here
<https://www.youtube.com/watch?v=ys_8FLVov2U>`_ is a short video on how to get
started.