# Thriftshop Site - Default Theme

[![Netlify Status](https://api.netlify.com/api/v1/badges/17758869-2b98-4ae6-87f3-6206ac5d8578/deploy-status)](https://app.netlify.com/sites/goldcoders/deploys)

## Requirements

-   Thriftshop Site Manager v1.0.0

## Using Checkout with Paymongo

-   Set this on your netlify account ENV Variables for the specific site

```
PAYMONGO_EMAIL=
PAYMONGO_PASS=
PAYMONGO_LIVEMODE=
```

## Using Custom Domain Name

-   Update your site DNS to point to netlify DNS

```
dns1.p05.nsone.net
dns2.p05.nsone.net
dns3.p05.nsone.net
dns4.p05.nsone.net
```

-   Add your Domain in Netlify
-   Add DNS Record in your Domain inside Netlify

## Using FB Messenger Chat Plugin

-   get Page ID , on Facebook Fanpage Message Settings and update in on your CMS

## Using Disqus Comment

-   Get Disqus Shortcode and update it on your CMS

## Using Contact Form

### Recaptcha V2

-   [Create Recaptcha For Your Domain](https://www.google.com/recaptcha/admin/create) and copy Site Key

### Creating New Google Form

-   Create New Form
-   Add New Fields
    -   Name
    -   Phone
    -   Message
-   Allow Collecting Emails

### Getting Form URL

-   Click Send Form Click and click via link
-   copy link open it in browser
-   inspect element
-   search for form action
-   copy the url in action

### Adding Field Name

-   Click on the right corner triple dot
-   It will show Get Prefilled Link , Click it
-   Inspect The Form Field
-   Copy the name , it always start with entry.{ANY_NUMBER}
-   paste in on the form field name on contact page
