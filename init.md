Beginning of script file should start with `#!/bin/bash`
Good practice: save in `~/bin/` dir

If missing "execute" permission: `chmod +x script.sh`
To ensure scripts in `~/bin/` are available, add this directory to `PATH` within config file (~/.bash_profile)
* PATH=~/bin:$PATH
