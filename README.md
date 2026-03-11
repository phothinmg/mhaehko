# mhaehko

A static analysis tool designed to examine TypeScript and JavaScript projects and produce dependency graphs,using TypeScript APIs.

## Key Features

- **Dependency Graph Generation:** Analyze TypeScript/JavaScript projects to map file dependencies.
- **Circular Dependency Detection:** Implements depth-first search (DFS) algorithms to identify cycles in the dependency graph, helping developers locate problematic import patterns.
- **Topological Sorting:** Files are ordered according to their dependency relationships, enabling build systems and bundlers to process files in the correct sequence.
- **Leaf & Mutual Dependencies:** Find files with no local imports and mutual (two-way) dependencies.
- **NPM & Node Built-in Detection:** List external and built-in module usage.
