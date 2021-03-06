# wp widget

<small>Quick links: <a href="https://github.com/issues?q=is%3Aopen+label%3Acommand%3Awidget+sort%3Aupdated-desc+org%3Awp-cli">Github issues</a></small>

Manage sidebar widgets.

### EXAMPLES

    # List widgets on a given sidebar
    $ wp widget list sidebar-1
    +----------+------------+----------+----------------------+
    | name     | id         | position | options              |
    +----------+------------+----------+----------------------+
    | meta     | meta-6     | 1        | {"title":"Meta"}     |
    | calendar | calendar-2 | 2        | {"title":"Calendar"} |
    +----------+------------+----------+----------------------+

    # Add a calendar widget to the second position on the sidebar
    $ wp widget add calendar sidebar-1 2
    Success: Added widget to sidebar.

    # Update option(s) associated with a given widget
    $ wp widget update calendar-1 --title="Calendar"
    Success: Widget updated.

    # Delete one or more widgets entirely
    $ wp widget delete calendar-2 archive-1
    Success: 2 widgets removed from sidebar.



### SUBCOMMANDS

<table>
	<thead>
	<tr>
		<th>Name</th>
		<th>Description</th>
	</tr>
	</thead>
	<tbody>
		<tr>
			<td><a href="https://developer.wordpress.org/cli/commands/widget/add/">add</a></td>
			<td>Add a widget to a sidebar.</td>
		</tr>
		<tr>
			<td><a href="https://developer.wordpress.org/cli/commands/widget/deactivate/">deactivate</a></td>
			<td>Deactivate one or more widgets from an active sidebar.</td>
		</tr>
		<tr>
			<td><a href="https://developer.wordpress.org/cli/commands/widget/delete/">delete</a></td>
			<td>Delete one or more widgets from a sidebar.</td>
		</tr>
		<tr>
			<td><a href="https://developer.wordpress.org/cli/commands/widget/list/">list</a></td>
			<td>List widgets associated with a sidebar.</td>
		</tr>
		<tr>
			<td><a href="https://developer.wordpress.org/cli/commands/widget/move/">move</a></td>
			<td>Move the position of a widget.</td>
		</tr>
		<tr>
			<td><a href="https://developer.wordpress.org/cli/commands/widget/reset/">reset</a></td>
			<td>Reset sidebar.</td>
		</tr>
		<tr>
			<td><a href="https://developer.wordpress.org/cli/commands/widget/update/">update</a></td>
			<td>Update options for an existing widget.</td>
		</tr>
	</tbody>
</table>
