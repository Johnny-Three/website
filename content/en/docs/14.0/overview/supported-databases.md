---
title: Supported Databases  
weight: 2
featured: true
---

Vitess deploys, scales and manages clusters of open-source SQL database instances. Currently, Vitess supports the [MySQL](https://www.mysql.com/), [Percona Server for MySQL](https://www.percona.com/software/mysql-database/percona-server), and to a limited extent [MariaDB](https://mariadb.org) databases.

The [VTGate](../../concepts/vtgate/) proxy server advertises its version as MySQL 5.7.

## MySQL versions 5.7 to 8.0

Vitess supports the core features of MySQL versions 5.7 to 8.0, with [some limitations](../../reference/compatibility/mysql-compatibility/). Vitess also supports [Percona Server for MySQL](https://www.percona.com/software/mysql-database/percona-server) versions 5.7 to 8.0.

{{< info >}}For new Vitess installations, MySQL or Percona Server for MySQL version 8 are recommended.{{< /info >}}

## MariaDB versions 10.0 to 10.3

Vitess supports the core features of MariaDB versions 10.0 to 10.3. Vitess [does not yet](https://github.com/vitessio/vitess/issues/5362) support later versions of MariaDB.

{{< warning >}}MariaDB support is likely to end in the the future. You can view and comment on [the relevant proposal here](https://github.com/vitessio/vitess/issues/9518).{{< /warning >}}

## See also

+ [MySQL Compatibility](../../reference/compatibility/mysql-compatibility/)
