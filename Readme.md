# A Toy Project Application

## Tasks to be accomplished in this exercise :
- [x] Add an interface called ListItemClickListener.
- [x] Within that interface, define a void method called onListItemClick that takes an int as a parameter.
- [x] Create a final private ListItemClickListener called mOnClickListener.
- [x] Add a ListItemClickListener as a parameter to the constructor and store it in mOnClickListener.
- [x] Implement OnClickListener in the NumberViewHolder class.
- [x] Override onClick, passing the clicked item's position (getAdapterPosition()) to mOnClickListener via its onListItemClick method.
- [x] Call setOnClickListener on the View passed into the constructor (use 'this' as the OnClickListener).
- [x] Implement GreenAdapter.ListItemClickListener from the MainActivity.
- [x] Create a Toast variable called mToast to store the current Toast.
- [x] Override ListItemClickListener's onListItemClick method.
- [x] In the beginning of the method, cancel the Toast if it isn't null.
- [x] Show a Toast when an item is clicked, displaying that item number that was clicked.
- [x] Pass in this as the ListItemClickListener to the GreenAdapter constructor.
- [x] Pass in this as the ListItemClickListener to the GreenAdapter constructor.


## Screenshots
1. Final Output of this exercise

![img1](https://github.com/kuluruvineeth/CoreAndroidConcepts/blob/FavoriteToys/RecyclerViewClickHandling/Screenshots/img.png)