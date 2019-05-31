---
title: Importing Demo contents
layout: post
page_id: demo
has_sub: true
number: 3
toc: true
---


Want to build your site like the demo? You can do it by only one click!

** Note: Before proceeding, please remember that when you are done with the demo import, all existing settings and contents will be removed and replaced by the demo contents. So it is highly recommended that you should only do this in fresh site.**
{: .text-danger}

### 3.1 | Auto Import

First please make sure that Koncrete Parent Theme is activated on your site.

From Admin menu, navigate to `Tools > Demo Content Install`. Or alternatively,  navigate to `Plugins > RT Demo Importer > Install Demo Contents`.

<img alt="" src="{{ 'assets/images/koncrete_theme/importing-demo-content/idc.1.jpg' | relative_url }}">

In this page, Click on the **Install** button for installing the demo.

<img alt="" src="{{ 'assets/images/koncrete_theme/importing-demo-content/idc.2.jpg' | relative_url }}">

It will take some time for importing the demo contents. *Please note: Some images are replaced with a placeholder image because of licensing.*

After importing demo data, please update your permalink. To update permalink, navigate to `Settings > Permalink` and then click on`Save Settings` button.

<img alt="" src="{{ 'assets/images/koncrete_theme/importing-demo-content/idc.3.jpg' | relative_url }}">

If you face any issue, check the Troubleshooting section from <a href="#t-demo">here</a>.

### 3.2 | Manual Import

We have provided some sample contents inside `sample-data` directory which comes with your theme package. You have to import those contents.

You will need to import 4 file  

1. `content.xml`
2. `widget.wie`
3. `slider.zip`
4. `options.json`

<strong>1. Importing `content.xml` </strong>

---

From Admin menu, navigate to `Tools > Import.` From there select the `WordPress` and then run the importer ( It will ask you to install the importer before if this is your first time ). In the next step when file uploading option appears, select the `content.xml` file from sample-data and start uploading. In next step select the checkbox saying `Download and import file attachments` and click on `Submit`. Then it'll start uploading contents eg. pages, posts etc. 

<p> <img alt="" src="{{ 'assets/images/koncrete_theme/importing-demo-content/manual-demo-1.jpg' | relative_url }}"> </p>
<p> <img alt="" src="{{ 'assets/images/koncrete_theme/importing-demo-content/manual-demo-2.jpg' | relative_url }}"> </p>
<p> <img alt="" src="{{ 'assets/images/koncrete_theme/importing-demo-content/manual-demo-3.jpg' | relative_url }}"> </p>

<strong>2. Importing `widget.wie` </strong>

---

You can import widgets using plugin `Widget Importer & Exporter`. After installing this plugin, navigate to `Tools > Widget Importer & Exporter`. In the next step when file uploading option appears, select the `widgets.wie` file from `sample-data` and start importing.

<p> <img alt="" src="{{ 'assets/images/koncrete_theme/importing-demo-content/manual-demo-widget.jpg' | relative_url }}"> </p>   




<strong>3. Importing `slider.zip` </strong>

---

From Admin menu, navigate to `LayerSlider WP`, then click on `Import Sliders` option. In the next step when file uploading option appears, select the `slider.zip` file from `sample-data` and start importing.  

<p> <img alt="" src="{{ 'assets/images/koncrete_theme/importing-demo-content/manual-demo-slider-1.jpg' | relative_url }}"> </p>   
<p> <img alt="" src="{{ 'assets/images/koncrete_theme/importing-demo-content/manual-demo-slider-2.jpg' | relative_url }}"> </p>   


<strong>4. Importing `options.json` </strong>

---

First open the file `options.json` in any text editor and copy the whole contents. Now from Admin menu, navigate to `Appearance > Theme Options`, then go to `import/Export` tab. From there click on `Import from file` option. A textbox will appear, paste the copied contents on that textbox and click on `Import` button.


<p> <img alt="" src="{{ 'assets/images/koncrete_theme/importing-demo-content/manual-demo-options.jpg' | relative_url }}"> </p>   
