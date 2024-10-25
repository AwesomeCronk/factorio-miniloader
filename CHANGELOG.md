These are changes made by AwesomeCronk to get Factorio 2.0 compatibility

# 2.0.0

- pack.sh:1 - Changed `#!/bin/sh` to `#!/bin/bash` because `sh` on my system is `dash` and it caused errors
- prototypes/entities.lua:196 - Changed `circuit_connector_definitions.create` to `circuit_connector_definitions.create_vector`
- prototypes/recipies.lua:8-47 - Restructured recipe definitions
