# wp role

<small>Quick links: <a href="https://github.com/issues?q=is%3Aopen+label%3Acommand%3Arole+sort%3Aupdated-desc+org%3Awp-cli">Github issues</a></small>

Manage user roles.

### EXAMPLES

    # List roles.
    $ wp role list --fields=role --format=csv
    role
    administrator
    editor
    author
    contributor
    subscriber

    # Check to see if a role exists.
    $ wp role exists editor
    Success: Role with ID 'editor' exists.

    # Create a new role.
    $ wp role create approver Approver
    Success: Role with key 'approver' created.

    # Delete an existing role.
    $ wp role delete approver
    Success: Role with key 'approver' deleted.

    # Reset existing roles to their default capabilities.
    $ wp role reset administrator author contributor
    Success: Reset 3/3 roles.



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
			<td><a href="https://developer.wordpress.org/cli/commands/role/create/">create</a></td>
			<td>Create a new role.</td>
		</tr>
		<tr>
			<td><a href="https://developer.wordpress.org/cli/commands/role/delete/">delete</a></td>
			<td>Delete an existing role.</td>
		</tr>
		<tr>
			<td><a href="https://developer.wordpress.org/cli/commands/role/exists/">exists</a></td>
			<td>Check if a role exists.</td>
		</tr>
		<tr>
			<td><a href="https://developer.wordpress.org/cli/commands/role/list/">list</a></td>
			<td>List all roles.</td>
		</tr>
		<tr>
			<td><a href="https://developer.wordpress.org/cli/commands/role/reset/">reset</a></td>
			<td>Reset any default role to default capabilities.</td>
		</tr>
	</tbody>
</table>
