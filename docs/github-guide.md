
# Git for Writers

Git is an extremely useful version control tool. It may look intimidating to non-developers, but it's actually pretty simple. It's an essential piece of any collaborative writing workflow.<br>
Oftentimes people work with Git purely through command line terminals. While this is  efficient and practical for coders, it's not quite necessary for writers. It's easier to work in something that has a GUI, like Github Desktop.<br>

## What Does Git Actually Do?

Git is a version control tool. It keeps track of every different version that you save of a file. With Git, you can easily track changes and collaborate with other people through forking, merging, branching, and pulling.

## What is Markdown?

Markdown is a plain text formatting syntax. It converts plain text to HTML code. It was developed to be simpler and more readable than HTML.

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

Go into GitHub Desktop, right-click on your repo, and select Open in Visual Studio Code. 
<br>

You can also open your repo through VS Code by going to File -> Open Folder and selecting the location of your GitHub repo on your device. 

Once you're in VS Code, open the Explorer tab and click the New File -IMAGE- button. Create a file called *test.md*.<br>
Try copying and pasting the following sample markdown template.

```
# Level 1 Heading

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

![This is alt text for an image.](https://terryoneil.github.io/images/cat.jpg)

This is a photo of the author's cat.
```

## Making A Local Commit

Save your markdown file and open Github Desktop. Click the checkmark on *test.md* to *stage* it. Write a summary to describe your changes, then press *Commit 1 file to main.* You've just done a *local commit*.

Making a local commit is like saving your progress in a video game; it's a great way to track changes. Use the summary and description boxes to provide additional context. This will make it easy to know which commit to revert to if necessary.


!!! tip

    In VS Code, you can easily preview your changes in real-time. Simply press `ctrl/cmd + shift + v` to open a markdown preview tab.

## Tracking Changes 

Now it's time to understand how to use Git as version control. In VS Code, within *test.md*, delete the first level 1 heading. Replace it with a level 4 heading.

```
#### This is A Level 4 Heading
```
Save your file and look in GitHub desktop. Notice how Git simply tracks edits by highlighting them in red and green. It tracks line-level deletions and insertions, which is traditionally very useful for tracking changes to code, but is also highly applicable for technical writing and documentation. 

## Pushing Changes

Finally, it's time to *push to main*. Stage *test.md* and commit it to main. Press Push Origin. 

!!! note
    *Origin* is Git's way of referring to the location a repo originally came from. When you Push Origin, you're pushing your branched copy of the repo onto the original repo. 

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

**Stage**
— To select a changed file to include in your next commit. Staging allows you select only the files you want to commit, instead of committing everything at once.

**Local Commit**
— A commit that isn't pushed to the main branch. It lives only on your local machine.