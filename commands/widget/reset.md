# wp widget reset

<small>Quick links: <a href="https://github.com/issues?q=is%3Aopen+label%3Acommand%3Awidget-reset+sort%3Aupdated-desc+org%3Awp-cli">Github issues</a></small>

Reset sidebar.

Removes all widgets from the sidebar and places them in Inactive Widgets.

### OPTIONS

[&lt;sidebar-id&gt;...]
: One or more sidebars to reset.

[\--all]
: If set, all sidebars will be reset.

### EXAMPLES

    # Reset a sidebar
    $ wp widget reset sidebar-1
    Success: Sidebar 'sidebar-1' reset.

    # Reset multiple sidebars
    $ wp widget reset sidebar-1 sidebar-2
    Success: Sidebar 'sidebar-1' reset.
    Success: Sidebar 'sidebar-2' reset.

    # Reset all sidebars
    $ wp widget reset --all
    Success: Sidebar 'sidebar-1' reset.
    Success: Sidebar 'sidebar-2' reset.
    Success: Sidebar 'sidebar-3' reset.



