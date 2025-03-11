---
name: UI
size: 6EC
---

Brane is aimed at usability for domain specialized, who may not necessarily be computer scientists or engineers.
As such, the current command-line tool is not ideal for this target audience. A Jupyter notebook plugin does exist, but only solves the problem partially, as it still requires code to create workflows and does not handle package mangement.
This while workflows are, by their graph-like nature, very good candidates to create user-friendly, no-code interfaces for.

This project aims to investigate if a no-code development environment can be created for easy domain-scientist access to Brane. This is what you'd be doing:
1. Investigate which solutions already exist to graphically create workflows and if they can be used somehow (albeit through translations via e.g. plugins) or instead serve as inspiration.
2. Develop a new development environment for creating BraneScript workflows based on a graphical interface.
3. Add support for importing & inspecting Brane packages to this interface.
