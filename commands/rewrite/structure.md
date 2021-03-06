# wp rewrite structure

<small>Quick links: <a href="https://github.com/issues?q=is%3Aopen+label%3Acommand%3Arewrite-structure+sort%3Aupdated-desc+org%3Awp-cli">Github issues</a></small>

Update the permalink structure.

Sets the post permalink structure to the specified pattern.

To regenerate a .htaccess file with WP-CLI, you'll need to add
the mod_rewrite module to your [WP-CLI config](http://wp-cli.org/config/).
For example:

```
apache_modules:
  - mod_rewrite
```

### OPTIONS

&lt;permastruct&gt;
: The new permalink structure to apply.

[\--category-base=&lt;base&gt;]
: Set the base for category permalinks, i.e. '/category/'.

[\--tag-base=&lt;base&gt;]
: Set the base for tag permalinks, i.e. '/tag/'.

[\--hard]
: Perform a hard flush - update `.htaccess` rules as well as rewrite rules in database.

### EXAMPLES

    $ wp rewrite structure '/%year%/%monthnum%/%postname%'
    Success: Rewrite structure set.



