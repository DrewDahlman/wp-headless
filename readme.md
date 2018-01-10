# WP Headless
A simple plugin for publishing static JSON files from Wordpress for a headless CMS.

## Install
- Download the repo
- Place in your plugins directory
- Activate
- Setup your AWS bucket information with Key and Secret in the aws plugin.
	- WP Headless uses those same credentials for uploading to s3.

## Requirements
- ACF Pro ( [Advanced Custom Fields Pro](https://www.advancedcustomfields.com/pro/) )
- AWS ( [Amazon Web Services](https://wordpress.org/plugins/amazon-web-services/) )
- WP Offload ( [Wordpress Offload Lite](https://wordpress.org/plugins/amazon-s3-and-cloudfront/) )

## Using
Once installed and all requirements are met, you will see a new menu item called Publish Site. There you will find:
	- About
	- Publish Staging
	- Publish Production
	- Content

Inside of content you can setup your content however you wish. When you create a new content group you give it a name and pick posts/pages/users/media - whatever you want to create a package out of. Once you've configured your content click "update" and then `publish staging` or `publish production`
