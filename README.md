# MacPostFactor

# Bringing OS X 10.8+ to older Macs

MacPostFactor has been dev since 2014 when I was in year 9.

Thus the code is a mixture of great and bad.

I'm currently refining it so it'll fit nicely on github.

## How things are going?

The new MacPostFactor v3.0 is almost complete. It can install OS X Mountain Lion on a MacBook
with proper patches.

However, there are still stuff to do:

- Custom Recovery (currently, the recovery boot, but is stock)
- USB Key support (currently, MCPF can generate a bootable USB Key, but it cannot install patched OS X)
- Testing all patches and versions

These aren't so long to do, but given the very low ammount of time I have to focus on it, it ends up
taking some time to do.

As such, I won't give any ETA except that I'd like to release this new version in 2020.

## Why do I continue?

The reasons I continue working on it are:

- I collect those old Macs
- I like fiddling around them
- I see emails of people who are still using the software and having issues with the current version.

On that last topic, one reason I don't answer (or at least quickly) is that I cannot fix your problem :

Some of the bugs MacPostFactor v2.0.1 or earlier have are inherent to their design.
Furthermore, the ammount of info it gives me is slim. For example, I don't get `stderr` of the install script,
which makes it complicated to fix some issues that could be.
