# Steps to create Blueprints in GitHub

## Goal:
Provide an online storage area for blueprints to be shared with others.
- Easy to share link
- Blueprint String
- Preview Image
- Searchable by keywords
- Easy to maintain
- no dedicated website creation / maintenance

### Pre-reqs:
- Have a GitHub account (github.com)
- Create a new repo (e.g. "FactorioBlueprints")

### **Create a Book**:
- Select "Add file" dropdown
- Select "Create new file" choice
- In the `file name` field, enter the name of your book and add `.md` to the name.
>     This tells GitHub that the file is MarkDown and enables special formatting.
- Paste this template into the file:

```
# book_title

## [Blueprint String Text](string_url)

[FactorioBin](fb_url)

-----

### Book Contents
```

We will return to this GitHub page after creating the FactorioBin page.


### **Prepare to share a Blueprint Book**
In Factorio, select the blueprint book you want to share.  You should add a description (including keywords).  The blueprints inside the book will be included, so ensuring each has a description will be helpful.
- Select the blueprint book
- Select the `Export to String` action
- Select the `Copy` button
>     Copying a large book will take time.  Note that FactorioBin has a limit of `2000000` characters.  I'm not sure how much of a limit this is.


### **Create a post in FactorioBin**
FactorioBin provides an easy way to store and view blueprints.  It does not have a search feature or a way to group blueprints.
- Browse to factoriobin.com
> The default page is **Share a Blueprint**.
- In the **Blueprint String** field, paste the blueprint string copied from Factorio
- In the **Post Title** field, enter the name of the blueprint book.  I recommend copying the name in Factorio.
- You may change the **Expiration** if you want the blueprint to expire.
- Select the Submit button

After a moment, you will be presented with a page for your book.  **Do not navigate away from this page until you have captured the URL.**

### **Add the FactorioBin information into GitHub**
Return to the GitHub page you started above.
- Replace the `book_title` page with the name of the Blueprint Book.  
>   If you used the same name in FactorioBin, you can copy from either.

#### Replace the `string_url`
- On the FactorioBin page, there is a button labeled *View*.  **Right-Click** on that button and select `Copy link address`.  This will put the FactorioBin page that has the blueprint string into your copy buffer.
>     This is a link to the string.  One of the benefits of using FactorioBin is that the blueprint string is not stored in GitHub.  It is a large text string and we don't want to manage it.
- In the GitHub page, replace the `string_url` text with the url copied from FactorioBin by selecting `string_url` and pressing **Ctrl-Shift-V**.  (You can also select `string_url`, Right-Click, and select "Force Paste".)
> You need to paste only the url to get around GitHub's automatic formatting.  It recognizes that you are pasting a URL and it will try to format it as such.  This messes up the "[Blueprint String Text]" message you already have.  Using Force Paste saves having to correct the link title and only inserts the URL string.

#### Replace the `fb_url`
- On the FactorioBin page, select the url.
- In the GitHub page, replace the `fb_url` text with the url copied from FactorioBin.  As above, you need to use "Force Paste". 

#### Add the Book Contents
- On the FactorioBin page, select all of the lines under the **Book Contents** heading and copy them into the text buffer.
- In the GitHub page, paste these this information under the `### Book Contents` heading.  You will need to make a change to the pasted text:
 - Replace the text `Blueprint` at the start of each line with a star and space (`* `).  This will create a bullet list of the blueprints in the book.
 >    The copy action uses the label for `Blueprint`, `Upgrade planner`, and `Deconstruction planner`.  It smashes these words together with the name of the bluperint.  You'll want to clean this up.
 
 
 >  Note that if you use icons in the blueprint title, these will be expanded with the text that defines them.  For exmaple, instead of an icon of a locomotive, the text `[item=locomotive]` will be shown.  This does not happen _inside_ the blueprint, only in the title list at the book level. 

### **Update the Commit new file field**
The first field under this section will be displayed when viewing the GitHub repo.  You can put anything here.  If you don't provide anything, GitHub provides a description of the action, (e.g. 'Created', 'Updated').  This doesn't provide much value to a person looking for blueprints.  I recommend using 'Blueprint Book'. The extended description is not displayed this way.

### **Commit the new file**
This will save the file into the repo.  Congratulations.


## Edits and updates
You can update an existing entry in GitHub by navigating to the file selecting the 'Pen' icon in the top right of the file information.  

There is no edit function on FactorioBin.  If you have updated a blueprint and want to update the shared information, you will create a new Post in FactorioBin, then update the url's in GitHub.  If there are no description changes, those can be left as is.

> Contact me at my blueprint library on GitHub (https://github.com/HySpeed/FactorioBlueprints) if you have any questions or suggestions.

thanks

