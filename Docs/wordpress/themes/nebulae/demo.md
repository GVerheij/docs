---
title: Nebulae: Recreating the Demo
description: Your Guide to Recreating Elements of the Nebulae Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/nebulae:Nebulae

---

Introduction
-----

![][nebulae2]

Recreating features of the demo site used to show off some of the more interesting aspects of Nebulae can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Nebulae theme.

Keep in mind that a lot of the detail that makes our demos look so good are the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Nebulae:

* [Gantry Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* [RokCommon Library](http://www.rockettheme.com/wordpress/plugins/rokutilities) (Should be Installed and Activated Before RokGallery and/or RokSprocket)
* [RokGallery][rokgallery]
* [RokSprocket][roksprocket]

All of these plugins are included with the Nebulae RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Nebulae demo sits apart from the rest of the page layouts in that it features the latest and greatest features used in the theme. It is because of this that several widget and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Nebulae theme.

Theme Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a setting override. This can be done by navigating to **Administrative Dashboard -> Nebulae Theme** and selecting the **+** icon located just above the **Style** settings tab.

It would be a good idea for organization to name this layout override something like **Front Page** as it would be used only for the front page of your site.

#### Assignments

The next step you will need to take in creating your Theme Settings override is to assign the Front Page override to the site's home page. Under the **Template Page Types** list, you will want to select both **Home Page** and **Front Page**. These settings can be found by navigating to **Assignments > Template Page Types** in the theme settings.

Doing this will assign the override to these two page types. This will allow the override to cover all access scenarios that would lead a user to your site's main home page.

>> Under the administrative area, you can check you site's home page settings by navigating to **Settings -> Reading** and making sure that **Your latest posts** is selected. This is the setting we use for the demo content's home page as it does not require the creation of a static page.

You can find more information about the entire override breakdown for both the front page and our default settings in the demo by visiting the [override portion][demooverride] of this tutorial.

Widget Settings
-----

![][Nebulae]

:   1. **Header - Gantry Logo** [8%, 16%, se]
    2. **Header - Gantry Menu** [8%, 40%, se]
    3. **Content Top - Text** [49%, 16%, se]
    4. **Footer - Text** [83%, 16%, se]
    5. **Footer - Text** [83%, 33%, se]
    6. **Footer - Text** [83%, 63%, se]
    7. **Copyright - Gantry Branding** [90%, 43%, se]

>> Any widgets not specifically pointed out above are likely left out due to the fact that they were created using legacy plugins and/or features of WordPress that are no longer supported.

Like any Gantry theme, Nebulae utilizes widget overrides to allow different widget placements for various areas of your WordPress site. This makes it possible to not only utilize the full power of the Gantry framework, but to make each area of your site uniquely suited to meet your user's needs.

Below, you will find the widget placement and settings for the various widget positions as they appear in the Front Page widget override. Not all of these positions were overwritten. Some positions (such as the Header section) are often set in the primary default widget setting.

One important thing to note here is that many of the widget sections included in our demo are split up using a **Gantry Divider** widget. This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section. You will see the Gantry Divider in any widget section breakdowns as they are included in the demo.

### Widget Sections

* [Header][header]
* [Content Top][contenttop]
* [Footer][footer]
* [Copyright][copyright]

[gantry]: http://gantry-framework.org/download
[rokajaxsearch]: http://www.rockettheme.com/wordpress/plugins/rokajaxsearch
[rokbox]: http://www.rockettheme.com/wordpress/plugins/rokbox
[roksprocket]: http://www.rockettheme.com/wordpress/plugins/roksprocket
[Nebulae]: assets/nebulae2.jpeg
[nebulae2]: assets/nebulae.jpeg
[roksprocket]: http://www.rockettheme.com/wordpress/plugins/roksprocket
[rokgallery]: http://www.rockettheme.com/wordpress/plugins/rokgallery
[faq]: faq.md
[override]: http://gantry-framework.org/documentation/wordpress/configure/
[navigation]: demo_navigation.md
[header]: demo_header.md
[feature]: demo_feature.md
[navigation]: demo_navigation.md
[maintop]: demo_maintop.md
[contenttop]: demo_contenttop.md
[post]: demo_post.md
[sidebar]: demo_sidebar.md
[mainbottom]: demo_mainbottom.md
[footer]: demo_footer.md
[copyright]: demo_copyright.md
[demooverride]: demo_override.md
