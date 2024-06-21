# Awesome WordPress Playground [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[WordPress Playground](https://wordpress.github.io/wordpress-playground/) is WordPress in one click. It's a platform that lets you run WordPress instantly on any device without a host. It’s your place to build, experiment, test, and grow.

This list collects awesome uses of playground and awesome tools to build with it.

## Contents

- [Use It](#use-it)
- [Building Blueprints](#building-blueprints)


## Use it

This is where WordPress Playground powers applications that were not possible or much harder without it.

- [Gutenberg Pull Request Previewer](https://playground.wordpress.net/wordpress.html) - Run a <a href="https://github.com/WordPress/gutenberg/">Gutenberg</a> Pull Request in a playground to test it.
- [Playground inside Playground](https://playground.wordpress.net/#{%22landingPage%22:%22/wp-admin/post.php?post=1&action=edit%22,%22steps%22:[{%22step%22:%22login%22},{%22step%22:%22installPlugin%22,%22pluginZipFile%22:{%22resource%22:%22wordpress.org/plugins%22,%22slug%22:%22interactive-code-block%22}},{%22step%22:%22writeFile%22,%22path%22:%22/wordpress/post.txt%22,%22data%22:%22%3C!--%20wp:wordpress-playground/playground%20{\%22codeEditor\%22:true,\%22files\%22:[{\%22name\%22:\%22index.php\%22,\%22contents\%22:\%22%3C?php\\\\n/**\\\\n%20*%20Plugin%20Name:%20A%20WordPress%20plugin\\\\n%20*/\\\\nadd_action('init',%20function()%20{\\\\n%20%20update_option('blogname',%20'This%20is%20a%20Playground%20demo!');\\\\n});\%22}]}%20/--%3E%22},{%22step%22:%22runPHP%22,%22code%22:%22%3C?php%20require%20'/wordpress/wp-load.php';%20kses_remove_filters();%20wp_update_post(['ID'=%3E1,'post_title'%20=%3E%20'Playground%20Plugin%20Editor',%20'post_content'=%3Efile_get_contents('/wordpress/post.txt')]);%22}]}) - Uses the interactive code block to do a live preview of the code.
- [Playground Synchronization](https://playground.wordpress.net/demos/time-traveling.html) - Record changes made in one playground and play them back in a second playground.
- [Time Traveling](https://playground.wordpress.net/demos/time-traveling.html) - Record changes made in one playground and play them back in a second playground.
- [Translate Live](https://translate.wordpress.org/projects/wp-plugins/friends/dev/de/default/playground/) - Inline Translation for WordPress plugins and themes, here is an example of the [WordPress Plugin Friends](https://wordpress.org/plugins/friends/) and the language German.
- [WordPress Core Pull Request Previewer](https://playground.wordpress.net/wordpress.html) - Run a <a href="https://github.com/WordPress/wordpress-develop/">WordPress Core</a> Pull Request in a playground to test it.
- [WP-CLI in the browser](https://playground.wordpress.net/demos/wp-cli.html) - Puts a wp-cli commandline above a playground to manipulate it.

## Building Blueprints

- [Blueprint Builder](https://playground.wordpress.net/builder/builder.html) - A codepen-like environment for building blueprints with autocomplete.
- [Blueprints Gallery](https://github.com/WordPress/blueprints/blob/trunk/GALLERY.md) - A directory of blueprints that demonstrate different ways to use them.
- [Step Library](https://akirk.github.io/playground-step-library/) - A collection of custom steps that you can use to build your own blueprint, along with a UI.


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
