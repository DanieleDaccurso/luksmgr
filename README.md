# luksmgr

WORK IN PROGRESS

## luksmgr, an easy utility to manage encrypted containers
### Usage: luksmgr [command [...options]]

  commands:
      create (name, size, [pass])
        creates a new container
            - name    A name, must be valid as a filename
            - size    Container size in MB
            - pass    Optional, passphrase to encrypt the container.
                      If ommitted, passphrase will be prompted.

      mount (name, path, [pass])
        mounts a container
            - name    Name of the container
            - path    Path to mount (must be folder and empty)
            - pass    Optional, passphrase to decrypt the container.
                      if ommitted, passphrase will be prompted.

Copyright: (c) 2017 Daniele D'Accurso <daniele@daccurso.net>
This utility is distributed under the BSD license

For issues, visit: https://github.com/danieledaccurso/luksmgr
