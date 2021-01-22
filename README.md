# Ansible role `Drupal`

An Ansible role for Drupal. Specifically, the responsibilities of this role are to:

- Download and extract Drupal.

## Requirements

No specific requirements

## Role Variables


| Variable   | Default | Comments (type)  |
| :---       | :---    | :---             |
| `drupal_version` | drupal-8.8.6 | Specify the drupal version to download. Must be in format `drupal-x.y.z` |
| `drupal_install_path` | /home  | Directory to install Drupal in. |

## Dependencies

No dependencies.

## Contributors

- [Werner De Schryver](https://github.com/Wernerdeschryver/) (maintainer)

