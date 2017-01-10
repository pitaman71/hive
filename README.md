# hive

- [ ] Distributed Recipes: explicit ssh prefix
    - [x] hive_cli: list command
    - [x] hive_cli: plan command
    - [x] hive_cli: execute command
    - [x] hive_cli: expression interpretation
    - [x] hive_cli: shell interface
    - [ ] UC Tested
    - [ ] UC Documented
- [ ] Distributed Recipes: dynamically provisioning EC2 instances
- [ ] Distributed Recipes: direct and indirect recipes
    - [ ] hive_daemon: factor shared code out of hive_cli
    - [ ] goal.pursue should automatically select local or remote recipe
    - [ ] start remote hive daemon
    - [ ] transmit goal to remote hive daemon
    - [ ] monitor goal progress on remote hive daemon
    - [ ] receive final outcome of remote hive daemon
- [ ] Emulating POSIX make with Hive
- [ ] Emulating Jenkins with Hive
- [ ] Forward Path: Resumable Exception Goals
- [ ] Production Delivery modes
    - [x] hive_daemon: delivery to POSIX host via scp
    - [x] hive_daemon: delivery to POSIX host via rpm package + yum
