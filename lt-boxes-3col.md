
[Return Home](index.md)

# 3 Column Boxes with Icons and Text
This component is 3 boxes with an icon, subheader text, and descriptive text. It should be used for displaying short concise bits of text. This component displays 3 boxes horizontally on desktop, and stacked on mobile


```
VSCode Snippet Shortcut: lt-boxes-3col
```

### Desktop
![3 Column Boxes on Desktop](https://s3.amazonaws.com/marketing.lendingtree.com/email/module-library/lt-boxes-3col-desktop.png)

### Desktop Dark Mode
![3 Column Boxes on Desktop - Dark mode Version](https://s3.amazonaws.com/marketing.lendingtree.com/email/module-library/lt-boxes-3col-desktop-dm.png)

### Mobile
![3 Column Boxes on Mobile](https://s3.amazonaws.com/marketing.lendingtree.com/email/module-library/lt-boxes-3col-mobile.png)


## Mobile CSS
The mobile CSS for this module is not included in the starter template
```
 .pl-0 {
    padding-left: 0px !important;
  }

  .pr-0 {
    padding-right: 0px !important;
  }

  .mb-20 {
    margin-bottom: 20px !important;
  }

  .font-13 {
    font-size: 13px !important;
  }

  .mw-280 {
    max-width: 280px !important;
  }
```


## Dark Mode CSS
The dark mode CSS for this module is already included in the starter template
```
.dm-border-none {border:none !important;} 

.dm-bg-black { background-color: #000000 !important;}
```

## Notes
- You should adjust the left and right margin of the email body to 40px in order for this component to display correctly
- Many of the hopper green icons are already hosted in amazon AWS at the following path: email/icons/lt5_es/hopper-green-icons/
- The icon you want to use may already exist at the above location. If it is not there when you search, create a new one using the following nomenclature: **lt5-icon-hg-no-ring-[image-description].png**
- You should try to use consistent amounts of text for the header and body of each of the boxes to make sure they have the same heights. Otherwise you will have to set explicit heights on each of the header and body text elements and then create a mobile style to strip them away when they stack.

## Troubleshooting
If you have issues with the boxes being different heights in **Outlook 2013 120 DPI (Win 10)** you can create a special class like so and add it to the special mso code only section to explicitely set a height for all 3 boxes (only in outlook)
```
.mso-h-170 { height:170px !important;}
```

After creating this class you need to apply it as the **first class** on each of the \<td\>s that contain the stylng for the border and shadow
```
<td class="mso-h-170 dm-black-bg dm-no-border" style="background-color: #FFFFFF; border: 1px solid #EFEFEF; padding: 20px 10px; box-shadow: 0px 2px 4px rgba(0,0,0,.2);">
```

## Tabs
After inserting the code snippet into VSCode immediately pressing tab will take you to bookmarked sections in the snippets where edits are commonly made
1. box 1 header
2. box 1 blurb
3. box 2 header
4. box 2 blurb
5. box 3 header
6. box 3 blurb

[Return Home](index.md)
