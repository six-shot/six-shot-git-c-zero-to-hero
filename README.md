# Learn C by reading Git

A zero-to-hero guide to C, taught from the source code of [Git](https://git-scm.com/)
itself. It is aimed at people who want to contribute to Git, especially to the work on
reducing Git's global state (`the_repository`) so Git can be used as a library.

New to C? Start with sections A–D:

- A. What C is, and what Git is made of
- B. Setting up a compiler and building Git
- C. Your first C program, including how to read a compiler error
- D. Git in one picture

Then each level teaches one idea from a real piece of git.git:

0. The map of git.git
1. Headers, declarations and `#include`
2. Structs, enums and initializers
3. Pointers
4. Strings, memory and `strbuf`
5. Errors, `die()` and `goto` cleanup
6. The preprocessor and `USE_THE_REPOSITORY_VARIABLE`
7. Scope, `static` and global variables
8. Function pointers and callbacks
9. How a command runs
10. Patterns for removing global state
11. Reading and running Git's tests
12. From commit to the mailing list

It finishes by tracing a repository from `git merge-tree` down to `merge_blobs()`, then a
reading list and a glossary.

## How to use it

Open `index.html` in a browser, or read it online at
https://six-shot.github.io/git-c-zero-to-hero/ once GitHub Pages is on.

Type every example yourself, try each exercise before opening the answer, and read
the compiler's warnings carefully. Git's community wants to mentor humans, not AIs:
make sure you understand everything you send.

## Credits

Code excerpts come from [Git](https://git.kernel.org/pub/scm/git/git.git), licensed
under the GNU General Public License version 2.
# six-shot-git-c-zero-to-hero
