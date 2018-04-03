# A collection of snippets for the Sublime Text Editor


## Installation
In order to be available in Sublime, the snippets have to be located in the Sublime package directory.
Depending on the OS, you can simply clone this git-repository into the respective Sublime Text package directory.

__Windows:__

Package location:

`C:\Users\<Username>\AppData\Roaming\Sublime Text 3\Packages\Snippets`

Git command:

`git clone https://github.com/firstdayofjune/sublime-text-snippets.git C:\Users\<Username>\AppData\Roaming\Sublime Text 3\Packages\Snippets`

__Mac OS X:__

Package location:

`/Users/<Username>/Library/Application Support/Sublime Text 3/Packages/Snippets`

Git command:

`git clone https://github.com/firstdayofjune/sublime-text-snippets.git /Users/<Username>/Library/Application Support/Sublime Text 3/Packages/Snippets`

__No git available?__

You can either download the latest version of git [here](https://git-scm.com/downloads) or simply download the snippets in a zipped folder [here](https://github.com/firstdayofjune/sublime-text-snippets/archive/master.zip) (or by selecting _Download Zip_, behind the the green _Clone or download_ button :sparkle::arrow_up:). The zip-archive then has to be unpacked and copied to the specific snippet folder (to the location mentioned above).

## Usage

The snippets are organized depending on their (file) contexts use case. The name of each snippet will tell you three things; First, in what context can the snippet be applied. Second, what does the snippet produce and third, what shortcut is used to trigger the snippet. The naming pattern therefore is: _{context}\_{hyphenated command outcome}\_{shortcut}.sublime-snippet_

If you consider the _tex_inline-quote_quol.sublime-snippet_ snippet, you can tell by the snippets name that:

1. The snippet can be used in LaTeX (_.tex_) files
2. The snippet is used for inline-quotation
3. The snippet is triggered by typing _quol_ and hitting tab

To make the html-snippets code-completaion available, `"auto_complete_selector": "source, text"` has to be added to the user settings file (Preferences > Settings - User).
