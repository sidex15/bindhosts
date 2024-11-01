bindhosts

writable /system/etc/hosts via mount --bind
  
  1.0.0 - 1.3.9
   - initial
   - various stuff
   - copies old hosts file on update
   - fix magisk support
   - hardcode moddir
   - disable and copy old hosts file from other modules too
   - [susfs](https://gitlab.com/simonpunk/susfs4ksu) try_umount support added
   - [susfs](https://gitlab.com/simonpunk/susfs4ksu) modernized susfs support

  1.4.2 - 1.4.4
   - sources, blacklist and whitelist support
   - optimize and check for other downloaders
   - fully implemented, standalone hosts-based-adblocking implementation

  1.4.5
   - detect user changes, fix localhost bug

[Download](https://raw.githubusercontent.com/backslashxx/bindhosts/master/module.zip)

[report for any issues](https://github.com/backslashxx/bindhosts/issues)

[Building your own kernel? grab this!](https://github.com/tiann/KernelSU/pull/1494)

[Pro at building your own kernel? grab this!](https://gitlab.com/simonpunk/susfs4ksu)
