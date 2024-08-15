Beginning of script file should start with `#!/bin/bash`
Good practice: save in `~/bin/` dir

If missing "execute" permission: `chmod +x script.sh`
To ensure scripts in `~/bin/` are available, add this directory to `PATH` within config file (~/.bash_profile)
* PATH=~/bin:$PATH

Here is the list of comparison operators for numbers you can use within bash scripts:

Equal: -eq
Not equal: -ne
Less than or equal: -le
Less than: -lt
Greater than or equal: -ge
Greater than: -gt
Is null: -z
When comparing strings, it is best practice to put the variable into quotes ("). This prevents errors if the variable is null or contains 
spaces. The common operators for comparing strings are:

Equal: ==
Not equal: !=
