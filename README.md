# Experiments with the Maven Release Plugin
In this repository I have performed some experiments with the Maven Release Plugin.
Usually, this plugin is used to create a Git _tag_ for every release.

In addition, I would like it to _also_ create a _branch_ that starts at the _tag_.

```
      1.5.0 (tag)
      |
------*---- master (branch) --------
      \
       \--- release-1.5 (branch) ---
```