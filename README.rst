Cron Jobs for Arch Linux packages
=================================

Arch Linux package maintainers have started removing cron jobs from several packages and replacing them with their respective systemd *timers*.

This repository aims to provide cron jobs for several Arch Linux packages, for those of us who prefer cron over systemd timers.

**Note:** You will have to place the files in the appropriate directory, i.e., one of
:code:`/etc/cron.{d,hourly,daily,weekly,monthly}` yourself.

If a cron job for your favourite package has gone missing from your system, you can probably recover it by taking a look at the history of the appropriate package from the Arch Linux `svntogit repository <https://projects.archlinux.org/svntogit>`_.
