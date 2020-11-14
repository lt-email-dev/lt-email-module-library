
[Return Home](index.md)

# CTA
CTA stands for 'Call to Action'. We use Orange, Blue, and Green CTAs. They can have rounded or soft square edges
```
VSCode Snippet Shortcut: lt-cta
```

![Image of Squared CTAs](https://s3.amazonaws.com/marketing.lendingtree.com/email/module-library/lt-cta-square.png)

![Image of Rounded CTAs](https://s3.amazonaws.com/marketing.lendingtree.com/email/module-library/lt-cta-round.png)


## Mobile CSS:
The mobile CSS for this module is already included in the starter template
```
.container-cta a {
    font-size: 15px !important;
    padding: 10px !important;
  }

  .container-cta {
    width: 267px !important;
  }

```


## Additional CSS for Hover Effect:
Paste this CSS above the mobile CSS styles. These are the hover effects. You can paste all of these styles are just the one for the color button you are using.
```
.cta-es:hover { 
  background-color: #eb5843 !important;
}

.cta-blue-ghost:hover,
.cta-blue:hover { 
  background-color: #2187c1 !important; 
}

.cta-green:hover { 
  background-color: #069059 !important; 
}

```

## Dark Mode CSS:
The dark mode CSS for this module is already included in the starter template
```
/* Make Link Text Black */
  .container-cta a {
    color:#000 !important;
  }

/* Make Ghost CTA Link Text White */
  .container-cta a.cta-blue-ghost {
    color:#FFF !important;
  }
```

## Notes
- Square buttons have a border radius of 4px
- Round buttons have a border radius of 25px
- You can adjust the width of the button
- You can change this button to 3 different colors: #FF704D(Electric Salmon), #00AEEF(Blue) or #08C177(Green)

## Tabs
After inserting the code snippet into VSCode immediately pressing tab will take you to bookmarked sections in the snippets where edits are commonly made
1. button width
2. dropdown where you select the button color
3. border radius: enter either 4 (square) or 25 (round)
4. dropdown where you select the mobile hover style. es (Electric Salmon), green, or blue
5. button text

[Return Home](index.md)
