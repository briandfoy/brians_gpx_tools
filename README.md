# brian's GPX tools

I do some stuff where I track routes with [Avenza]() then upload files to Dropbox. I use these tools to process those files and move them to the right place.

* `gpx_splitter` - turn multi-track files into multiple single track files
* `gpx_renamer` - name the files how I need them. *YYYYMMDD - location.gpx*
* `gps_watcher` - the cron script I use to watch the directory

Use these how you like under the Artistic License 2.0. See the
*LICENSE* file in this project. See the CONTRIBUTING file too.

The orignal source is at [https://github.com/briandfoy/brians_gpx_tools](https://github.com/briandfoy/brians_gpx_tools).

You need Perl (at least v5.10) and Mojolicious:

	$ cpan Mojolicious IO::Interactive
