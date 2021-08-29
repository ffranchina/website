+++
categories = ["Releases"]
tags = ["Releases"]
title = "BookStack Release v21.08"
date = 2021-08-30T21:05:23Z
author = "Dan Brown"
image = "/images/blog-cover-images/lighthouse-dimitry_b.jpg"
slug = "bookstack-release-v21-08"
draft = false
+++

Today we release BookStack v21.08, which brings along mulit-factor authentication support in addition to a
number of other nice features. Within this post we'll dive into some of the biggest new changes since the v21.05 release.

* [Update instructions](https://www.bookstackapp.com/docs/admin/updates)
* [GitHub release page](https://github.com/BookStackApp/BookStack/releases/tag/v21.08)


Important Notes


### Multi-Factor Authentication



### Markdown Export



### Role Export Permissions



### Upload Images in Page Content via API



### "Skip to content" Accessibility Link



### Non-Download Attachment Links



### Translations



### Full List of Changes

**Released in v21.08**

* Added mulit-factor authentication system. ([#2827](https://github.com/BookStackApp/BookStack/pull/2827), [#1118](https://github.com/BookStackApp/BookStack/issues/1118))
* Added the ability to export content as Markdown. Thanks to [@nikhiljha](https://github.com/BookStackApp/BookStack/pull/2115). ([#2115](https://github.com/BookStackApp/BookStack/pull/2115), [#1717](https://github.com/BookStackApp/BookStack/issues/1717))
* Added role permissions for exporting content. ([#2899](https://github.com/BookStackApp/BookStack/pull/2899), [#1251](https://github.com/BookStackApp/BookStack/issues/1251))
* Added an advisory notice on the shelf permissions page regarding the lack of cascade. ([#2876](https://github.com/BookStackApp/BookStack/issues/2876))
* Added Lithuanian language translations. Thanks to [@ffranchina](https://github.com/BookStackApp/BookStack/pull/2868). ([#2868](https://github.com/BookStackApp/BookStack/pull/2868))
* Added item parent link in recycle bin restore to make parent item restore easier. Thanks to [@arjvand](https://github.com/BookStackApp/BookStack/pull/2682). ([#2682](https://github.com/BookStackApp/BookStack/pull/2682), [#2594](https://github.com/BookStackApp/BookStack/issues/2594))
* Added some core opengraph tags to content. Thanks to [@james-geiger](https://github.com/BookStackApp/BookStack/pull/2393). ([#2393](https://github.com/BookStackApp/BookStack/pull/2393), [#2348](https://github.com/BookStackApp/BookStack/issues/2348))
* Updated blade views to be more consistent and follow a documented convention. ([#2805](https://github.com/BookStackApp/BookStack/issues/2805))
* Fixed markdown blockquotes not rendering correctly in preview. ([#2858](https://github.com/BookStackApp/BookStack/issues/2858), [#2837](https://github.com/BookStackApp/BookStack/issues/2837))
* Fixed issue on API where page update removes HTML. ([#2856](https://github.com/BookStackApp/BookStack/issues/2856))
* Fixed inconsistency in list display and nesting. ([#2854](https://github.com/BookStackApp/BookStack/issues/2854))
* Standardised styling of the codebase. ([#2820](https://github.com/BookStackApp/BookStack/pull/2820))

**Released in v21.05.1 through v21.05.4**

* Added base64 image extraction within page content. Thanks to [@awarre](https://github.com/BookStackApp/BookStack/pull/2700). ([#2700](https://github.com/BookStackApp/BookStack/pull/2700), [#2631](https://github.com/BookStackApp/BookStack/issues/2631))
* Added Croatian translations. Thanks to [@ffranchina](https://github.com/BookStackApp/BookStack/pull/2784). ([#2784](https://github.com/BookStackApp/BookStack/pull/2784), [#2785](https://github.com/BookStackApp/BookStack/pull/2785))
* Added VB.NET code block highlighting option. ([#2869](https://github.com/BookStackApp/BookStack/issues/2869))
* Added a "Skip to content" link as first page focus item for accessibility use. ([#2810](https://github.com/BookStackApp/BookStack/issues/2810))
* Added the ability to serve attachments without forcing downloads. ([#2791](https://github.com/BookStackApp/BookStack/pull/2791))
* Updated item permission roles list to be sorted alphabetically. ([#2782](https://github.com/BookStackApp/BookStack/issues/2782))
* Updated social account detachment to have CSRF protection. ([#2808](https://github.com/BookStackApp/BookStack/issues/2808))
* Updated PHP dependency versions.
* Updated translations with latest changes from Crowdin. ([#2790](https://github.com/BookStackApp/BookStack/pull/2790))
* Merged in latest Crowdin translations. ([#2787](https://github.com/BookStackApp/BookStack/pull/2787), [#2777](https://github.com/BookStackApp/BookStack/pull/2777))
* Improved audit log user select list stability. ([#2863](https://github.com/BookStackApp/BookStack/issues/2863))
* Fixed incorrect styling of favourites sidebar when using a non-default homepage option. ([#2783](https://github.com/BookStackApp/BookStack/issues/2783))
* Fixed issue where empty HTML comments could cause errors. ([#2804](https://github.com/BookStackApp/BookStack/issues/2804))
* Extracted not found text into it's own view for easier overriding ([58117bc](https://github.com/BookStackApp/BookStack/commit/58117bcf2d91b72620de3e34b0daa705da519f5e))
* Fixed issue where translations system may attempt to load from the root directory when a theme was not in use. ([#2836](https://github.com/BookStackApp/BookStack/issues/2836))
* Fixed issue where user profile pages item "View All" links used ids hence did not link to proper searches. ([#2857](https://github.com/BookStackApp/BookStack/issues/2857))


### Next Steps

- Last release before leaving job
- Focus on Laravel 8 upgrade
- Spend some time on the little bits.

----

<span style="font-size: 0.8em;opacity:0.9;">Header Image Credits: <span>Photo by <a href="https://unsplash.com/@dimitry_b?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Dimitry B</a> on <a href="https://unsplash.com/?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span></span>