# Bloc Notes

## ToC

- [Bloc Notes](#bloc-notes)
  - [ToC](#toc)
  - [Name space](#name-space)

## Name space

Name | Content | Admin cluster | Sysops | Devs | Client | Users | Cpu | RAM | Replica | Priority
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ---
development | WordPress & DB | :white_check_mark: | :white_check_mark: | :white_check_mark: | :x: | :x: | 2 | 4Gi | 1 | Ok
staging | WordPress & DB | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :x: | 2 | 4Gi | 1 | Ok
production | WordPress & DB | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | 4 | 8Gi | 3 | Critique
monitoring | Prometheus & Grafana | :white_check_mark: | :white_check_mark: | :x: | :x: | :x: | 4 | 8Gi | 3 | Critique
registry | DockerRegitry | :white_check_mark: | :white_check_mark: | :x: | :x: | :x: | 1 | 1Gi | 2 | Critique 