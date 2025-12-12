# renovate-config
Renovate configuration presets for my repos.


## default
Base configuration that inherits multiple different configurations.

Usage: `"extends": ["github>c-gerke/renovate-config"]`

Included in default: Yes


## add-labels
Adds standard label(s) to Renovate PRs.

Usage: `"extends": ["github>c-gerke/renovate-config:add-labels"]`

Included in default: Yes


## rangeStrategy / pinDigests
Adds a default range strategy of "pin". This causes Renovate to create PRs that update dependencies to specific versions or SHA hashes where possible to ensure the most reproducible builds.

Usage: `"rangeStrategy": "pin"` and `"pinDigests": true`

Included in default: Yes


## auto-merge-only-minor-updates
Automatically merge minor and patch updates, but not major updates.

Usage: `"extends": ["github>c-gerke/renovate-config:auto-merge-only-minor-updates"]`

Included in default: No