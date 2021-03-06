# wp comment meta

<small>Quick links: <a href="https://github.com/issues?q=is%3Aopen+label%3Acommand%3Acomment-meta+sort%3Aupdated-desc+org%3Awp-cli">Github issues</a></small>

Manage comment custom fields.

### EXAMPLES

    # Set comment meta
    $ wp comment meta set 123 description "Mary is a WordPress developer."
    Success: Updated custom field 'description'.

    # Get comment meta
    $ wp comment meta get 123 description
    Mary is a WordPress developer.

    # Update comment meta
    $ wp comment meta update 123 description "Mary is an awesome WordPress developer."
    Success: Updated custom field 'description'.

    # Delete comment meta
    $ wp comment meta delete 123 description
    Success: Deleted custom field.





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
			<td><a href="https://developer.wordpress.org/cli/commands/comment/meta/add/">add</a></td>
			<td>Add a meta field.</td>
		</tr>
		<tr>
			<td><a href="https://developer.wordpress.org/cli/commands/comment/meta/delete/">delete</a></td>
			<td>Delete a meta field.</td>
		</tr>
		<tr>
			<td><a href="https://developer.wordpress.org/cli/commands/comment/meta/get/">get</a></td>
			<td>Get meta field value.</td>
		</tr>
		<tr>
			<td><a href="https://developer.wordpress.org/cli/commands/comment/meta/list/">list</a></td>
			<td>List all metadata associated with an object.</td>
		</tr>
		<tr>
			<td><a href="https://developer.wordpress.org/cli/commands/comment/meta/update/">update</a></td>
			<td>Update a meta field.</td>
		</tr>
	</tbody>
</table>
