#### wp-config

> A stripped down WP config

With all the comments and line-breaks removed and some clever additions this wp-config is good to go.

##### Features

+ Home & site URL uses the HTTP HOST from the server.
   <small>(overwriting the wp-options; less db calls, easier to work on multi-environments)</small>
+ WP-content is renamed to `assets`
+ MU-plugins are stored in the `core` folder within `assets`
+ post revisions are off, and empty trash after 30 days is on
+ caching, concatenating, and debugging to log is on
