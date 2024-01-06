# brian's GPX tools

I do some stuff where I track routes with [Avenza]() then upload files to Dropbox. I use these tools to process those files and move them to the right place.

* `gpx_splitter` - turn multi-track files into multiple single track files
* `gpx_renamer` - name the files how I need them. *YYYYMMDD - location.gpx*
* `gps_watcher` - the cron script I use to watch the directory

For this to work in cron, you need to enable Full Disk Mode to cron.
See https://apple.stackexchange.com/questions/378553/crontab-operation-not-permitted

Use these how you like under the Artistic License 2.0. See the
*LICENSE* file in this project. See the CONTRIBUTING file too.

The original source is at [https://github.com/briandfoy/brians_gpx_tools](https://github.com/briandfoy/brians_gpx_tools).

You need Perl (at least v5.10) and Mojolicious:

	$ cpan Mojolicious IO::Interactive

As with many of my things, I store the repo on more than one service:

* [GitHub](https://github.com/briandfoy/brians_gpx_tools)
* [Gitlab](https://gitlab.com/briandfoy/brians_gpx_tools)
* [Bitbucket](https://bitbucket.org/theperlreview/brians_gpx_tools)
* [Codeberg](https://codeberg.org/briandfoy/brians_gpx_tools)
