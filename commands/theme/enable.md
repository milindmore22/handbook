# wp theme enable

<small>Quick links: <a href="https://github.com/issues?q=is%3Aopen+label%3Acommand%3Atheme-enable+sort%3Aupdated-desc+org%3Awp-cli">Github issues</a></small>

Enable a theme on a WordPress multisite install.

Permits theme to be activated from the dashboard of a site on a WordPress
multisite install.

### OPTIONS

&lt;theme&gt;
: The theme to enable.

[\--network]
: If set, the theme is enabled for the entire network

[\--activate]
: If set, the theme is activated for the current site. Note that
the "network" flag has no influence on this.

### EXAMPLES

    # Enable theme
    $ wp theme enable twentysixteen
    Success: Enabled the 'Twenty Sixteen' theme.

    # Network enable theme
    $ wp theme enable twentysixteen --network
    Success: Network enabled the 'Twenty Sixteen' theme.

    # Network enable and activate theme for current site
    $ wp theme enable twentysixteen --activate
    Success: Enabled the 'Twenty Sixteen' theme.
    Success: Switched to 'Twenty Sixteen' theme.



