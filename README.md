# Azure Utils
###### @Adamency

### Summary

Collections of scripts for manipulating Azure resources programmatically

### Legend

$${\scriptsize \color{orange}\text{script_name}$$

With `<script_name>` the base name of a script:

##### `<br>script_name>.ps1<br/>`
##### <br>script_name>.ps1<br/>

is a powershell script

##### `<script_name>.sh`

is a Unix shell script (*may use some bash-only constructs.*)

##### `<script_name>.unixified.ps1`

is a powershell script which uses some Unix commands (all can be installed with [`scoop`](https://github.com/scopinstaller/scoop))

##### `<script_name>.shell_config.ps1`

is powershell code meant to be put in a Powershell configuration script, what microsoft calls a "profile". It is accessible with `vim $profile` (or any other editor) inside a Powershell session.

##### `<script_name>.shell_config.sh`

is shell code meant to be put in a Unix shell configuration script, typically `~/.bashrc`.

