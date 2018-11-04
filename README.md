# sssd-limit-user-filter

Ansible role to configure an sssd user filter to limit the number of users that may be permitted to log into a system.

## Variables
* `sssd_filter_domain`: Active Directory domain that the filter will apply to
* `sssd_filter_username` (optional): username to configure the filter to, Defaults to the current username.
