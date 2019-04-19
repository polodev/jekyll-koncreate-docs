---
title: Importing Demo contents
layout: post
unique_id: demo
has_sub: false
number: 3
toc: true
---
Want to build your site like the demo? You can do it by only one click!
<p style="color:red;">
	<b>
		** Note: Before proceeding, please remember that when you are done with the demo import, all existing settings and contents will be removed and replaced by the demo contents. So it is highly recommended that you should only do this in fresh site. **
	</b>
</p>  

### 3.1 | Auto Import

First please make sure that Koncreate Parent Theme is activated on your site.  

From Admin menu, navigate to `Tools > Demo Content Install`. Or alternatively,  navigate to `Plugins > RT Demo Importer > Install Demo Contents`.   

<img alt="" src="{{ 'assets/images/40.png' | relative_url }}">   

In this page, Click on the **Install** button for installing the demo.       

<img alt="" src="{{ 'assets/images/2.jpg' | relative_url }}">     

It will take some time for importing the demo contents. *Please note: Some images are replaced with a placeholder image because of licensing.*   

After importing demo data, please update your permalink. To update permalink, navigate to `Settings > Permalink` and then click on`Save Settings` button.  

<img alt="" src="{{ 'assets/images/r3.jpg' | relative_url }}">    

If you face any issue, check the Troubleshooting section from <a href="#t-demo">here</a>.     


### 3.2| Manual Import

We have provided some sample contents inside "sample-data" directory which comes with your theme package. You have to import those contents.   

* **Importing Contents**: From Admin menu, navigate to `Tools > Import`. From there select the `WordPress` and then run the importer(It will ask you to install the importer before if this is your first time). In the next step when file uploading option appears, select the `contents.xml` file from sample-data and start uploading. In next step select the checkbox saying "Download and import file attachments" and click on `Submit`. Then it'll start uploading contents eg. pages, posts etc.

<img src="{{ 'assets/images/78.jpg' | relative_url }}">

<img src="{{ 'assets/images/80.jpg' | relative_url }}">

<img src="{{ 'assets/images/81.jpg' | relative_url }}">

* **Importing Widgets**: You can import widgets using plugin <a href="https://wordpress.org/plugins/widget-importer-exporter/">Widget Importer & Exporter</a>. After installing this plugin, navigate to `Tools > Widget Importer &amp; Exporter`. In the next step when file uploading option appears, select the `widgets.wie` file from sample-data and start importing.

<img src="{{ 'assets/images/82.jpg' | relative_url }}">
* **Importing Sliders**: From Admin menu, navigate to `LayerSlider WP`, then click on `Import Sliders` option.
	In the next step when file uploading option appears, select the `slider.zip` file from sample-data and start importing.
	<img src="{{ 'assets/images/83.jpg' | relative_url }}">
	<img src="{{ 'assets/images/84.jpg' | relative_url }}">

* **Importing options**: First open the file `options.json` in any text editor and copy the whole contents.
  Now from Admin menu, navigate to `Appearance > Koncreate Options`, then go to `import/Export` tab.
  From there click on `Import from file` option.
  A textbox will appear, paste the copied contents on that textbox and click on "Import" button.
  <img src="{{ 'assets/images/2.jpg' | relative_url }}">


