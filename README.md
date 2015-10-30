This Git repository contains the metro stations for Washington DC, thanks to WMATA maps.

You can visualize the result in many ways, for example:
- GitHub network view: https://github.com/cdombroski/WMATA-MAP/network
- `gitk` on your local copy
- `git log --all --graph`

Each metro line is represented by a **branch** (`git checkout --orphan <branch>`).

A **commit** corresponds to a station. All commits are created empty (`git commit --allow-empty`)

A **merge** is a connection between two or more lines.
