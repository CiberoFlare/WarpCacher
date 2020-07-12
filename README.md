# PHP WarpCacher
A lightweight, small, effecient php script that makes a php webpage static from being a dynamic using cache strategies.
## Usage
Before any other codes, include the **warpcacher-start.php**.
```
<?php include "warpcacher-start.php";?>
```
After any other codes, include the **warpcacher-end.php**
```
<?php include "warpcacher-end.php";
```
## Files
| Filename | Uses |
| ------ | ------ |
| warpcacher-start.php | **The Preparer**, which means it prepare the main script by identifying cachetime, to-cache page, etc. |
| warpcacher-end.php | **The Executer**, which means it 'cached' the page and the one who does the work. |
