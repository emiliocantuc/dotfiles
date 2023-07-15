# Personal use bash scripts

To use all scripts as commands, the `.profile` script or equivalent must run the `add_to_path` script and
set an environment variable. 

For example, if this repo is located at `~/bash-scripts/`, add the following:

```sh
# Add my custom commands to PATH
source ~/bash-scripts/add_to_path ~/bash-scripts

# Push notification channel name
export NTFY_CHANNEL="[channel]"
```