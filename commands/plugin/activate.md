# wp plugin activate

<small>Quick links: <a href="https://github.com/issues?q=is%3Aopen+label%3Acommand%3Aplugin-activate+sort%3Aupdated-desc+org%3Awp-cli">Github issues</a></small>

Activate a plugin.

### OPTIONS

[&lt;plugin&gt;...]
: One or more plugins to activate.

[\--all]
: If set, all plugins will be activated.

[\--network]
: If set, the plugin will be activated for the entire multisite network.

### EXAMPLES

    # Activate plugin
    $ wp plugin activate hello
    Plugin 'hello' activated.
    Success: Activated 1 of 1 plugins.

    # Activate plugin in entire multisite network
    $ wp plugin activate hello --network
    Plugin 'hello' network activated.
    Success: Network activated 1 of 1 plugins.



