
[Return Home](index.md)

# Articles
This module should be inserted just above the footer or below the main body content.  It is not meant to be used within the main body content of the email. This module displays a space beneath the main body of the email then displays two article blocks separated by a space. On mobile the image stacks above the text.
```
VSCode Snippet Shortcut: lt-article
```

### Original View
Once you insert this module into the template using this snippet, there is a comment that appears that you should replace using the [CTA snippet](lt-cta.md).  Once you insert the CTA snippet, change **align="center"** to **align="left"**.

![Original View of the Module](https://s3.amazonaws.com/marketing.lendingtree.com/email/module-library/lt-article-desktop-original.png)

### Desktop
![Articles Desktop](https://s3.amazonaws.com/marketing.lendingtree.com/email/module-library/lt-article-desktop.png)

### Desktop Dark Mode
![Articles Desktop Dark Mode](https://s3.amazonaws.com/marketing.lendingtree.com/email/module-library/lt-article-desktop-dm.png)

### Mobile
![Approval Mobile](https://s3.amazonaws.com/marketing.lendingtree.com/email/module-library/lt-article-mobile.png)


## Mobile CSS
Some of the mobile styles are already included in the starter template, others are not.
```
.container-inner {
    padding: 34px 20px !important;
  }

.mw-280{
    max-width: 260px !important;
  }

.block-elem {
    display: block !important;
    float: none !important;
    width: 100% !important;
  }

.mb-20 {
    margin-bottom: 20px !important;
  }

.height-100 {
    height: 100px !important;
  }

.img-article {
    width: 100% !important;
    height: auto !important;
  }

.pl-0 {
    padding-left: 0px !important;
  }

.pr-0 {
    padding-right: 0px !important;
  }

.article-h2 {
    font-size: 20px !important;
    line-height: 30px !important;
}

.lt-p {
    font-size: 15px !important;
    line-height: 24px !important;
    margin-bottom: 20px !important;
  }
```

## Dark Mode CSS
The dark mode CSS for this module is already included in the starter template
```
.dm-bg-charcoal { background-color: #303030 !important;}

h1, h2, h3, p, span, a, b { color: #ffffff !important; }
```

## Notes
- When you first add this module to the email template **the button will NOT be included**. But there will be instructions to use the [CTA Snippet](lt-cta.md) to add a button. You can then change align="center" to align="left" in the CTA snippet to left align the button.

## Tabs
After inserting the code snippet into VSCode immediately pressing tab will take you to bookmarked sections in the snippets where edits are commonly made

1. article 1 image link
2. article 1 image URL
3. article 1 title
4. article 1 blurb
5. article 2 image link
6. article 2 image URL
7. article 2 title
8. article 2 blurb

## Example Template
![Articles Example Email Template](https://s3.amazonaws.com/marketing.lendingtree.com/email/module-library/lt-article-example.png)


[Return Home](index.md)
