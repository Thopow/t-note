# T-NOTE and the Bash-UI-Toolkit

T-NOTE is a pure bash script application. It store all notes as separate text files so you can also use it to note scripts of any kind.

I created the toolkit to make my live easier. And I use it for different scripts. The best way to find out what it do you can run it by it self.

## Installation 
The easiest way is to copy both scripts in your ${PATH} direction. Then you can run T-Note with `tn` in your Terminal.
( I did a keyboard shortcut <${TERMINAL} -e tn> )

## How to

Most functions are self explaining. However some functions are not full developed yet. For example the TAG management and the Change Notebook.

- Change Notebook: You can use any folder on your system to be your Notebook. But at this time it not change the default Notebook. If you like to do so you need to change line 10 of the script.
- TAG's are at this time just extensions to the title and made by using _tag_anothertag. And you can search them with Search Title.
Functionality for this is in progress. 

Use of bash-ui-toolkit:

You just use instead of <echo "blablabla"><print_c "blablabla"> or <print_r "blabla">.
To draw a line <print_c "-" "-"> you can use any symbol or letter.
Use <print_b "some text ....."> for single line box. <print_bc><print_br>
Multi line box <print_mlb "hi" "this is" "some more text" > <print_mlbc><print_mlbr>
and last <banner "#" "your text"><banner_c><banner_r> The first argument set the symbol.

Thanks for the use and I'm happy to get your feed back at:
https://www.reddit.com/user/ToPow1 
