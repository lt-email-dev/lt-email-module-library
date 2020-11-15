
[Return Home](index.md)

# Image
This is your run of the mill basic image

```
VSCode Snippet Shortcut: lt-img
```

## Mobile CSS
This is a mobile class you can include optionally to make the image full width on mobile.
```
.fluid-img {
    height: auto !important;
    max-width: 100% !important;
    width: 100% !important;
  }

```

## Notes
- The image snippets contains the first part of the path for the images stored in AWS.  You will need to add the name of your image.
- Be sure to set an explicit width and height
- If the image contains text or adds context to the email be sure to specify alt text
- If the image is just an icon or a decorative element leave the alt tag empty **alt=""**
- To make the image responsive for mobile, give it a class of **.fluid-img** and copy that class from the css master file into your mobile styles


## Tabs
After inserting the code snippet into VSCode immediately pressing tab will take you to bookmarked sections in the snippets where edits are commonly made
1. image name
2. width
3. height
4. alt text


[Return Home](index.md)
