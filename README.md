# swap
|     key | description
|     ---:|:---
|  script | swap - safely swap two files or directories
|    type | ruby
|  author | Wybo Dekker
|   email | wybo@dekkerdocumenten.nl
| version | 1.02
| license | GNU General Public License

swap swaps the names of two files or two directories. It makes sure that those
both exist, are writable, are both either directories or regular files, and are
not the same file. If the two are on different devices, swap makes sure that
the --copy option was used.
