# Post-Boot Diagnostics at Instance Console

This service and script will update a file in `/etc/issue.d/` that will be output to the console
before the getty service starts, and accessible without loging into the instance either by watching
the boot process or waiting for a login to timeout and allowing the tty to refresh (60 seconds).

Note: This is a POC. The script and file permissions are currently set to the user "ubuntu."
