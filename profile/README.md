# Structure of repositories.

- All [Themes][1]
    - [Base theme][2]. One parent to rule them all.
    - [Base child theme][3]. The start of a new theme.
- All [Plugins][4]
  - [Premium Plugin Pile][5]. Hold the premium plugins
- All [Blocks][6]. Usually in a plugin.
- All [Devop tools][7]
  - [Silo][8]. WP-cli for all sites, create new environments on the server.
  - [Base][9]. Setup a project in [local](https://localwp.com/)

# Starting a new project

Use the [Base][9] The new theme _is_ the project, git wise.

# Creating a new repository

Make sure to **add the** correct **topic**. The basic topics we use.

 - [wp-theme][1]
 - [wp-plugin][4]
 - [wp-block][6]
 - [devops-tools][7]

Other topics might apply, more than one topic is allowed. 


[1]: https://github.com/search?q=org%3Awebfundament+topic%3Awp-theme        "All theme repos"
[2]: https://github.com/webfundament/base-theme
[3]: https://github.com/webfundament/base-theme-child
[4]: https://github.com/search?q=org%3Awebfundament+topic%3Awp-plugin       "All Plugin repos"
[5]: https://github.com/webfundament/premium-plugins-pile
[6]: https://github.com/search?q=org%3Awebfundament+topic%3Awp-block        "All Blocks"
[7]: https://github.com/search?q=org%3Awebfundament+topic%3Adevops-tools    "All Devop tools"
[8]: https://github.com/webfundament/base
[9]: https://github.com/webfundament/silo