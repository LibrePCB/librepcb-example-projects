# LibrePCB Example Projects

Projects in *.lppz format to be downloaded and installed by LibrePCB when
creating a new workspace.

## Maintenance

All projects should be updated to the latest file format before creating
a new major release of LibrePCB. To avoid breaking older LibrePCB
releases, links to the project files shall always include the Git
revision.

## Contributing

If you have a cool project which potential new users might find interesting
for evaluating LibrePCB, please open an issue or pull request! Requirements
for new projects are:

- Must be released under an open-source license (CC0-1.0 preferred)
- Must use as many parts from our official libraries as possible
  (self-made parts allowed only if not available in our libraries)
- A high percentage of parts must have MPN + manufacturer specified
- A high percentage of parts must have 3D models
- The more features used, the better (output jobs, assembly variants,
  alternate MPNs, multiple schematic sheets, multilayer boards...)
- The project should not be too trivial (e.g. just a breakout board)
- Although this is a subjective requirement, schematics and boards should
  generally be clean and well designed (no hacky projects)
