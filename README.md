Read Git release notes in the terminal.

The release notes are fetched from https://github.com/git/git/tree/master/Documentation/RelNotes.

### Installation
1. Download the script `git-relnotes`.
2. Save it as `/usr/local/bin/git-relnotes`, or use any directory available in `$PATH`.
3. Ensure the script is made executable.

### Usage

* Show the release notes for the currently installed git version

	`git relnotes`

* List recently releases from https://github.com/git/git/releases

	`git relnotes -l`

* List all releases

  `git relnotes -L`

* Show the release notes for a given version

	`git relnotes v2.14`

	`git relnotes 2.14.3`

	`git relnotes 2.15.0-rc2`    *# Caveat: latest snapshot of upcoming v2.15.0 release notes.*
