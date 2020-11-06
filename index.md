
# Welcome to the LT Module Library

This is a library that houses template modules. It lists the vscodesnippet to use for inserting it into your code, and it displays the css you can copy and paste to make these modules work.

- [Call to Actions (CTAs)](#ctas)



## CTAs
We use 3 main CTAs. They can have rounded or soft square edges

**VSCode Snippet:** lt-cta


![Image of Rounded CTAs](https://s3.amazonaws.com/marketing.lendingtree.com/email/module-library/lt-cta-round.png)


### Mobile CSS:
```
.container-cta a {
    font-size: 15px !important;
    padding: 10px !important;
  }

  .container-cta {
    width: 267px !important;
  }

```

### Dark Mode CSS:
The dark mode code for this module is already included in the starter template
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

### Notes
- Square buttons have a border radius of 4px
- Round buttons have a border radius of 25px
- You can adjust the width of the button
- You can change this button to 3 different colors: #FF704D(Electric Salmon), #00AEEF(Blue) or #08C177(Green)
