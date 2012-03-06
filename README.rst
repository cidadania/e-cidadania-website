e-cidadania website
===================

This is the source code for the website of e-cidadania. It was created using
the static website generator `Hyde <http://github.com/hyde/hyde>`_ 0.8.4 and
`Twitter Bootstrap 2.0 <http://twitter.github.com/bootstrap>`_.

To work propertly, this website requires a rewrite to your default language.
Example (for spanish as default)::

    Options +FollowSymlinks
    RewriteEngine On
    RewriteCond %{HTTP_HOST} ^ecidadania\.org$
    RewriteRule (.*) http://www.ecidadania.org/$1 [R=301,L]
    RewriteRule ^$ /es [R=301,L]

Features
========

 - Navigation
 - Multilanguage (english, spanish, galician)
 - Social (Facebook, Twitter)
 - Blog
 - Dynamic footer

Feel free to copy and/or modify. Licensed under GPLv3.
