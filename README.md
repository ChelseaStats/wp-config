#### wp-config

> A stripped down WP config

With all the comments and line-breaks removed and some clever additions this wp-config is good to go.

##### Features

+ Home & site URL uses the `HTTP HOST` from the server (`$_SERVER`).
+ WP-content is renamed to `assets`
+ MU-plugins are stored in the `core` folder within `assets`, Parallel to ordinary `plugins`.
+ Post revisions are off
+ Empty trash after 30 days is on
+ Caching, concatenating, and debugging to log are on
