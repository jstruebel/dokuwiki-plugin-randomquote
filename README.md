# randomquote Plugin for DokuWiki

This is a very (!) simple syntax plugin for DokuWiki that allows you to show random quotes on your DokuWiki page.
The plugin is file-based and relies on a list of quotes stored in a `quotes.txt` file.
Each quote is a separate line in the `quotes.txt` file.


## Usage

After installing the plugin, all instances of `<randomquote>` will be replaced with a random quote. 

To customize the quotes or to change the style, please create a `quotes.txt` in `/data/pages` and edit the `userstyle.css` file in your `/conf` directory.

The `quotes.txt` file can be created through the wiki front-end by creating a top-level quotes page. You can use an ACL to restrict access to the `quotes.txt` file to prevent unauthorized modifications.

## Development

This plugin initially was not intended for public use. Therefore it is very bare-bones and, for example, does not have
the option of making settings via the admin pages. Feel free to make it better!
