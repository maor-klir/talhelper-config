## talhelper configuration files

`talhelper` is a tool to help creating Talos configuration files declaratively.

The main reason to use `talhelper` instead of `talosctl gen config` command to generate Talos machineconfig files is because we want to have them version controlled in our Git repository which is currently not possible yet with `talosctl`.
