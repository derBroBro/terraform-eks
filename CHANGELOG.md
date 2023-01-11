## [2.1.3]

FEATURE:
* Add EBS CSI EKS add-on, this is necessary for clusters with a version >= 1.23

## [2.1.2]

Make CoreDNS optional

## [2.1.1]

Hotfix: Remove AWS Provider.

## [2.1.0]

ENHANCEMENTS:
* Upgraded terraform version to 0.15
[#11](https://generic/tf-modules/tf-mod-aws-eks/-/issues/11)

BACKWARDS INCOMPATIBILITIES / NOTES:
* Terraform version 0.15.x

## [2.0.2]

FEATURE:   
* Change cluster-addon resolve_conflicts to "NONE"

## [2.0.1]

FEATURE:
* Variables for spot instance scaling

## [2.0.0]

ENHANCEMENTS:
* Upgraded terraform version to 0.14
[#9](https://generic/tf-modules/tf-mod-aws-eks/-/issues/9)

## [1.0.7]

FEATURE:   
* Update documentation and Changelog

## [1.0.6]

FEATURE:   
* Make IAM resources optional

## [1.0.5]

FEATURE:   
* Add Terraform Managed AddOns

## [1.0.4]

FEATURE:   
* Add support for service IPs

## [1.0.2]

FEATURE:
* Added support for aws-auth configmap management.(Please see README for more important information)

## [1.0.1]

FEATURE:
* Allow passing userdata to the launch template

## [1.0.0]

ENHANCEMENTS:
* Upgraded terraform version to 0.13

## [0.2.2]

ENHANCEMENTS:
* Added support for spot instance node group.

## [0.2.1]

ENHANCEMENTS:
* Added support for tags on nodes using a launch template.

## [0.2.0] - 2021-02-12

ENHANCEMENTS:
* Updated README.md
* Added versions.tf

BACKWARDS INCOMPATIBILITIES / NOTES:
* Terraform version 0.12.x

## [0.1.0] - 2020-09-21

### Added

- Initial version.
