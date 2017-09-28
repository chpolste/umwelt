# umwelt

A simple PATH environment manager for interactive bash sessions.

```
usage:  umwelt list
        umwelt append <environment> <path>...
        umwelt edit <environment>
        umwelt remove <environment>
        umwelt enter <environment>...

Put environment files (containing one path per line) into '~/.config/umwelt' or
use the append, edit and remove subcommands to manage environments. Entering an
environment launches an interactive session of bash where the PATH variable is
extended by the paths specified in the environment file. Multiple environments
can be activated at the same time. To exit an entered environment just leave
the launched session of bash (exit or ^D).
```
