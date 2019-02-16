# core-fetch

Core and asset updater for retroarch.

Downloads and extracts your current list of cores and/or asset files from the libretro buildbot into the appropriate folders specified by your retroarch user configuration file.

Either point to your config file with `-g retroarch.cfg` or within the script itself.

Update your current cores with `-c`, asset files with `-s`, or both with `-a`.

Use `-d` for a dry run and `-v` to display url targets and path destinations.

Tested on Linux and Windows platforms. Requires Python 3.
