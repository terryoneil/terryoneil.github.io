
# Git for Writers

Git is an extremely useful version control tool. It may look intimidating to non-developers, but it's actually pretty simple. It's an essential piece of any collaborative writing workflow.<br>
Oftentimes people work with Git purely through command line terminals. While this is  efficient and practical for coders, it's not quite necessary for writers. It's easier to work in something that has a GUI, like Github Desktop.<br>

## What Does Git Actually Do?

Git is a version control tool. It keeps track of every different version that you save of a file. With Git, you can easily track changes and collaborate with other people through forking, merging, .. 

## MARKDOWN EXPLANATION

## Installing GitHub and a Text Editor

### GitHub

Thus, to begin, create a [Github Account](https://github.com/) and then download [Github Desktop](https://github.com/apps/desktop).


### Text Editor

To edit our Markdown files, we're going to use [Visual Studio Code](https://code.visualstudio.com/), or *VS Code*. Install it.<br>

!!! Note
    Microsoft's Visual Studio Code is one of the most popular tools for writing documentation. However, there are plenty of other options like Typora, Obsidian, and Ulysses.

## Creating Your First Repo

Open GitHub Desktop and sign in with your GitHub account. The program walks you through the process of creating and connecting a repo. Follow those steps.

!!! note

    If you're collaborating with other users, you'll want to *fork* and *clone* the repo. See the [Glossary](#Glossary) for definitions of all these Git-specific terms. 

## Making Your Markdown File

Go into GitHub Desktop, right-click on your repo, and select Open in Visual Studio Code. PROVIDE AN ALTERNATIVE METHOD?<br>
Once you're in VS Code, open the Explorer tab and click the New File -IMAGE- button. Create a file called *test.md*.<br>
Try copying and pasting the following sample markdown template.

!!! tip

    In VS Code, you can easily preview your changes in real-time. Simply press `ctrl/cmd + shift + v` to open a markdown preview tab.



### Level 1 Heading

Here is some sample text. **This sentence is bolded.** *The following sentence—in other words, this one—is italicized.* ***This one combines both emphasis techniques.*** 

## Level 2 Heading 

> Here is a blockquote!
>
>> And another, nested!

### Level 3 Heading

1. Markdown automatically handles numbered lists.
1. You don't actually need to keep track.
1. Notice how this list, in the code, consists only of the number 1
1. And yet, when all is said and done, it renders as a proper numbered list.

- By contrast,
- This is an ordered list.

This is a hyperlink to [Google](https://google.com "And this is the link's tooltip.").
<This is a direct link.>

#### Image Insertion 

![This is alt text for an image.]()

This is the author's cat.
```

## Glossary

**Repo (Repository)**
— A folder tracked by Git containing all your project files and their full history.

**Commit**
— A saved snapshot of your changes, with a message describing what changed.

**Fork**
— Your personal copy of somebody else's GitHub repository.

**Clone**
— The act of downloading a copy of a repo to your computer so you can edit it without affecting the original. 

**Markdown**
— A markup language for writing, like HTML. Markdown files use the **.md** extension.

**Syntax**
– The set of formal rules that defines the structure and format of a coding or markup language. You can think of syntаx as the "grammar" of coding languages.