# wp user update

<small>Quick links: <a href="https://github.com/issues?q=is%3Aopen+label%3Acommand%3Auser-update+sort%3Aupdated-desc+org%3Awp-cli">Github issues</a></small>

Update an existing user.

### OPTIONS

&lt;user&gt;...
: The user login, user email or user ID of the user(s) to update.

\--&lt;field&gt;=&lt;value&gt;
: One or more fields to update. For accepted fields, see wp_update_user().

### EXAMPLES

    # Update user
    $ wp user update 123 --display_name=Mary --user_pass=marypass
    Success: Updated user 123.



