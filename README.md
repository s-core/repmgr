repmgr: Replication Manager for PostgreSQL
==========================================

`repmgr` is a suite of open-source tools to manage replication and failover
within a cluster of PostgreSQL servers. It enhances PostgreSQL's built-in
replication capabilities with utilities to set up standby servers, monitor
replication, and perform administrative tasks such as failover or switchover
operations.

PostgreSQL 12, 11, 10, 9.6 and 9.5 are fully supported.
PostgreSQL 9.4 and 9.3 are supported, with some restrictions.

`repmgr` is distributed under the GNU GPL 3 and maintained by 2ndQuadrant.

Documentation
-------------

The full `repmgr` documentation is available here:

> [repmgr documentation](https://repmgr.org/docs/current/index.html)

The old `README` file for `repmgr` 3.x is available here:

> https://github.com/2ndQuadrant/repmgr/blob/REL3_3_STABLE/README.md

Note that the `repmgr` 3.x series is no longer supported and contains known bugs;
please upgrade to the current `repmgr` version as soon as possible.

Versions
--------

For an overview of `repmgr` versions and PostgreSQL compatibility, see the
[repmgr compatibility matrix](https://repmgr.org/docs/current/install-requirements.html#INSTALL-COMPATIBILITY-MATRIX).

Files
------

 - `CONTRIBUTING.md`: details on how to contribute to `repmgr`
 - `COPYRIGHT`: Copyright information
 - `HISTORY`: Summary of changes in each `repmgr` release
 - `LICENSE`: GNU GPL3 details


Directories
-----------

 - `contrib/`: additional utilities
 - `doc/`: DocBook-based documentation files
 - `expected/`: expected regression test output
 - `scripts/`: example scripts
 - `sql/`: regression test input


Support and Assistance
----------------------

2ndQuadrant provides 24x7 production support for `repmgr`, including
configuration assistance, installation verification and training for
running a robust replication cluster. For further details see:

* https://2ndquadrant.com/en/support/

There is a mailing list/forum to discuss contributions or issues:

* https://groups.google.com/group/repmgr

The IRC channel #repmgr is registered with freenode.

Please report bugs and other issues to:

* https://github.com/2ndQuadrant/repmgr

See 

Further information is available at https://repmgr.org/

We'd love to hear from you about how you use repmgr. Case studies and
news are always welcome. Send us an email at info@2ndQuadrant.com, or
send a postcard to

    repmgr
    c/o 2ndQuadrant
    7200 The Quorum
    Oxford Business Park North
    Oxford
    OX4 2JZ
    United Kingdom

Thanks from the repmgr core team.

* Ian Barwick
* Jaime Casanova
* Abhijit Menon-Sen
* Simon Riggs
* Cedric Villemain

Further reading
---------------

* [repmgr documentation](https://repmgr.org/docs/current/index.html)
* https://blog.2ndquadrant.com/repmgr-3-2-is-here-barman-support-brand-new-high-availability-features/
* https://blog.2ndquadrant.com/improvements-in-repmgr-3-1-4/
* https://blog.2ndquadrant.com/managing-useful-clusters-repmgr/
* https://blog.2ndquadrant.com/easier_postgresql_90_clusters/
