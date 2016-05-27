This Drupal theme is a complete sub-theme of the [Drupal Bootstrap Theme](https://drupal.org/project/bootstrap).

It has bundled all of the [Boostrap](https://getbootstrap.com/) code in it, so creating a sub-theme of this theme is trivial:

 * Create a folder in your theme directory with a unique name (aka unique)
 * Create a file inside that directory called unique.info with the contents:
    name = unique 
    description = unique Subtheme
    base theme = civiresponsive 
    core = 7.x
    engine = phptemplate

    stylesheets[all][] = unique.css

    ;;;;;;;;;;;;;;;;;;;;;
    ;; Regions
    ;;;;;;;;;;;;;;;;;;;;;

    regions[navigation]     = 'Navigation'
    regions[header]         = 'Top Bar'
    regions[highlighted]    = 'Highlighted'
    regions[help]           = 'Help'
    regions[content]        = 'Content'
    regions[sidebar_first]  = 'Primary'
    regions[sidebar_second] = 'Secondary'
    regions[footer]         = 'Footer'
    regions[page_top]       = 'Page top'
    regions[page_bottom]    = 'Page bottom'

    settings[bootstrap_cdn] = ''
 * Create a css file called unique.css 
