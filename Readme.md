# An onSaveInstanceState Application

Tasks to be accomplished in this exercise :
- [x] Create a static final key to store the query's URL.
- [x] Create a static final key to store the search's raw JSON.
- [x] Override onSaveInstanceState to persist data across Activity recreation.
- [x] Make sure super.onSaveInstanceState is called before doing anything else.
- [x] Put the contents of the TextView that contains our URL into a variable.
- [x] Using the key for the query URL, put the string in the outState Bundle.
- [x] Put the contents of the TextView that contains our raw JSON search results into a variable.
- [x] Using the key for the raw JSON search results, put the search results into the outState Bundle.
- [x] If the savedInstanceState bundle is not null, set the text of the URL and search results TextView respectively.

## Screenshots

![img1](https://github.com/kuluruvineeth/CoreAndroidConcepts/blob/5b.1-SaveResults/Screenshots/img.png)
![img2](https://github.com/kuluruvineeth/CoreAndroidConcepts/blob/5b.1-SaveResults/Screenshots/img_1.png)