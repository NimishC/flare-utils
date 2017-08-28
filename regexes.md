# Regular expressions for find/replace

In the Find/Replace pane, under Find Options, select **Find in source code**, and under Search Type, select **Regular Expressions**

### Find condition tags

Find any condition tag: `MadCap:conditions=\".*?\"`

Find specific condition tag: `MadCap:conditions=\"Conditionfile.Conditionname\"`

### Find and replace HTML/XML tags

Find tags (example: p with any class or attribute): `<p.*?>(.*)</p>`
Replace: `<newtag class="class-if-applicable">\1</newtag>`
