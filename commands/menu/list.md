# wp menu list

<small>Quick links: <a href="https://github.com/issues?q=is%3Aopen+label%3Acommand%3Amenu-list+sort%3Aupdated-desc+org%3Awp-cli">Github issues</a></small>

Get a list of menus.

### OPTIONS

[\--fields=&lt;fields&gt;]
: Limit the output to specific object fields.

[\--format=&lt;format&gt;]
: Render output in a particular format.
\---
default: table
options:
  - table
  - csv
  - json
  - count
  - ids
  - yaml
\---

### AVAILABLE FIELDS

These fields will be displayed by default for each menu:

* term_id
* name
* slug
* count

These fields are optionally available:

* term_group
* term_taxonomy_id
* taxonomy
* description
* parent
* locations

### EXAMPLES

    $ wp menu list
    +---------+----------+----------+-----------+-------+
    | term_id | name     | slug     | locations | count |
    +---------+----------+----------+-----------+-------+
    | 200     | My Menu  | my-menu  |           | 0     |
    | 177     | Top Menu | top-menu | primary   | 7     |
    +---------+----------+----------+-----------+-------+



