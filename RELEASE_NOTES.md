<!---
This file is reset every time a new release is done. The contents of this file are for the currently unreleased version.

Example Note:

## Example Heading
Details about the thing that changed that needs to get included in the Release Notes in markdown.
-->

# knife-azure 1.8.0 release notes:
In this release `--chef-service-interval` option is renamed to `chef-daemon-interval`. Updated code to work with latest azure-sdk gems i.e. version 0.9.0.

New options introduced

`--daemon`, which lets user to select options to run chef-client as auto, service or scheduled task. This option works for windows node and --bootstrap-protocol to be 'cloud-api'.

Please file bugs or feature requests against the [KNIFE_AZURE](https://github.com/chef/knife-azure/issues) repository.
More information on the contribution process for Chef projects can be found in the [Chef Contributions document](https://docs.chef.io/community_contributions.html).

## knife-azure on RubyGems and Github
https://rubygems.org/gems/knife-azure

https://github.com/chef/knife-azure

## Features added in this release:

See the [1.8.0 CHANGELOG](https://github.com/chef/knife-azure/blob/1.8.0/CHANGELOG.md) for the complete list of features added in this release.

Here is a partial list:

* Added --daemon option for chef extension. [\#417](https://github.com/chef/knife-azure/pull/417) ([Vasu1105](https://github.com/Vasu1105))

## Issues fixed in this release:

See the [1.8.0 CHANGELOG](https://github.com/chef/knife-azure/blob/1.8.0/CHANGELOG.md) for the complete list of issues fixed in this release.

Here is a partial list:

* Fix for azurerm command bootstrap was not happening fully [\#447](https://github.com/chef/knife-azure/pull/447) ([harikesh-kolekar](https://github.com/harikesh-kolekar))
* Fix for --node-ssl-verify-mode none' does not write appropriate value to resulting client.rb [\#437](https://github.com/chef/knife-azure/pull/437) ([piyushawasthi](https://github.com/piyushawasthi))
* Updated azure-sdk to work with latest version [\#425](https://github.com/chef/knife-azure/pull/425)([dheerajd-msys](https://github.com/dheerajd-msys))