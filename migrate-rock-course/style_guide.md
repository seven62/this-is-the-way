# MOCYBER Docs Style Guide

Refer to this style guide for information on how to format documentation

## General Style

* **Menu Navigation** - Italics, separated by `->` (e.g., "Click on *File -> New -> New Rule...*")
* **Keyboard Shortcuts** - Italics (e.g., "Press *Command + Shift + Q* to log out.")
* **Buttons** - Bold (e.g., "Click **OK**")
* **Checkboxes** - Italics (e.g., "Ensure that *Restart when complete* is checked before continuing")
* **Radio Buttons** - Italics (e.g., "Select *Yes*, then click **Next**")
* **Tabs** - Italics (e.g., "Click on the *Settings* tab")
* **Web Links** - Bold (e.g. "Click on **Register New Node** to add a new node")
* **The Oxford Comma** - Know it. Love it.  

>"I'd like to thank my parents, Ayn Rand and God."

  Don't be that guy.

* **Notes** - Bold & Italic "Note:" (that's 3 asterisks), then italicized text (e.g.,  "***Note:*** *You may need to refresh the page to see the change.*")

## Lists

* When creating an ordered list, use `1.` for every item in the list, and allow the markdown interpreter to render the numbers properly.
* For unordered lists, use `*` for each item

## Inline Monospace/Code Highlighting

Use monospace highlighting in the following cases:

* filenames/paths
* hostnames/IP addresses
* usernames
* passwords
* CLI commands (include the appropriate prompt [i.e., "`$`" or "`C:\>`"])

## Fenced code blocks

Use fenced blocks (preceded and followed by 3 backticks) to enclose large blocks of CLI output, code examples/samples/excerpts, etc.

You can specify a language immediately following the opening fence to invoke context highlighting.

**Shell output:**
```
$ git push
Counting objects: 4, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 512 bytes | 0 bytes/s, done.
Total 4 (delta 3), reused 0 (delta 0)
```

**JSON:**
```json
{
    "menu": {
        "id": "file",
        "value": "File",
        "popup": {
            "menuitem": [
                {
                    "value": "New",
                    "onclick": "CreateNewDoc()"
                },
                {
                    "value": "Open",
                    "onclick": "OpenDoc()"
                },
                {
                    "value": "Close",
                    "onclick": "CloseDoc()"
                }
            ]
        }
    }
}
```

## External Resources

* [Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [Markdown (Bitbucket-flavored) Reference](https://bitbucket.org/tutorials/markdowndemo/overview)
* [Markdown Table Generator](http://www.tablesgenerator.com/markdown_tables)