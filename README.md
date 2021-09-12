# notion-nginx-proxy-config
For when you want to publish notion on your own domain.

# Usage
Include this config file from your own nginx.conf!

You must change some settings.

* CHANGE_TO_YOUR_DOMAIN
  * your custom domain name
* /path/to/signed_cert_plus_intermediates
  * your domain's ssl certificate path
* /path/to/private_key
  * your domain's ssl certificate key path
* /path/to/dhparam
  * download [dhparam](https://ssl-config.mozilla.org/ffdhe2048.txt) and place it
* ${change_to_your_notion_public_page_root_path}
  * Make your notion page public, and copy your URL path.
* ${*****YOUR_GTM_ID*****}
  * your GTM IDString (GTM-${IDString})

