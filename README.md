# FireMacro

FireMacro enables the templatization of our business and configuration data. It merges
data with objects, arrays, strings and other atomic types. It can conditionally rewrite
object structure and loop. It is intended for scripted integration with foreign
modules and services.

FireMacro is used throughout the metric-im componentry collection. However, it has
no dependencies to the componentry structure. The only external library it uses is
"moment", but only needed when the macro template references date variables.

FireMacro will run in the browser or node.

**[Full Reference](./doclets/FireMacro.md)**
