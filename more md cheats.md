What You Can Do Natively in Pure Markdown

Font size: Only indirectly via headings
# Big title (largest)
## Medium ### Smaller
Down to 
###### (smallest)
No control over exact pixel/pt sizes.
Font family/type: Nothing at all—no way to switch to Arial, Times, etc.
Color / highlighting: No built-in colored text.
You can do basic emphasis:
bold (**text**), italic (*text*), bold italic (***text***)
Or code-like highlighting: inline code (`text`) — usually appears in a monospace font with background.
$$    \color{red}{\text{This is red text!}}    $$
+ This line appears green (addition)
- This line appears red (deletion)
! This might be orange in some views
Deprecated but still works sometimes: <font size="5" color="blue">old way</font>
This is normal text.

<span style="font-size: 24px; color: red; font-family: Arial, sans-serif; font-weight: bold;">
This is BIG, RED, Arial, and bold!
</span>

<span style="background-color: yellow; padding: 2px;">Highlighted like a marker</span>

<p style="font-size: 18px; color: green;">Green paragraph text</p>
