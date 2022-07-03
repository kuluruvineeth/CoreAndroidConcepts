# A Toy Project Application

## Tasks to be accomplished in this exercise :
- [x] Add a String for the title of the menu item, "Reset".
- [x] Create a menu resource in res/menu/ called main.xml.
- [x] Add one item to the menu with an ID of action_refresh.
- [x] Set the title of the menu item to "Refresh" using strings.xml.
- [x] Set the orderInCategory value to 1 to make sure this item is the first in the list.
- [x] Set app:showAsAction to ifRoom to display the menu item in the ActionBar if there is room.
- [x] Override onCreateOptionsMenu.
- [x] Use getMenuInflater().inflate to inflate the menu.
- [x] Return true to display this menu.
- [x] Override onOptionsItemSelected.
- [x] Within this method, get the ID from the MenuItem.
- [x] If the ID equals R.id.action_refresh, create and set a new adapter on the RecyclerView and return true.
- [x] For now, for all other IDs, return super.onOptionsItemSelected.


## Screenshots
1. Final Output of this exercise

![img1](https://github.com/kuluruvineeth/CoreAndroidConcepts/blob/FavoriteToys/RefreshMenuButton/Screenshots/img.png)