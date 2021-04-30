
[Return Home](index.md)

# Reverse Mortgage eBook Shared Asset
This shared asset is added to the bottom of select reverse mortgage template.  It contains parts. The CSS and the HTML Styling.  The shared asset for the CSS should be placed just below the closing style tag for the CSS embedded in the template.


```
CSS: <shared_asset> bsft_reverse_mortgage_ebook_content_block_css </shared_asset>
HTML: <shared_asset> bsft_reverse_mortgage_ebook_content_block </shared_asset>

```

### Desktop
![eBook Shared Asset on Desktop](https://s3.amazonaws.com/marketing.lendingtree.com/email/module-library/sa-reverse-mortgage-ebook-desktop.png)


### Mobile
![eBook Shared Asset on Mobile](https://s3.amazonaws.com/marketing.lendingtree.com/email/module-library/sa-reverse-mortgage-ebook-mobile.png)


### Sample Template with eBook Shared Asset
![eBook Shared Asset used in a Template](https://s3.amazonaws.com/marketing.lendingtree.com/email/module-library/sa-reverse-mortgage-ebook-sample-template.png)


## Mobile CSS
All of the mobile CSS for this module is included in the CSS Shared Asset: 
```<shared_asset> bsft_reverse_mortgage_ebook_content_block </shared_asset>```


## Dark Mode CSS
There is no special dark mode styling required for this template


## MSO CSS
The MSO CSS may already be included in the template you are using.  If not, make sure to add the below code snippet.  This code ensures that the buttons render correctly in outlook clients

```
<!--[if mso]>
<style type="text/css">
.mso-container-cta { height: 50px !important; }
</style>
<![endif]-->
```

## Notes
- The shared asset for the CSS should be placed just below the closing style tag for the CSS embedded in the template.


## Troubleshooting
No troubleshooting tips at this moment


## Sample Templates in Blueshift
Reference these templates in Blueshift if you need to see exactly how to use this shared asset

- trigger-dropoff-rm-day2-ctl
- trigger-dropoff-rm-day4-ctl
- trigger-dropoff-rm-day8-ctl


[Return Home](index.md)
