# Create HTTP -> HTTPS redirect

## Setting up the site

Go to sites-enabled dir in nginx folder, and create a file with a helpful name

```bash
cd /etc/nginx/sites-enabled
sudo vim <helpful name>
```

You can use [demo_site](demo_site) as an example 

## Reload the web-server ##

After changeing anything ensure to reload server with the following command, will also report if there are any errors in the scripts.

```bash
sudo nginx -s reload
```