=== Cr3ativ Sponsor ===
Contributors: Cr3ativ
Tags: sponsors, events
Requires at least: 3.0.1
Tested up to: 4.0
Stable tag: 1.0.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Cr3ativ Sponsors plugin is created specifically for you to setup and display sponsors, via level of sponsorship on your WordPress powered website.


== Description ==

Easily add unlimited sponsorship levels and sponsors, along with company name, link, bio and logo for each sponsor. Display anywhere on your site using either the simple short code or via a widget. 

For your convenience, the plugin also contains a directory called language files, where you will find the mo/po files you may use for translation purposes.

<a href=“http://mythemepreviews.com/plugins/sponsors/”>View the demo</a>.


== Installation ==

1. Upload the `cr3ativ-sponsor` folder to your to the `/wp-content/plugins/` directory or alternatively upload the cr3ativ-sponsor.zip via the plugin page of WordPress by clicking 'Add New' and select the zip from your local computer.

2. Activate the plugin through the 'Plugins' menu in WordPress.

3. You will see a new post type on the left of the WP admin menu ’Sponsor’.

4. Under the ‘sponsor’ menu option, you will see ‘All Sponsors’, ‘Add New Sponsor’ and ‘Sponsor Levels’.  


== Creating a Single Sponsor Listing ==

1. Click ‘Add New Sponsor and enter all relevant information.  The title will be the Sponsor’s Name, the Featured Image would be sponsor’s logo, the content area would be the sponsor’s bio and the Company URL meta box would be the url to the sponsor’s website.

2. On the right of the screen you will see a new box named ‘Sponsor level’ - this is used to categorize your sponsorships easily - an example being Platinum, Gold, Silver etc basically levels in your event for sponsorships - either choose an existing sponsor level or create a new one for it to be assigned by clicking ‘+Add New Category’.

3. Click Publish.

4. Continue to add as many sponsors as you need.  You can use a short code (or the drag/drop widget) to display these on any post or page.


== Short Code ==

To display sponsors on any post or page using the text based short code, copy/paste this short code into the desired area and just change the information to what you want it to display.  For example:

[sponsor_level category="all" orderby="DESC" columns="4" image="yes" title="yes" link="yes" bio="yes"]

The above short code will display all sponsors in DESC order as a 4 column layout with the featured image, sponsor name and the content.  The featured image and sponsor name will be linked.

Here is what each part of that short code means:

sponsor_level - this is required to request the short code to work

category - this would be the sponsor level.  You would type in the ‘slug’ name of the sponsor level you created.  To determine the ‘slug’ name, click ‘Sponsor Level’ under the Sponsor menu option and you will see all the levels you have created, the level you would type in here is what is shown (exactly shown) in the ‘slug’ column.

orderby - type ‘ASC’ or ‘DESC’ to change how the order of the sponsors

columns - you can enter ‘1’, ‘2’, ‘3’ or ‘4’ here

image - enter ‘yes’ or ‘no’ to show the featured image

title - enter ‘yes or ‘no’ to show the sponsor name

link - enter ‘yes’ or ‘no’ to have the image and/or name linked with the url in the ‘Company URL’ field pulled from the sponsor page

bio - enter ‘yes’ or ‘no’ to display the content from the sponsor page


== Widget ==

The Cr3ativ Sponsor plugin comes not only with a useful widget to display sponsors by level or all levels as well as select what information you would like to have displayed:

Title - Title that will appear above the widget

Sorting Method - select ASC or DESC for your sorting options

Show sponsor logo? - If this is checked, the featured image set under the sponsor will show.

Show sponsor name? - If this is checked, the sponsor name will show.

Link logo and/or sponsor name? - If this is checked, the featured image and/or sponsor name will link to the company url entered from the sponsor page (in a new browser window).

Show sponsor bio? - If this is checked the content from the sponsor page will show.

Sponsor Level - Choose from the drop down what sponsor level you want to show or select ‘All’ to show all sponsors. 

Click Save.


== Screenshots ==

1. Sponsor admin view
2. Adding a new sponsor
3. Sponsor levels view (category)
4. Sponsor loop widget


== Styling ==

Styling for these page templates are included in the includes directory under :

/includes/css/cr3ativsponsor.css


== Changelog ==

= 1.0.0 =
* First release.

