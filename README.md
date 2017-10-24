# foundationpress-breadcrumbs
FoundationPress Breadcrumbs

FoundationPress discontinued supporting breadcrumbs (Oct 2017).

Custom Post Types and Custom Taxonomies were not supported as described here:
https://github.com/olefredrik/FoundationPress/issues/1088

SKY1 updated to the following code as described on that page:
https://www.thewebtaylor.com/articles/wordpress-creating-breadcrumbs-without-a-plugin

Then removed separator li to match Foundation example markup. 

WORKS!

To use this code just add a require_once statement to breadcrumbs.php in your functions.php file and it should work.  

So if you place the file in the /library directory your code/statement should look like this in your functions.php: 

<code>
// FoundationPress Breadcrumbs
require_once( 'library/breadcrumbs.php' );
</code>
