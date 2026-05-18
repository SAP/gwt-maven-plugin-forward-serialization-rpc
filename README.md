[![REUSE status](https://api.reuse.software/badge/github.com/SAP/gwt-maven-plugin-forward-serialization-rpc)](https://api.reuse.software/info/github.com/SAP/gwt-maven-plugin-forward-serialization-rpc)

The documentation for **Mojo's Maven Plugin for GWT** is here: https://gwt-maven-plugin.github.io/gwt-maven-plugin/

This fork is intended to be used in conjunction with the fork at https://github.com/SAP/gwt-forward-serialization-rpc and
in particular its branch ``issue-7987-compatibility-with-issue-9584`` which provides a solution
to the original GWT issue [7987](https://github.com/gwtproject/gwt/issues/7987) which asks for enabling
RPC response serialization in streaming mode. See also the
[fork's README](https://github.com/SAP/gwt-forward-serialization-rpc/tree/issue-7987-compatibility-with-issue-9584)
for more details.

**NOTICE** There is a [new plugin][ng] ([archetypes][archetype] and [eclipse integration][eclipse]), a fresh start 
that correctly support multi-module projects, it is not version-bounded with GWT, support multiples GWT versions and 
other fixes, improvements and best practices. This plugin is now considered the `legacy GWT maven plugin` (aka **mojo**
GWT maven plugin) and the new one is considered the `new generation GWT maven plugin` (aka **tbroyer** GWT maven 
plugin). The legacy maven plugin is still supported but it is strongly encouraged to use the new one for new projects.

[ng]: https://github.com/tbroyer/gwt-maven-plugin
[archetype]: https://github.com/tbroyer/gwt-maven-archetypes
[eclipse]: http://gwt-plugins.github.io/documentation/gwt-eclipse-plugin/maven/Maven.html
