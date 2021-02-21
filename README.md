The ** Post To OpenCart ** plugin is designed to publish posts from WordPress to OpenCart 2.3.x.

After installing and activating the plugin on the "Settings> Post To OpenCart" page:

* Set site address in ** OpenCart URL ** field
* Set the key in the ** OpenCart API Key ** field.

The API key can be found in the OpenCart admin panel on the System> Users> API page.

For the plugin to work, you need to add an additional field to the post editor. To do this, install the ** Advanced Custom Fields ** plugin and configure an additional field:

* post type - post
* field label - Publish to news feed
* field name - push_to
* elections -
``,
no: No
yes: Yes
``,
! [screenshot-2.png] (screenshot-2.png)


After that, the "Publish to news feed" field appears in the post editor. By selecting the ** Yes ** option and clicking the ** Publish ** (** Update **) button, the current post is saved to the OpenCart website:

! [screenshot-3.png] (screenshot-3.png)


## OpenCart Settings

In the admin panel of OpenCart, you need to allow access to the API from the news site. The news feed can accept and save posts from several different sites. To do this, on the "System> Users> API" page, add a new API key for each source (domain name). In the ** IP address ** tab add the real IP address of the news site:

