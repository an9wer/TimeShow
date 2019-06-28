Puppet3.8
=========

Puppet is **declarative**, **idempotent**, and **stateless** by default.

Installation
------------

Install puppet3.8 on CentOS7:

::

    # rpm -ivh https://yum.puppetlabs.com/puppetlabs-release-el-7.noarch.rpm
    # yum install puppet

https://puppet.com/docs/puppet/3.8/install_el.html

Subcommands
-----------

Module
""""""

Install a module:

::

    # puppet module install <module>

Install a specified version of module:

::

    # puppet module install -v <version> <module>

Resource
--------

Exec
----

refreshonly
    When this attribute is set to *true*, the command should only be run when
    it is triggered by some resource it subscribes (by using *subscribe* or
    *notify* attribute, not *require* or *before*).

    ::

        exec { "some command":
            refreshonly => only,
            require => File['some file'],
        }

    In this example, whether the required *file* resource is run, the *exec*
    resource will never be triggered.



