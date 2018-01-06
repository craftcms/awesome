<div align="center">
	<img width="400" src="https://cdn.rawgit.com/chasegiunta/awesome-craft/master/awesome-craft.svg" alt="Awesome Craft CMS">
  <br><br>
</div>

# Awesome Craft CMS [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
> Carefully curated list of awesome Craft CMS plugins, articles, resources and shiny things.

[Craft CMS](https://craftcms.com) is a focused content management system for developers, designers, and web professionals that blends flexibility, power, and ease of use for clients. Built to be as exceptionably scalable and as flexible as possible, without compromising on the ease of use for content authors.

### Contributing
Please take a quick look at the [contribution guidelines](CONTRIBUTING.md) first. If you see a plugin, article, or resource here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Also, ideas for more categories, and suggestions on where various plugins should be placed [are needed](https://github.com/chasegiunta/awesome-craft/issues/2)! Thank you to all contributors; you rock!

### Contents
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Articles](#articles)
  - [Technical](#technical)
  - [Why Craft? (Praises)](#why-craft-praises)
- [Plugins](#plugins)
  - [SEO](#seo)
  - [Field Types](#field-types)
  - [Control Panel](#control-panel)
  - [Data](#data)
  - [Forms](#forms)
  - [Images](#images)
  - [Navigation](#navigation)
  - [Integrations](#integrations)
    - [Social](#social)
  - [Twig](#twig)
  - [Social](#social-1)
  - [Cache](#cache)
  - [Development](#development)
      - [Build Process](#build-process)
      - [Debugging](#debugging)
      - [Fields](#fields)
      - [Maintenance](#maintenance)
      - [Etc.](#etc)
  - [Security](#security)
  - [Misc](#misc)
  - [Commerce](#commerce)
- [Development Tools/Resources](#development-toolsresources)
- [Community](#community)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Articles
### Technical
- [9 Tips For Speeding Up Your Imager Transforms](https://www.vaersaagod.no/en/9-tips-for-speeding-up-your-imager-transforms-in-craftcms) by André Elvan/Værsågod
- [Building Complex Queries by Extending the ElementCriteriaModel](https://blog.tighten.co/craft-cms-building-complex-queries-by-extending-the-elementcriteriamodel) by Tighten Co
- [Craft CMS AJAX Page Transitions with history.pushState](https://designbycosmic.com/articles/development/craft-cms-ajax-page-transitions-with-history-pushstate) by Cosmic
- [Craft CMS Content Builder: The Client Experience](https://designbycosmic.com/articles/development/craft-cms-content-builder-the-client-experience) by Cosmic
- [DRY Templating with Twig and Craft CMS](https://medium.com/base-voices/dry-templating-with-twig-and-craft-cms-543292d114aa) by Pierre Stoffe/Base Digital
- [Deploying CraftCMS to Digital Ocean](https://www.jonathankelley.design/blog/deploying-craftcms-to-digital-ocean) by Jonathan Kelley
- [Editing a Front End Form with Matrix](https://caffeinecreations.ca/blog/editing-a-front-end-form-with-matrix/) by Sean Smith/Caffeine Creations
- [Getting Started with CraftCMS](https://www.jonathankelley.design/blog/getting-started-with-craftcms) by Jonathan Kelley
- [How I Automate My Local Development Craft CMS 2.x Installs](https://medium.com/@timknight/how-i-automate-my-craft-cms-2-x-installs-8427f70914e4) by Tim Knight
- [Large websites and performance in Craft CMS](http://madebyshape.co.uk/web-design-blog/large-websites-and-performance-in-craft-cms) by MadeByShape
- [Localization & Multi-Environment Setup in Craft.](https://designkarma.co.uk/blog/localization-multi-environment-setup-in-craft) by Ian Ebden/Design Karma
- [Multi-attribute variant selection in Craft Commerce](https://www.vaersaagod.no/en/multi-attribute-variant-selection-in-craft-commerce) by André Elvan/Værsågod
- [Quick Tips: Craft CMS](http://gregorterrill.com/blog/2017/quick-tips-craft-cms) by Gregor Terrill
- [Responsive Images with srcset & Craft](https://www.viget.com/articles/responsive-images-with-srcset-craft) by Trevor Davis/Viget
- [Support for Imgix in Imager for Craft](https://www.vaersaagod.no/en/support-for-imgix-in-imager-for-craftcms) by André Elvan/Værsågod
- [The Living Component Library](https://clearleft.com/posts/443) by Graham Smith/Clearleft
- [Thoughts on full page caching in Craft](https://angell.io/blog/thoughts-on-full-page-caching-in-craft) by Josh Angell
#### Articles by Andrew Welch @ [nystudio107](https://nystudio107.com/blog)
- [A/B Split Testing with Nginx & Craft CMS](https://nystudio107.com/blog/a-b-split-testing-with-nginx-craft-cms)
- [Creating Optimized Images in Craft CMS](https://nystudio107.com/blog/creating-optimized-images-in-craft-cms)
- [Creating a Content Builder in Craft CMS](https://nystudio107.com/blog/creating-a-content-builder-in-craft-cms)
- [Database & Asset Syncing Between Environments in Craft CMS](https://nystudio107.com/blog/database-asset-syncing-between-environments-in-craft-cms)
- [Google AMP: Should You Care?](https://nystudio107.com/blog/google-amp-should-you-care)
- [Handling Errors Gracefully in Craft CMS](https://nystudio107.com/blog/handling-errors-gracefully-in-craft-cms)
- [Hardening Craft CMS Permissions](https://nystudio107.com/blog/hardening-craft-cms-permissions)
- [Lazy Loading with the Element API & VueJS](https://nystudio107.com/blog/lazy-loading-with-the-element-api-vuejs)
- [Multi-Environment Config for Craft CMS](https://nystudio107.com/blog/multi-environment-config-for-craft-cms)
- [Setting up a New Craft CMS 3 Project](https://nystudio107.com/blog/setting-up-a-craft-cms-3-project)
- [Simple Static Asset Versioning in Craft CMS](https://nystudio107.com/blog/simple-static-asset-versioning)
- [Speed up your Craft CMS Templates with Eager Loading](https://nystudio107.com/blog/speed-up-your-craft-cms-templates-with-eager-loading)
- [Static Page Caching with Craft CMS](https://nystudio107.com/blog/static-caching-with-craft-cms)
- [The Case of the Missing PHP Session](https://nystudio107.com/blog/the-case-of-the-missing-php-session)
- [The Craft {% cache %} Tag In-Depth](https://nystudio107.com/blog/the-craft-cache-tag-in-depth)
- [Twig Processing Order & Scope](https://nystudio107.com/blog/twig-processing-order-and-scope)

### Why Craft? (Praises)
- [10 Reasons Why We Love Craft CMS](http://taechogroup.com/blog/10-reasons-why-we-love-craft-cms) by Taecho Group
- [A Review of Craft Commerce](http://www.newmediacampaigns.com/blog/a-review-of-craft-commerce) by New Media Campaigns
- [A love letter to Craft CMS](https://medium.com/diesdas-direct/a-love-letter-to-craft-cms-737f60d756cc) by Harry Keller/diesdas.digital
- [An Overview of Pixel & Tonic’s Craft CMS.](https://medium.com/@msoyka91/an-overview-of-pixel-tonics-craft-cms-4bd9d5768ed0) by Matthew Soyka
- [Crazy About Craft](http://www.newmediacampaigns.com/blog/review-of-craft-cms-tips-to-get-started) by New Media Campaigns
- [How we chose Craft CMS for our product websites](https://wildbit.com/blog/2016/11/01/how-we-chose-craft-cms-for-products-websites) by Eugene Fedorenko/Wildbit
- [Why Content Managers Love Craft CMS](https://weareabstrakt.com/blog/2017/why-content-managers-love-craft-cms/) by WeAreAbstrakt
- [Why Content Writers Love Craft CMS](https://caffeinecreations.ca/why-content-writers-love-craft-cms/) by Caffeine Creations
- [Why Craft CMS is the best content management system we (and you) have ever used](https://www.ten4design.co.uk/insight/why-craft-cms-is-the-best-content-management-system) by Ten4 Design
- [Why We Love Craft CMS](https://www.viget.com/articles/why-we-love-craft-cms) by Trevor Davis/Viget
- [Why We Use Craft CMS](https://designbycosmic.com/articles/development/why-we-use-craft-cms) by Cosmic
- [Why We Use Craft CMS](https://builtbymasonry.com/journal/why-we-use-craft-cms) by Masonry
- [Why We've Fallen Head Over Heels for Craft CMS](https://welfordmedia.co.uk/blog/design-development/we-love-craft-cms) by Welford Media
- [Why we develop websites using Craft CMS instead of Wordpress](https://weareabstrakt.com/blog/2017/why-we-develop-websites-using-craft-cms-instead-of-wordpress/) by WeAreAbstrakt
- [Why you should be considering Craft over WordPress](http://madebykind.com/thinking/why-you-should-be-considering-craft-over-wordpress) by Sam Goddard/Kind

## Plugins


### SEO
- [SEOmatic](https://github.com/nystudio107/seomatic) - Turnkey SEO implementation for Craft CMS that is comprehensive,Structured Data,and Social Sharing.
- [SEO](https://github.com/ethercreative/seo) - Search engine optimization utilities for Craft CMS.
- [Sitemap](https://www.putyourlightson.net/craft-sitemap) - Automatically creates a dynamic XML sitemap of your entire site and informs search engines exactly which pages on your site are available for crawling.
- [Retour](https://github.com/nystudio107/retour) - Intelligently redirect legacy URLs,and flexible.
- [Sprout SEO](https://sprout.barrelstrengthdesign.com/craft-plugins/seo) - Provides a seamless way to manage SEO strategy within Craft CMS. Create metadata for Search,powerful,so that you don't lose SEO value when rebuilding & restructuring a website.

### Calendar
- [Calendar](https://solspace.com/craft/calendar) - Create full-featured calendars and recurring events with exceptions.
- [Craft Calendars](https://topshelfcraft.com/calendars/introduction) - Easy-to-use, powerful-as-balls events Calendar for Craft. Any Element can be an event.
- [Venti2](https://venticalendar.io/) - Easily create unlimited event calendars, manage recurring event schedules, output multiple views and much more.


### Field Types
- [Button Box](https://github.com/supercool/buttonbox) - Collection of utility field types (Buttons, Colors, Text Size, Stars, Width, and Triggers).
- [Color Swatches](https://github.com/vigetlabs/craft-color-swatches) - Choose a color from a selection of admin defined colors.
- [Doxter](https://github.com/selvinortiz/craft.doxter) - Markdown editor and parser.
- [Hue](https://github.com/TopShelfCraft/Hue) - Slightly better color picker.
- [LJ Dynamic Fields](https://github.com/lewisjenkins/craft-lj-dynamicfields) - Simple plugin for populating fields with dynamic data.
- [LinkIt](https://github.com/fruitstudios/LinkIt) - Multi-purpose link plugin for Craft CMS.
- [Neo](https://github.com/benjamminf/craft-neo) - Matrix-like field type that uses existing fields.
- [Preparse Field](https://github.com/aelvan/Preparse-Field-Craft) - Field type that parses twig when the element is saved. Can be used for all kinds of optimizations.
- [Randomm](https://superbig.co/plugins/randomm) - Allows you to create random things via chance.js .
- [Reasons](https://github.com/mmikkel/Reasons-Craft) - Add conditionals to your field layouts.
- [Simple Map](https://github.com/ethercreative/simplemap) - Google Map field type with full localization support, compatible with Matrix, supports searching by location and sorting by distance.
- [SmartMap](https://www.doublesecretagency.com/plugins/smart-map) - Easily manage geographic points, calculate latitude & longitude, display locations on map, and more.
- [Sprout Fields](https://sprout.barrelstrengthdesign.com/craft-plugins/fields) - Email Addresses, Links, and Phone Numbers, Hidden and Invisible values, Notes, and more.
- [Store Hours](https://github.com/craftcms/store-hours) - Adds a new “Store Hours” field type to Craft, for collecting the opening and closing hours of a business for each day of the week. ![P&T](https://cdn.rawgit.com/chasegiunta/awesome-craft/master/pt.png)
- [SuperTable](https://github.com/verbb/SuperTable) - Create powerful tables utilising native Craft field types, including Assets, Users, Entries and even Matrix.
- [Template Select](https://superbig.co/plugins/template-select) - Lets you select templates from your entry.
- [VZ Address](https://github.com/elivz/VzAddress-Craft) - Simple address field.


### Control Panel
- [amcommand](https://github.com/am-impact/amcommand) - Command palette in Craft.
- [CPCSS](https://github.com/lindseydiloreto/craft-cpcss) - Easily overwrite the default Control Panel styles that ship with Craft.
- [CPNav](https://github.com/verbb/CPNav) - Manage your Control Panel navigation.
- [Content Stats](https://github.com/wbrowar/contentstats) - Dashboard widget to see how many entries have been created for channels and structures.
- [Expanded Singles](https://github.com/verbb/ExpandedSingles) - Alters the Entries Index sidebar to list all Singles, rather than grouping them under a 'Singles' link.
- [Matrix Colors](https://github.com/lindseydiloreto/craft-matrixcolors) - Easily identify your matrix blocks, by assigning a different color for each block type.
- [Sprout Notes](https://sprout.barrelstrengthdesign.com/craft-plugins/notes) - Add notes to your dashboard. Customize your note's header, body, and even use custom HTML.
- [Workflow](https://github.com/verbb/Workflow) - Plugin to create a workflow for publishing entries.


### Data
- [ArtVandelay](https://github.com/xodigital/ArtVandelay) - Importing and exporting fields.
- [Beam](https://superbig.co/plugins/beam) - Generate CSV and XLS files in your templates.
- [Craft Dump](https://github.com/putyourlightson/craft-dump) - Simple way to create DB backups.
- [Element API](https://github.com/craftcms/element-api) - Create a JSON API/Feed for your elements. ![P&T](https://cdn.rawgit.com/chasegiunta/awesome-craft/master/pt.png)
- [FeedMe](https://github.com/verbb/FeedMe) - Import entries and entry data from XML, RSS or ATOM feeds, setup as a task, or called on-demand in twig templates.
- [Import](https://github.com/boboldehampsink/import/tree/master) - Import data from CSV files.
- [Out](https://github.com/ethercreative/out) - Super-simple plugin for creating CSV exports of you entry data.
- [Reports](https://superbig.co/plugins/reports) - Write reports with Twig.
- [Sprout Import](https://sprout.barrelstrengthdesign.com/craft-plugins/import) - Import, migrate, seed, and weed content and settings into Craft CMS, Craft Commerce, the Sprout Plugin Suite, and add your own custom integrations.
- [Sprout Reports](https://sprout.barrelstrengthdesign.com/craft-plugins/reports) - Customize, save, and run the reports you need to manage your business. Export all of your website data and custom reports in CSV format.
- [The Architect](https://github.com/Pennebaker/craftcms-thearchitect) - Construct Groups, Fields, Sections, EntryTypes, Transforms, Globals, Assets, Categories, and Users & User Groups from JSON data


### Forms
- [amforms](https://github.com/am-impact/amforms) - Forms in Craft, made easy.
- [Contact Form](https://github.com/craftcms/contact-form/tree/v1) - Add a simple contact form to your site. ![P&T](https://cdn.rawgit.com/chasegiunta/awesome-craft/master/pt.png)
- [FormBuilder 2](https://github.com/roundhouse/FormBuilder-2-Craft-CMS) - Create & manage forms for your front-end. Entries get stored to database so you can easily view your submission or export them.
- [Formerly](https://github.com/xodigital/Formerly) - Create custom forms.
- [Freeform](https://solspace.com/craft/freeform) - Gives you full control to create simple or complex multi-page forms, and has options for many different API integrations.
- [Simple Mailer](https://github.com/tjdraper/simple-mailer-craft) - Easily create and submit forms using Craft’s native email setup.
- [SimpleMailer](https://buzzingpixel.com/software/simple-mailer-craft) - Easily create and submit forms in Craft using Craft’s native email setup.
- [Sprout Forms](https://sprout.barrelstrengthdesign.com/craft-plugins/forms) - Create and manage multiple forms. Save submitted form data, receive notification emails on submissions.


### Images
- [Ansel](https://buzzingpixel.com/software/ansel-craft) - Define image fields with minimum and/or maximum requirements, aspect ratios, minimum/maximum number of images, and more.
- [donkeytail](https://github.com/simplygoodwork/donkeytail-plugin) - Quickly and easily content manage points on images, locations on a faux map, or showcasing multiple products within an image.
- [Focal Point Field](https://github.com/aelvan/FocalPointField-Craft) - Choose focal point for your assets.
- [FocusPoint](https://github.com/smcyr/Craft-FocusPoint) - Choose coordinates on an image for the focus point on responsive images.
- [ImageResizer](https://github.com/verbb/ImageResizer) - Resize images on upload.
- [Imager Pretransform](https://superbig.co/plugins/imager-pretransform) - Pretransform any Assets on save, with Imager.
- [Imager](https://github.com/aelvan/Imager-Craft) - Image transforms gone wild.
- [TinyImage](https://craftpl.us/plugins/tiny-image) - Provide a clean and easy to use interface for clients to compress their images using the TinyPNG API.


### Navigation
- [a&m nav](https://github.com/am-impact/amnav) - Navigations in Craft, made easy.
- [Navee](https://github.com/fromtheoutfit/navee) - Simple Navigation, Made Simple. Build any kind of navigation you like, without limitation.


### Integrations
- [Analytics](https://dukt.net/analytics) - Customizable statistics widgets and entry tracking for Google Analytics.
- [Drift](https://superbig.co/plugins/drift) - Integrate Drift.com. Helps your team generate more leads and book meetings faster using messaging.
- [Embedly](https://superbig.co/plugins/embedly) - Use Embed.ly to fetch information and embed content from 250+ services.
- [Facebook](https://dukt.net/facebook) - Facebook Insights widget for the dashboard.
- [Imgix](https://superbig.co/plugins/imgix) - Use Imgix.
- [Instant Analytics](https://github.com/nystudio107/instantanalytics) - Brings full Google Analytics support to your Twig templates and automatic Craft Commerce integration with Google Enhanced Ecommerce.
- [MailChimp Subscribe](https://github.com/aelvan/mailchimp-subscribe-craft) - Simple Craft plugin for subscribing to MailChimp lists.
- [Pushover](https://superbig.co/plugins/pushover) - Send messages to Pushover.
- [ShareCount](https://superbig.co/plugins/sharedcount) - Use SharedCount.com to fetch statistics about shares/likes from multiple services in one call.
- [Shopify Multipass](https://superbig.co/plugins/shopify-multipass) - Allow a Craft user to be logged in to Shopify through Multipass.
- [Slack Notifications](https://superbig.co/plugins/slack-notifications) - Send notifications to Slack when someone places an order, a entry is created, or something else happens.
- [Splash](https://github.com/ethercreative/splash) - Quickly and easily get beautiful Unsplash images in Craft.
- [Splashing Images](https://github.com/studioespresso/craft-unsplash) - Brings amazing photos to your fingertips with Unsplash integration.
- [Twitter](https://dukt.net/twitter) - Tweet field, search widget, and authenticated Twitter API requests.
- [Uptime Robot](https://superbig.co/plugins/uptime-robot) - Integrates with Uptime Robot to monitor the health of your Craft site.

#### Social
- [Chatra](https://superbig.co/plugins/chatra) - Integrate Chatra easily. Powerful live chat software that helps to increase revenue and collect feedback.
- [Crisp](https://superbig.co/plugins/crisp) - Integrate Crisp.im Free and beautiful livechat to interact with your customers.
- [Discourse SSO](https://superbig.co/plugins/discourse-sso) - Single Sign-On for Discourse.
- [Disqus](https://github.com/nystudio107/disqus) - Integrate the Disqus commenting system including Single Sign On (SSO) and custom login/logout URLs.
- [Embedder](https://github.com/A-P/Embedder) - Generate the exact, most up-to-date YouTube, Vimeo, Wistia, or Viddler embed code available.
- [Olark](https://superbig.co/plugins/olark) - Integrate Olark. Live chat to answer customers immediately on your website.
- [Social Login](https://dukt.net/social) - Let your visitors log in & register with web services like Facebook, Google, Twitter.
- [Videos](https://dukt.net/videos) - Connect to YouTube & Vimeo and publish social videos on your website.


### Twig
- [Fetch](https://github.com/netliferesearch/craft-fetch) - Relays PHP's `file_get_contents()` to return contents in raw format. Useful for embedding external svg code inline.
- [Filter Environment Variables](https://github.com/lindseydiloreto/craft-filterenvvar) - Replace environment variable strings in your Twig variables.
- [Hacksaw](https://github.com/ehousestudio/craft_hacksaw) - Simple text truncation. Strips the HTML and limits the excerpts by character count, word count, or cutoff marker.
- [Image Color](https://github.com/familiar-studio/craft-image-color) - Grabs the most prominate colors from any image asset using a twig filter on an assets object.
- [Inflect](https://github.com/lukeholder/craft-inflect) - Several Twig filters to transform the inflection of strings.
- [PathTools](https://github.com/nystudio107/pathtools) - Brings convenient path & url manipulation functions & filters to your Twig templates.
- [RetconHTML](https://github.com/mmikkel/RetconHTML-Craft) - Collection of Twig filters for rewriting HTML content.
- [Similar](https://github.com/aelvan/Similar-Craft) - Queries similar elements based on elements they are related to.
- [Sprout Active](https://sprout.barrelstrengthdesign.com/craft-plugins/active) - Easily manage active states and conditional content based on your selected URL segments.

### Social
- [Comments](https://github.com/verbb/Comments) - Allows your Craft users to comment on elements. Manage comments within CMS.
- [Social Poster](https://github.com/verbb/SocialPoster) - Automatically post entries to social media.
- [UpVote](https://www.doublesecretagency.com/plugins/upvote) - Gives you the ability to upvote,any element type can be rated.
- [Sprout Lists](https://sprout.barrelstrengthdesign.com/craft-plugins/lists) - Allow users to subscribe to,downvote,follow,or "Like" on any element.
- [Star Ratings](https://www.doublesecretagency.com/plugins/star-ratings) - Elegant ratings system. Secure and easily configurable,or like any Element. Display counts and related content.


### Cache
- [Cache Buster](https://github.com/focuslabllc/craftcms-cachebuster) - Keep your front-end assets free of cache issues after they've changed.
- [Cache Warmer](https://superbig.co/plugins/cache-warmer) - Warm up your cache with a single request.
- [CacheFlag](https://github.com/mmikkel/CacheFlag-Craft) - Provides an alternative way to have your caches clear automatically when your content changes.
- [CacheMonster](https://github.com/supercool/Cache-Monster) - Keeps your cache permanently warm and optionally integrates with Varnish.
- [Cloudfront Invalidation](https://superbig.co/plugins/cloudfront-invalidation) - Invalidate your cached assets on CloudFront.
- [HTML Cache](https://github.com/craftapi/htmlcache) - Generate static HTML files for your website. No need for Reddis/Varnish setups anymore.
- [No-Cache](https://github.com/benjamminf/craft-nocache) - Extension to escape caching inside cache blocks.
- [Presto](https://github.com/caddis/craft-presto) - Static file extension for the native Craft cache.
- [Upper](https://github.com/ostark/upper) - Speeds up Craft dramatically using a Cache Proxy in front of your webserver.
- [Varnish Purge](https://github.com/aelvan/VarnishPurge-Craft) - Granular purging of Varnish cached content.


### Development
##### Build Process
- [Minify](https://github.com/nystudio107/minify) - Minify blocks of HTML,CSS,and JS inline.
- [Minimee](https://github.com/johndwells/craft.minimee) - Minimize,and even external ones. 
- [Stamp](https://github.com/aelvan/Stamp-Craft) - Add timestamps to your assets in a variety of ways; as a query string,but works with files outside your template path,combine & cache your CSS and JS files.
- [Asset Rev](https://github.com/clubstudioltd/craft-asset-rev) - Cache-bust your assets by appending query string or swapping out asset file names with their revved version.
- [Inlin](https://github.com/aelvan/Inlin-Craft) - Inline files in your Twig templates. Similar to Twig's `source()` function,og as a path segment.,part of the filename

##### Debugging
- [Bugsnag](https://superbig.co/plugins/bugsnag) - Log Craft errors/exceptions to Bugsnag.
- [Inspector](https://github.com/amacneil/craft-inspector) - Adds a helpful `inspect` method to your templates - figure out what kind of variables you are dealing with, and what methods they implement.
- [Kint](https://github.com/mildlygeeky/craft_kint) - In-app PHP debugger for use in Twig and PHP.
- [Query Log](https://github.com/rsanchez/craft-query-log) - Show a log of database queries in your front-end templates.
- [Query](https://github.com/craftcms/query/tree/v1) - Enables admins to run SQL queries from the CP. ![P&T](https://cdn.rawgit.com/chasegiunta/awesome-craft/master/pt.png)

##### Fields
- [Cheat Sheet](https://github.com/focuslabllc/craft-cheat-sheet) - Fast and customized set of instantly usable Field code samples.
- [Field Manager](https://github.com/verbb/FieldManager) - Makes it easy to manage fields and field groups.
- [Inventory](https://github.com/lindseydiloreto/craft-inventory) - Take stock of how your fields are being used.

##### Maintenance
- [404 Finder](https://craftpl.us/plugins/404-finder) - Keeps a running tally of pages users are currently trying to access but can't.
- [GTmetrix](https://github.com/lukeyouell/craft-GTmetrix) - Gives insight on how well your entries load and provides recommendations to optimize.
- [Maintenance](https://github.com/carlcs/craft-maintenance) - Provides tools to help you do maintenance on your website.
- [Patrol](https://github.com/selvinortiz/craft.patrol) - Simplifies SSL and maintenance routing.

##### Etc.
- [Admin Bar](https://github.com/wbrowar/adminbar) - Front-end shortcuts for clients logged in.
- [CraftQL](https://github.com/markhuot/craftql) - A drop-in GraphQL server allowing access to all features.
- [Environment Label](https://github.com/madebykind/craft.labelenvironment) - Nice coloured labels in the CP to help distinguish your environments.
- [Faker](https://superbig.co/plugins/faker) - Output random fake data in your templates.
- [Migration Manager](https://github.com/Firstborn/Craft-CMS-Migration-Manager) - Create migrations to easily move settings and content between site installations
- [User Creator](https://superbig.co/plugins/user-creator) - Allow you to generate users en masse, simply.
 
 
### Security
- [CrawlerDetect](https://superbig.co/plugins/crawlerdetect) - Detect 1.000's of bots/crawlers/spiders.
- [Digital Download](https://www.doublesecretagency.com/plugins/digital-download) - Provide secure digital download links to your files. Set the expiration date, maximum number of downloads, and/or required user access.
- [Exclusive](https://craftpl.us/plugins/exclusive) - Allow limited and selected public registration on your website by generating and distributing unique registration tokens.
- [Internal Assets](https://github.com/tikiatua/internal-assets-plugin) - Restrict access to assets for permitted users only.
- [Restrict](https://superbig.co/plugins/restrict) - Restrict access to the CP based on a IP whitelist.
- [Sherlock](https://www.putyourlightson.net/craft-sherlock) - Security scanner and monitor to keep your site and CMS secure.
- [Snaptcha](https://www.putyourlightson.net/craft-snaptcha) - Invisible captcha that automatically validates your forms on submission.
- [Sprout Encode Email](https://sprout.barrelstrengthdesign.com/craft-plugins/encode-email) - Encode the email addresses in your templates so they can't be harvested by evil spam bots.
- [Sprout Invisible Captcha](https://sprout.barrelstrengthdesign.com/craft-plugins/invisible-captcha) - Protect your forms from spam using unobtrusive invisible captchas.


### Misc
- [AdWizard](https://www.doublesecretagency.com/plugins/ad-wizard) - Easily manage custom advertisements on your website.
- [Anchors](https://github.com/craftcms/anchors) - Add anchor links to headings in your website content. ![P&T](https://cdn.rawgit.com/chasegiunta/awesome-craft/master/pt.png)
- [Boris](https://github.com/webdna/boris) - Make your entries invincible! Protect them from being deleted.
- [Cookies](https://github.com/nystudio107/cookies) - Simple plugin for setting and getting secure cookies from within templates.
- [Country Redirect](https://superbig.co/plugins/country-redirect) - Easily redirect visitors to a locale based on their country of origin.
- [Craft Help](https://github.com/70kft/craft-help) - Allows developers to provide CMS documentation to their clients directly inside the control panel.
- [Craft User Manual](https://github.com/hillholliday/Craft-User-Manual) - Allows developers or content editors to provide CMS documentation using sections to create a "User Manual" or "Help" section in the control panel.
- [Eager Beaver](https://github.com/nystudio107/eagerbeaver) - Eager load elements from auto-injected Entry elements on demand
- [LJ Cookies](https://github.com/lewisjenkins/craft-lj-cookies) - Simple plugin for setting and retrieving cookies from within templates.
- [Language Link](https://github.com/lindseydiloreto/craft-languagelink) - Easily switch between languages on any page of your website.
- [Large Upload](https://superbig.co/plugins/large-upload) - Makes it easy & safe to upload large files without any hassles like changing server settings and the risk of DDoS attacks.
- [Printmaker](https://craftpl.us/plugins/printmaker) - Template-based HTML-to-PDF engine: Save or output a PDF from any template, URL, or string.
- [Rich Variables](https://github.com/nystudio107/richvariables) - Allows you to easily use Globals as variables in Rich Text fields.
- [Scraper](https://craftpl.us/plugins/scraper) - Fetch HTML from any URL and manipulate it in your Twig templates.
- [Task Manager](https://github.com/boboldehampsink/taskmanager) - Adds a "Task Manager" section to your CP to easily cancel or delete Craft Tasks.
 
 
### Commerce
_(Forthcoming)_

----
Updated list of Craft 3 plugins can be found at [plugins.craftcms.com](https://plugins.craftcms.com).

----

## Development Tools/Resources
- [Crafty Vagrant](https://github.com/niceandserious/crafty-vagrant) - Boilerplate dev environment for jump-starting projects with Vagrant configured, Gulp configured, and more.
- [craft-cli](https://github.com/rsanchez/craft-cli) - Command line interface for Craft CMS.
- [craft-multi-environment](https://github.com/nystudio107/craft-multi-environment) - Efficient and flexible multi-environment config.
- [craft-scripts](https://github.com/nystudio107/craft-scripts) - Shell scripts to manage database backups, asset backups, file permissions, asset syncing, cache clearing, and database syncing between Craft CMS environments.
- [craftman](https://github.com/gabrielmoreira/craftman) - To help speed set up and start a new Craft CMS installation smoothly.
- [generator-craftinstall](https://github.com/nystudio107/generator-craftinstall) - Yeoman generator for Craft CMS installs.
- [nginx-craft](https://github.com/nystudio107/nginx-craft) - Nginx virtual host configuration for Craft CMS that implements a number of best-practices.
- [pluginfactory.io](https://pluginfactory.io/) - Generate Craft CMS plugin code scaffolding that conforms to P&T’s Coding Standards, creating the bits you need to get your plugins started.


## Community
- [`@CraftCMS` on Twitter](https://twitter.com/craftcms) - Follow the conversation, official community hashtag is `#craftcms`.
- [Craft CMS StackExchange](https://craftcms.stackexchange.com/) - Q&A for administrators, end users, developers and designers.
- [Craft Cookbook](https://craftcookbook.net/) - Quick solutions to common Craft CMS problems.
- [Craft Link List](http://craftlinklist.com/) - Curated publication collecting interesting links.
- [Craft Slack](https://craftcms.com/community#slack) - Nearing 5,000 users, join the Slack group dedicated to Craft CMS discussion.
- [CraftX](https://craftx.io/) - Open source site built on Craft 3, and community of web professionals hosting hangouts.
- [Mijingo](https://mijingo.com/products/screencasts/up-and-running-with-craft/) - Video courses for learning Craft.
- [Official Facebook](https://www.facebook.com/craftcms/) - Like the official Craft CMS Facebook page.
- [Straight Up Craft](http://straightupcraft.com/) - Tutorials, plugin directory, event listings & more.
- [Work With Craft](https://www.workwithcraft.com/) - Dedicated job board aimed to connect employers with Craft professionals.
