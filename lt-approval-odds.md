
[Return Home](index.md)

# Approval Odds 
This is a dynamic module that displays whether a person has good or very good approval odds based on their credit band. If the user has excellent credit they will see that they have 'Very Good' approval odds.  If the user has good or fair credit, they will see that they have 'Good' approval odds. If the person fall into these 3 credit ranges then they will see nothing.

In order for this module to work correctly you will need to including the below 
```
Blueshift Shared Asset: <shared_asset> bsft_LT_Credit_Score </shared_asset> (already included in the starter template)
VSCode Snippet Shortcut: lt-approval-odds
VSCode Snippet Shortcut: lt-approval-odds-disclaimer-text

```
### Great Approval Odds
![Approval Odds - Great](https://s3.amazonaws.com/marketing.lendingtree.com/email/module-library/lt-approval-odds-great.png)

### Good Approval Odds
![Approval Odds - Good](https://s3.amazonaws.com/marketing.lendingtree.com/email/module-library/lt-approval-odds-good.png)

### Approval Odds Disclaimer Text
![Approval Odds - Disclaimer Text](https://s3.amazonaws.com/marketing.lendingtree.com/email/module-library/lt-approval-odds-disclaimer-text.png)


## Steps to Add Module to this Template
There are 3 things you'll need to include in order to setup this template properly

### 1. Blueshift Shared Asset
This should be added to the file beneath **<shared_asset> bsft_Preheader_Text </shared_asset>** (already included in the starter template)

### 2. Approval Odds Component (lt-approval-odds)
We typically include this in the body of the emails towards the top

### 3. Approval Odds Disclaimer (lt-approval-odds-disclaimer-text)
This should be included in the body of the email at the very bottom. It has dynamic logic so that it only show's if the user has excellent, good, or fair credit.

## Mobile CSS:
Some of the mobile styles are already included in the starter template, others are not. **.approval-odds** is not included in the starter template. **lt-p** is included in the starter template
```
.approval-odds {
    width: 150px !important;
    height: auto !important;
  }
  
.lt-p {
    font-size: 15px !important;
    line-height: 24px !important;
    margin-bottom: 20px !important;
  }
```

## Dark Mode CSS:
The dark mode CSS for this module is already included in the starter template
```
 /* Custom Dark Mode Font Colors */
  h1, h2, h3, p, span, a, b { color: #ffffff !important; }
```

## Notes
- No notes. Go crazy!

## Tabs
no tabs are used with this snippet

[Return Home](index.md)
