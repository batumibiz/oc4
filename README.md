# OpenCart 4.1.0.3++
This project is a collection of improvements and fixes for [OpenCart 4.1.0.3].

### Why this repository exists
To provide a stable, production-ready environment by backporting essential fixes while strictly avoiding the breaking changes found in the official development branches.

### Compatibility Guarantee
All modifications and enhancements are strictly developed to maintain full backward compatibility with [OpenCart 4.1.0.3].

### Why the "++" in the name?
The OpenCart 4.1.0.3++ designation signifies that this repository is a "plus-plus" edition of the original 4.1.0.3 release:
- The first + represents fixes for bugs and issues identified after the official 4.1.0.3 release.
- The second + stands for additional enhancements and optimizations that strictly maintain full backward compatibility.

This ensures a robust, production-ready core that remains a drop-in replacement for any 4.1.0.3-compatible environment.


## Versioning & Branching Strategy
To maintain clarity and project stability, OpenCart 4.1.0.3++ follows an absolute versioning system ($v1$, $v2$, etc.).
All code changes in this project originate from the official [OpenCart 4.1.0.3] release.

### Branch Workflow:
- `release` (Stable): contains production-ready, stable code.
    Release tags are applied here, making it easy to track changes and diffs between project versions.
- `main` (Development): The primary branch where verified improvements and fixes are accumulated.
  While generally stable, this branch may contain bugs that require further refinement.
  **Core functionality must remain operational at all times**.
- `develop` (Feature/Testing): A temporary branch for unverified or experimental code.
  General stability is not guaranteed. Once the code is stabilized, it is moved to `main` via **squash merge**,
  and the `develop` branch is deleted.
- Other temporary branches may be created as needed for specific tasks or features.


## Credits & Sources
To ensure transparency and acknowledge the work of the community, direct links to original sources or discussions
are provided in the [CHANGELOG](https://github.com/batumibiz/oc4/blob/main/CHANGELOG.md) for any borrowed or ported code.

Modifications without a specific link were developed within this repository.


## License
GNU General Public License version 3 ([GPLv3](https://github.com/batumibiz/oc4/blob/main/LICENSE))


## Links

- [OpenCart sources](https://github.com/opencart/opencart)
- [OpenCart forums](https://forum.opencart.com/)
- [Discussions](https://github.com/opencart/opencart/discussions)


[OpenCart 4.1.0.3]: https://github.com/opencart/opencart/releases/tag/4.1.0.3