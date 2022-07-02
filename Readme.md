# A Github Query Project Application

## Tasks to be accomplished in this exercise :
- [x] Add a string resource called search with the title "Search".
- [x] Create a menu xml called 'main.xml' in the res->menu folder.
- [x] Add one menu item to your menu.
- [x] Give the menu item an id of @+id/action_search.
- [x] Set the orderInCategory to 1.
- [x] Show this item if there is room (use app:showAsAction, not android:showAsAction).
- [x] Set the title to the search string ("Search") from strings.xml.
- [x] Override onCreateOptionsMenu.
- [x] Within onCreateOptionsMenu, use getMenuInflater().inflate to inflate the menu.
- [x] Return true to display your menu.
- [x] Override onOptionsItemSelected.
- [x] Within onOptionsItemSelected, get the ID of the item that was selected.
- [x] If the item's ID is R.id.action_search, show a Toast and return true to tell Android that you've handled this menu click.
- [x] Don't forgot to call .show() on your Toast.
- [x] If you do NOT handle the menu click, return super.onOptionsItemSelected to let Android handle the menu click.


## Screenshots
1. Final Output of this Exercise

![img1](https://github.com/kuluruvineeth/CoreAndroidConcepts/blob/GithubRepoSearch/AddMenu/Screenshots/img.png)
![img2](https://github.com/kuluruvineeth/CoreAndroidConcepts/blob/GithubRepoSearch/AddMenu/Screenshots/img_1.png)
