# analytics

> Smaller, cacheable subset of Smart Analytics JS client

This project is an implementation for Analytics tracker
script [analytics.js][analytics-js].

## Install to your project

The easiest way to install zp-tracker to your project is to include the following
script to your website:

```html
<script>
(function(e,t,n,i,c,r,s){e[n]=e[n]||function(){(e[n].q=e[n].q||[]).push(arguments)}
;r=t.createElement(i);s=t.getElementsByTagName(i)[0];r.async=true;r.src=c;setTimeout(
function(){s.parentNode.insertBefore(r,s)},1)})(window,document,"galite","script",
"https://cdn.jsdelivr.net/gh/azimvirt/analytics/zp-tracker.min.js");

galite('create', 'ZP-XXXXXXXX-X', 'auto');
</script>
```

This includes the most recent version of zp-tracker to your site from the JSDelivr
CDN, initializes the script with your own ZP code and sends the conversion events.