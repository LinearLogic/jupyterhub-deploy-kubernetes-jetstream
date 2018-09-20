## Create the VM

Execute interactively the commands in `create_vm_command_line.log`,
check that the outputs make sense.
Those commands and all the naming convention taken from the Jetstream help page:

<https://iujetstream.atlassian.net/wiki/spaces/JWT/pages/35913730/OpenStack+command+line>

Change the hostname with `sudo hostnamectl set-hostname NEWHOSTNAME`

## Configure accounts

Edit and run:

    bash create_users.sh
    sudo bash create_passwords_call_with_sudo.sh