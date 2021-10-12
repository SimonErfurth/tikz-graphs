# tikz-graphs
A collection of generic graphs drawn in TiKz.

## Why?
While one can find many collections of examples of graphs and other
drawings in TiKz on the internet, most of them are highly specialised, and are
often needlessly complex, to show what one can accomplish with TiKz.

When writing an assignment, one is often just interested in some simple graphs,
that one can then work on top of. This is further needed if decides to use TiKz
for a written exam, where time is often limited.

Therefore this collection of simple graphs is desired. Additionally, since it is
on github it is easily cloned before an exam, and, assuming it is kept
organised, it is easy to find the graph on is looking for.

# Contributing
Contributions are very welcome, but pull request will only be
accepted if the contribution follows the following guidelines.

- Folders: Each family of graphs should live in a folder with a matching name,
  i.e. `Complete graphs K_n` or ` Bipartite graphs K_(n,m)`.
- Files: Each file should have a descriptive filename, i.e. in `Complete graphs
  K_n` we should have `K_3`, `K_4`m `K_5` etc.
- Preamble: If any graph depends on the loading of pacakages (other than TiKz)
  or TiKz libraries, these should be included in the top of the file, but
  commented out.
- Naiming: Vertex and edge names should follow a pattern, and be consistent with
  this pattern. If needed, each file should include a description of the
  pattern.
