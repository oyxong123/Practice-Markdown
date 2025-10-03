# Practice-Markdown
An empty repo for me to learn and memorize Markdown syntax.

=== Practice starts here ===

# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
#### Heading level 5
##### Heading level 6


Heading level 1 Alt
==
Heading level 2 Alt
--


# Here's a Heading
Do this.

#Here's a Heading
Instead of this.


Put blank lines before...

# Heading

...and after a heading.

Otherwise, it may not...
# Heading
...look right in some edge cases.


Use a blank line,

to separate one or more lines of text,
otherwise they would get joined like this together into a paragraph.


Don't put tabs or spaces in front of paragraphs.
  (1 Tab) Otherwise it'll cause unexpected formatting problems
    (4 Spaces) Like this.


To have line breaks without placing one empty line, add two spaces behind a line, (2 Spaces)  
to create a line break.

Though for best practice, it's better to use the HTML tag<br>
for easier readibility on the text editor if it is supported.

It is not receommended to use backslash\
because not all application support it.


Just a note, a blank line spacing (blank line)

like this, is different and much wider than a line break spacing (2 Spaces)  
like this.


There are several ways to bold texts.  
This is the **first** method using double asterisks.  
This is the __second__ method using double underscores.  
This is the t**hir**d method using double asterisks in the middle of word.  
This is the f__ourt__h method using double underscores in the middle of a word that doesn't work in most Markdown applications.


There are several ways to italicize texts.  
This is the *first* method using single asterisks.  
This is the _second_ method using single underscores.
This is the t*hir*d method using single asterisks in the middle of a word.
This is the f_ourt_h method using single underscores in the middle of a word that doesn't work in most Markdown applications.


There are several ways to bold and italicize texts at the same time.  
This is the ***first*** method using triple asterisks.
This is the ___second___ method using triple underscores.
This is the **_third_** method using double asterisks and single underscores.
This is the __*fourth*__ method using double underscores and single asterisks.
This is the f***ift***h method using triple asterisks in the middle of a word.
This is the s___ixt__h method using triple underscores in the middle of a word that doesn't work in most Markdown applications.


> This is how you add blockquotes.

> You can also add multiple parapgrahs,
> within the same blockquote... (Blank line with >)
>
> by leaving a blank line like this... (2 Spaces)  
> same as line break.

> It can also be nested...
>> by using double greater-than sign.
>> To return to the blockquote outside... (Blank line)
>> 
>...a blank line is required at the end of the nested blockquote.


> We can use some other Markdown formatted elements within blockquotes.
> # Heading level 1 works.
> ## Heading level 2 works.
> ### Heading level 3 works.
> #### Heading level 4 works.
> ##### Heading level 5 works.
> ###### Heading level 6 works.
> Heading level 1 alt works.
> ==
> Heading level 2 alt works.
> --
> *Italicize* works.
> **Bold** works.
> ***Italicize + Bold*** works.
> I*taliciz*e in the middle of a word works.
> B**ol**d in the middle of a word works.
> I***talicize + Bol***d in the middle of a word works.


Always put blank lines before... (Blank line)

> ...a blockquote... (Blank line)

...and after to prevent weird formatting.


1. Ordered list can be created by joining a number, a period, and a space together...
2. ...like...
3. ...this. 
8. The numbers don't have to be in numerical order,
5. ... like this.
10. nor do they need to be different,
10. ...like this.
11. Both will still be rendered the same as a properly ordered list. (Blank Space) 

1. Blank space does not work to start another ordered list.
2. To start a new ordered list right after an existing ordered list, we can use the HTML tag "br" with blank lines before and after it. (Blank Space + br + Blank Space)

<br>

1. There we go.
2. It's working perfectly now. (Blank Space + br + Blank Space)

<br>

4. The first number of the ordered list depends on the first number that you set.
3. For examples, this list will start from "4.". (Blank Space + br + Blank Space)

<br>

1. Indented items can also be created.
   1. Like this.
      1. Note that you must start indented items with "1.", otherwise it won't get rendered as indented items.
4. We can have multiple indented lists.
   1. Though after the first item,
   3. the order of numberings don't matter, for example...
   2. ...like this. (Blank Space + br + Blank Space)

<br>

1) Note that use of parenthesis to create ordered list doesn't work in all Markdown applications,
2) so it's not good practice to use it. (Blank Space + br + Blank Space)

<br>

Unordered list uses the same logic as ordered list, except it doesn't have any order. There are several syntax we can use to create unordered list.
- The first one is using dash.
* The second one is using asterisk.
+ While the third one is using the plus sign.
  - Note that indentation works with unordered list too.
    * So feel free to add as much indentation as you like.
- It'll all work correctly. (Blank Space + br + Blank Space)

<br>

- Though, it is not recommended to mix up the syntax in a single list like this as not all Markdown applications render them correctly.
* Thus, try to stick to the same syntax.
+ First is because some Markdown applications require all syntax to be the same to treat it as an unordered list.
- Second is because in the case where a Markdown application cannot render the list correctly, it'll at least display it in a consistent and readable way. (Blank Space + br + Blank Space)

<br>

- If an ordered list item needs to start with a number followed by a period, a backslash is required before the period.
- For example, like this:
- 1234\.
- Otherwise, it'll get formatted like this:
- 1234. 
- (Blank Space + br + Blank Space)

<br>

1. If we want to continue the list after another element,
2. We can either add 4 spaces before the in-between element like this... (2 Spaces this line + 4 Spaces next line)  
    There are 4 spaces before this sentence.
3. ...or 1 tab like this, both methods require 2 space at the end of the last item to format correctly. (2 Spaces this line + 1 Tab next line)  
   There is a tab before this sentence.
4. Here's an extra blockquotes example. (1 Tab next line)
   > There is a tab before this sentence.
6. This applies both with ordered and unordered list. (Blank Space + br + Blank Space)

<br>

1. We can also mix ordered list with unordered list.
   - Here is an ordered list...
   - ...with multiple elements...
2. ...within an ordered list. (Blank Space + br + Blank Space)

<br>

`Backticks` can be used to format text as code.  
If we want to use backticks within a line of text that will be formatted as code, ``we can enclose it with double backticks so the `single backticks` in the line of text will still display.``


Code blocks are created by indenting all of them with 5 spaces like this...

     print("one")
     print("two")
     print("three")

...or surrounding them with triple backticks before and after like this...

```
print("one")
print("two")
print("three")
```

...or surrounding them with triple tildes before and after like this.

~~~
print("one")
print("two")
print("three")
~~~


There are several ways to create horizontal rules.
We can use triple or more asterisks on a line by themselves like this...

***

******

*********

...or triple or more dashes like this...

---

------

---------

...or triple or more underscores like this.

___

______

_________


For compatibility with all Markdown applications, it is best practice to put blank lines before and after each horizontal rule.

One example is where putting dashes right after a line of text makes the text a heading instead of creating a horizontal rule right after it.
---


A link can be created by enclosing the link text in brackets then follow it with the URL in parentheses like [this](https://youtube.com).

We can also add a tooltip for the link by writing it in the parentheses after the URL using double quotes like [this](https://youtube.com "The biggest video streaming website in the world.") or using single quotes like [this](https://youtube.com 'The biggest video streaming website in the world.') or using parentheses like [this](https://youtube.com (The biggest video streaming website in the world.)).

We can also create links for URLs or emails that has itself as the text by surrounding them in angle brackets.
<https://google.com>
<foo@gmail.com>

In addition to that, we can format the links like normal texts.  
One thing to note is that the way to format a link as code is a little different compared to the rest.  
**[Link](https://youtube.com)**  
__[Link](https://youtube.com)__  
*[Link](https://youtube.com)*  
_[Link](https://youtube.com)_  
**_[Link](https://youtube.com)_**  
__*[Link](https://youtube.com)*__  
***[Link](https://youtube.com)***  
___[Link](https://youtube.com)___  
[`Link`](https://youtube.com)  


There is a thing called reference-style links that we can use to navigate from a text to a part elsewhere in the file.  
It is divided into two parts.

The first part is where the link is located. Here's an example of it.  
[Link][1]  
The first bracketed content denotes the displaying text, while the second bracketed content contains the label that points to the link that we're storing elsewhere.  
The content of the second bracketed can be anything, from letters, numbers, spaces (but there needs to be at least one actual character), to punctuations.  
It is not case sensitive.  
[Link 2][a]  
[Link 3][ -]  
[Link 4][,]  
[Link 4][_]  

For the second part of the link, it is where the first part will link to.  
To write it, we first write the label in brackets, followed by a colon plus at least one space, then the URL which we can optionally enclose in angle brackets, 
and followed by the optional title enclosed in either double quotes, single quotes, or parentheses.  
The second part can be placed anywhere in the document, but it must have a blank space before and after it for it to work correctly. (Blank Space)

[1]: https://youtube.com
[a]: <https://youtube.com>  
[ -]: https://youtube.com "Title"  
[,]: https://youtube.com 'Title'  
[_]: https://youtube.com (Title) 
(Blank Space)

If there are spaces in URL, we should replace them with %20 as not all Markdown applications can render them correctly.  
For example, we should write it as,  
[Link](https://example.com/my%20file.txt)  
instead of,  
[Link](https://example.com/my file.txt)  

The same concept applies to parentheses, we should replace opening parenthesis with %28 and closing parenthesis with %29.  
For example, we should write it as,  
[Link](https://example.com/%28test%29)  
instead of,  
[Link](https://example.com/(test))  


The syntax to add images is an exclamation mark followed by alt text in bracketes (can be empty), and the path or URL to the image asset plus an optional title in single quotes, double quotes, or parentheses, both in parentheses.  
![An Image](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b6/Image_created_with_a_mobile_phone.png/1024px-Image_created_with_a_mobile_phone.png 'Nostalgic Image')  
![An Image](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b6/Image_created_with_a_mobile_phone.png/1024px-Image_created_with_a_mobile_phone.png "Nostalgic Image")  
![An Image](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b6/Image_created_with_a_mobile_phone.png/1024px-Image_created_with_a_mobile_phone.png (Nostalgic Image))  
![](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b6/Image_created_with_a_mobile_phone.png/1024px-Image_created_with_a_mobile_phone.png (Nostalgic Image))  


To escape characters that are used to format text in a Markdown document, add a backslash in front of the character.  
\\
\`
\*
\_
\{
\}
\[
\]
\<
\>
\(
\)
\#
\+
\-
\.
\!
\|


That is all of the basic syntax of Markdown. Congratulations for learning and going through all of them Yu Xuan! 
Keep going at it. You'll get to where you want to get to one day. You've done well reaching this far!!!!!!!!!

Time to conclude this Markdown document.  
The End.

by 
Ong Yu Xuan  
03-10-2025 4:30pm
