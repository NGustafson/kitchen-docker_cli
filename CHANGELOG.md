## 0.19.0

* Pull request [#43][]: Add pre_create_command to driver ([@ysgard][])
* Pull request [#42][] [#44][]: Quote environments value to support spaces ([@ahelal][])
* Pull request [#41][]: Add `build_pull` opt to pull the latest docker image ([@s-bernard][])
* Pull request [#38][]: Never force tty when opening transport ([@bdellegrazie][])

## 0.18.0

* Pull request [#33][]: Strengthen destroy ([@s-bernard][])
* Pull request [#33][]: Add `destroy_container_name` option ([@s-bernard][])

## 0.17.0

* Pull request [#32][]: Add ability to configure security options ([@fphilippon][])

## 0.16.0

* Pull request [#31][]: Add instance_container_name option ([@s-bernard][])

## 0.15.1

* Pull request [#30][]: Fix [#29][]: use docker cp to upload files ([@s-bernard][])

## 0.15.0

* Add `skip_preparation` option

## 0.14.2

* Fix error on Circle CI

## 0.14.1

* Pull request [#23][]: Add `build_context` option to pass Docker build context ([@nrvale0][])

## 0.14.0

* Pull request [#21][]: Support `--add-host` option ([@sawanoboly][])

## 0.13.1

- Fix output of `destroy` action in the case of the container does not exist.

## 0.13.0

* Support Docker LXC driver(for CircleCI)

## 0.12.1

* Fix error on `kitchen-ansible` with extra_vars [#18][]

## 0.12.0

* Pull request [#17][]: Add `dns` option ([@yewton][])

## 0.11.2

* Bugfix [#16][]

## 0.11.1

* `kitchen-ansible` support

## 0.11.0

* Add `expose` option

## 0.10.0

* Add `volumes_from` option

## 0.9.1

* Bugfix

## 0.9.0

* Change custom Dockerfile to ERB template [#11][] [#12][]

## 0.8.1

* Support test-kitchen `1.4.0`

## 0.8.0

* Add `instance_host_name` option

## 0.7.1

* Fix error on `fedora`

## 0.7.0

* Add `hostname` option

## 0.6.0

* Pull request [#4][]: allow setup environment variables(add environment option) ([@hd-deman][])
* Add `network` option

## 0.5.0

* Add `memory_limit` option
* Add `cpu_shares` option

## 0.4.0

* Pull request [#2][]: Add custom `Dockerfile` support ([@grubernaut][])

## 0.3.1

* Change dependency version of `test-kitchen`

## 0.3.0

* Use docker exec command to transfer the test-kitchen's sandbox

## 0.2.0.beta

* Add `privileged` option

## 0.1.1.alpha

* Change `no_cache` option's default value to `false`

## 0.1.0.alpha

* Initial release

<!--- The following link definition list is generated by PimpMyChangelog --->
[#2]: https://github.com/marcy-terui/kitchen-docker_cli/issues/2
[#4]: https://github.com/marcy-terui/kitchen-docker_cli/issues/4
[#11]: https://github.com/marcy-terui/kitchen-docker_cli/issues/11
[#12]: https://github.com/marcy-terui/kitchen-docker_cli/issues/12
[#16]: https://github.com/marcy-terui/kitchen-docker_cli/issues/16
[#17]: https://github.com/marcy-terui/kitchen-docker_cli/issues/17
[#18]: https://github.com/marcy-terui/kitchen-docker_cli/issues/18
[#21]: https://github.com/marcy-terui/kitchen-docker_cli/issues/21
[#23]: https://github.com/marcy-terui/kitchen-docker_cli/issues/23
[#29]: https://github.com/marcy-terui/kitchen-docker_cli/issues/29
[#30]: https://github.com/marcy-terui/kitchen-docker_cli/issues/30
[#31]: https://github.com/marcy-terui/kitchen-docker_cli/issues/31
[#32]: https://github.com/marcy-terui/kitchen-docker_cli/issues/32
[#33]: https://github.com/marcy-terui/kitchen-docker_cli/issues/33
[#38]: https://github.com/marcy-terui/kitchen-docker_cli/issues/38
[#41]: https://github.com/marcy-terui/kitchen-docker_cli/issues/41
[#42]: https://github.com/marcy-terui/kitchen-docker_cli/issues/42
[#43]: https://github.com/marcy-terui/kitchen-docker_cli/issues/43
[#44]: https://github.com/marcy-terui/kitchen-docker_cli/issues/44
[@ahelal]: https://github.com/ahelal
[@bdellegrazie]: https://github.com/bdellegrazie
[@fphilippon]: https://github.com/fphilippon
[@grubernaut]: https://github.com/grubernaut
[@hd-deman]: https://github.com/hd-deman
[@nrvale0]: https://github.com/nrvale0
[@s-bernard]: https://github.com/s-bernard
[@sawanoboly]: https://github.com/sawanoboly
[@yewton]: https://github.com/yewton
[@ysgard]: https://github.com/ysgard