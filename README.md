## Personal website
Website created with hugo, R blogdown, and the wowchemy academic theme. Served at [sslou.github.io](sslou.github.io).

## Folders
* config - contains configuration .toml files for layout of menus, and website parameters (including contact info, themes, fonts, layout of sections)
* content
    - authors/admin -  user profile information, used for about widget on homepage
    - home - configure homepage widgets
    - publication - one folder for each publication featured on the website. `_index.md` contains the content for /publications/ where filtering and searching can occur. Can add `featured.jpg` image files and `cite.bib` files to each publication folder.
    - resources - currently formatted with `type: post`. One folder for each post. Can consider switching to `type:book` if TOC etc is desired, can create more complex pages that way.