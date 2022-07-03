# A Toy Project Application

## Tasks to be accomplished in this exercise :
- [x] Create a layout resource in res/layout/ called number_list_item.xml.
- [x] Make the root layout a FrameLayout.
- [x] Make the width match_parent and the height wrap_content.
- [x] Set the padding to 16dp.
- [x] Add a TextView as the only child of the FrameLayout.
- [x] Give the TextView an ID "@+id/tv_item_number".
- [x] Set the height and width to wrap_content.
- [ ] Align the TextView to the start of the parent.
- [ ] Center the TextView vertically in the layout.
- [x] Set the font family to monospace.
- [x] Set the text size to 42sp.
- [x] Create a class called NumberViewHolder that extends RecyclerView.ViewHolder.
- [x] Within NumberViewHolder, create a TextView variable called listItemNumberView.
- [x] Create a constructor for NumberViewHolder that accepts a View called itemView as a parameter.
- [x] Within the constructor, call super(itemView) and then find listItemNumberView by ID.
- [x] Within the NumberViewHolder class, create a void method called bind that accepts an int parameter called listIndex.
- [x] Within bind, set the text of listItemNumberView to the listIndex.
- [x] Be careful to get the String representation of listIndex, as using setText with an int does something different.

## Screenshots
1. Final Output of this exercise

![img1](https://github.com/kuluruvineeth/CoreAndroidConcepts/blob/FavoriteToys/ViewHolder/Screenshots/img.png)
![img2](https://github.com/kuluruvineeth/CoreAndroidConcepts/blob/FavoriteToys/ViewHolder/Screenshots/img_1.png)

