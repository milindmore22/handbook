# wp cap

<small>Quick links: <a href="https://github.com/issues?q=is%3Aopen+label%3Acommand%3Acap+sort%3Aupdated-desc+org%3Awp-cli">Github issues</a></small>

Manage user capabilities.

### EXAMPLES

    # Add 'spectate' capability to 'author' role.
    $ wp cap add 'author' 'spectate'
    Success: Added 1 capability to 'author' role.

    # Add all caps from 'editor' role to 'author' role.
    $ wp cap list 'editor' | xargs wp cap add 'author'
    Success: Added 24 capabilities to 'author' role.

    # Remove all caps from 'editor' role that also appear in 'author' role.
    $ wp cap list 'author' | xargs wp cap remove 'editor'
    Success: Removed 34 capabilities from 'editor' role.



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
			<td><a href="https://developer.wordpress.org/cli/commands/cap/add/">add</a></td>
			<td>Add capabilities to a given role.</td>
		</tr>
		<tr>
			<td><a href="https://developer.wordpress.org/cli/commands/cap/list/">list</a></td>
			<td>List capabilities for a given role.</td>
		</tr>
		<tr>
			<td><a href="https://developer.wordpress.org/cli/commands/cap/remove/">remove</a></td>
			<td>Remove capabilities from a given role.</td>
		</tr>
	</tbody>
</table>
