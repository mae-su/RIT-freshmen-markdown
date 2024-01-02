# __*markdown cheat sheet!*__
## **__basic formatting__**
*surrounding text with the following characters will change the formatting. these can be combined:*

`*italics*`  *surround text with one asterisk to make it italic.*

`**bold**` **surround text with two asterisks to bold it** - great for emphasizing important words

`***both***` ***surround text with three asterisks to make it bold and italic.*** (use this with caution, it may come off as agressive)

`__underline__` __surround text with two underscores to underline it__ - great for an alternative to bolding

`~~strikethrough~~` ~~surround text with two tildes to strike it through. this is good for indicating something changed, but pretty rarely used.~~

``inline code block`` - surround text with a backtick (imagine typing `~` but without holding shift) for an inline code block. good for indicating a `short technical value` or something without formatting applied.

## __**titles/headers**__
# header 1
## header 2
### header 3
```markdown
# header 1
## header 2
### header 3```
*typing one, two, or three hashtags then a space will make the line super big, really big, or just big. __use these for things like titles and sectioning text.__*

## bulleted lists
*ngl, discord doesn't make these too pretty. nevertheless:*
`- bullet point`:
- adding `- ` in front of your text will bullet it
  - adding ` - ` (same thing but with a space in front) will make a subpoint

## __**code blocks**__
*we only use this for more technical/data related things, but good to know nevertheless!*
```python
print('code block')
```
*surround code with three backticks to create a code block for nicely formatted and colored code or technical output. only use this for code or long, technical, or repetitive snippets of text.*

## __**block quotes**__
`> line quote` - begin a line in a message with this to quote or reference something:
> something said a while back
`>>> multi-line quote` - discord will usually continue quote formatting automatically, but this will ensure a whole multi-line section gets quoted.

## __**[Links](<https://www.youtube.com/watch?v=xvFZjo5PgG0>)**__
`[link text](https://example.com)` links look far prettier integrated into your text. make sure the text/context clearly indicates what the link will lead to! 

**to prevent an embed** (the little preview of a link's content, for example a youtube video preview) you can surround the link with `<>`:
```markdown
<https://mae.red>
[mae dot red](<https://mae.red>)
```

here's a nice example of clean link formatting we used in an announcement:

> **RIT Mobile for iPhone:** [on the **App Store**](https://apps.apple.com/us/app/rit-mobile/id481121853)
> 
> **RIT Mobile for Android:** [on the **Play Store**](https://play.google.com/store/apps/details?id=edu.rit.ritmobile)
> 
> **TigerChat for Web:** [**tigerchat.app**](https://tigerchat.app/chat/dash)

```markdown
**RIT Mobile for iPhone:** [on the **App Store**](https://apps.apple.com/us/app/rit-mobile/id481121853)
**RIT Mobile for Android:** [on the **Play Store**](https://play.google.com/store/apps/details?id=edu.rit.ritmobile)
**TigerChat for Web:** [**tigerchat.app**](https://tigerchat.app/chat/dash)
```
## ⟶ this arrow is pretty cool for sectioning.
i've found this useful to be able to indicate a passage summary, closing statement, etc near the end of some statement.