## Texas Advanced Computing Center
# Django CMS Plugin: "System Specs"

This plugin renders structured data about a TACC system.

- __`__plugin_name__`__: `taccsite_system_specs`
- __`__PluginName__`__: `TaccsiteSystemSpecs`
- __"Plugin Name"__: "System Specs"

## For Plugin Developer

After cloning this repository for your plugin:

1. Follow https://github.com/tacc-wbomar/Core-CMS-Plugin/wiki/Core-CMS-Plugin-Development-Quick-Start.
2. Remove this section from your repository's `README.md`.


## Quick Start

1. Follow https://github.com/tacc-wbomar/Core-CMS-Plugin/wiki/Core-CMS-Plugin-Usage-Quick-Start.

## Usage

1. Add instance of plugin to a page.
1. Configure the plugin instance.
1. (Optional) Add and nest plugin instances to support extra content.
1. See plugin render content that matches configuration (and nested plugin instances).

[dcms-picture]: https://github.com/django-cms/djangocms-picture
[tacc-dlist]: https://github.com/tacc-wbomar/Core-CMS-Plugin-Data-List
[tacc-sysmon]: https://github.com/tacc-wbomar/Core-CMS-Plugin-System-Monitor

## Features

1. Renders heading, description, and structured data about a system.
1. Renders supported, nested plugin instances to incorporate extra content.
    <details>

    | content | supported by |
    | :- | :- |
    | subsystem/resources data | [`taccsite_data_list`][tacc-dlist] |
    | system image | [`djangocms-picture`][dcms-picture] |
    | system monitor | [`taccsite_system_monitor`][tacc-sysmon] |

    </details>
