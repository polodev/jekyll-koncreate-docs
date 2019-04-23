---
title: Special Tutorials
layout: post
page_id: special-tutorial
has_sub: true
number: 19
---

### 19.1| Setting up Contact Form

We are using plugin `Contact Form 7` for contact functionality. You can see their documentation for better understanding.

If you don't want to go through all the troubles to check their documentation and just want to use the default contact form we provided with this theme, **please at least set up the default emails in contact form settings. (Because if you don't do that, all form submission emails will come to us instead of you).** To do that, please follow the steps below:

_Step 1:_** Navigate to `Contact`, and then click on `Contact form 1` link.

<img alt="contact form 7" src="{{ 'assets/images/advance/contact-form-1.jpg' | relative_url }}">

_Step 2:_** From this page, click on `Mail` tab. Here you should set your own email address where you want to receive user submitted forms. Then click on save button.

<img alt="" src="{{ 'assets/images/advance/contact-form-2.jpg' | relative_url }}">

_Step 3:_**   Please submit some dummy forms from Contact page to make sure that it's working properly.


### 19.2| Translating Theme

You can translate this theme to another language easily. You actually have to translate two things for your website to work properly: `Koncreate` theme and `Koncreate Core` plugin. This plugin plays a major role in theme functionality, so if you don't translate this plugin along with the theme you can't be able to get the full translation.

There are many tools available for translation. But the easiest way is to use plugin `Loco Translate`. Using this plugin, you can literally translate any WordPress themes or plugins if it supports translation.

_Note: Please remember, if you update the theme later your translations might be gone if they are stored inside theme/plugin. So please keep a backup of **Koncreate** theme and **Koncreate Core** plugin first before updating theme._
{: .text-danger}



Here's a quick video tutorial about how to use **Loco Translate**:

{% youtube 3Fohy96uSzY %}


### 19.3| Updating Theme

Occationally we provide updates which includes new features and bugfixes. Updating WordPress theme is standard WordPress functionality. There are few ways to update WordPress theme. You can follow any of the methods described below:

**Note: Before updating, make sure to keep a backup of your website to be in safe side.**
{: .text-danger}

#### Method 1: Automatic Update by Using Envato Market Plugin

1. Install and activate the "Envato Market" plugin manually. Here's the plugin zip file: <a href="http://envato.github.io/wp-envato-market/dist/envato-market.zip">http://envato.github.io/wp-envato-market/dist/envato-market.zip</a>
2. From WordPress Admin Panel, navigate to **"Envato Market"** menu.
3. After completed the above steps successfully, Navigate to `Appearance > Themes`. Here you'll see an `Update now` link beside your theme. Click on that link and your theme will be updated automatically.

Here's a quick video tutorial explaining this method:

{% youtube  fhRFhXnuP1I %}


#### Method 2: By Uploading zip File
1. From WordPress Admin Panel, Navigate to `Appearance > Themes`.
1. Activate any other theme (eg. Twenty Seventeen) than the current one.
1. Delete `Koncreate` Theme.
1. Now you have to upload the updated theme zip file. To do this, Navigate to `Appearance > Themes > Add New > Upload`. Go to browse, and select the zipped theme folder. Hit "Install Now" and the theme will be uploaded and installed.

#### Method 3: By FTP
1. Using your FTP client, navigate to `/wp-content/themes/` folder on your server and delete the `Koncreate` folder from there.
1. Now upload the latest non-zipped theme folder into that `/wp-content/themes/` folder .
