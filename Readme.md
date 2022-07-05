# An AsyncTaskLoader Application

Tasks to be accomplished in this exercise :
- [x] implement LoaderManager.LoaderCallbacks<String> on MainActivity.
- [x] Create a constant int to uniquely identify your loader. Call it GITHUB_SEARCH_LOADER.
- [x] Override onCreateLoader.
- [x] Return a new AsyncTaskLoader<String> as an anonymous inner class with this as the constructor's parameter.
- [x] Override onStartLoading.
- [x] If args is null, return.
- [x] Show the loading indicator.
- [x] Force a load.
- [x] Override loadInBackground.
- [x] Get the String for our URL from the bundle passed to onCreateLoader.
- [x] If the URL is null or empty, return null.
- [x] Copy the try / catch block from the AsyncTask's doInBackground method.
- [x] Override onLoadFinished.
- [x] Hide the loading indicator.
- [x] Use the same logic used in onPostExecute to show the data or the error message.
- [x] Override onLoaderReset as it is part of the interface we implement, but don't do anything in this method.
- [x] If no search was entered, indicate that there isn't anything to search for and return.
- [x] Remove the call to execute the AsyncTask.
- [x] Create a bundle called queryBundle.
- [x] Use putString with SEARCH_QUERY_URL_EXTRA as the key and the String value of the URL as the value.
- [x] Call getSupportLoaderManager and store it in a LoaderManager variable.
- [x] Get our Loader by calling getLoader and passing the ID we specified.
- [x] If the Loader was null, initialize it. Else, restart it.
- [x] Initialize the loader with GITHUB_SEARCH_LOADER as the ID, null for the bundle, and this for the callback.
- [x] Remove the code that displays the JSON.
- [x] Remove the code that retrieves the JSON.
- [x] Remove the code that persists the JSON.
- [x] Remove the key for storing the search results JSON.
- [x] Delete the AsyncTask class.

## Screenshots

![img1](https://github.com/kuluruvineeth/CoreAndroidConcepts/blob/5b.2-AddAsyncTaskLoader/Screenshots/img.png)
![img2](https://github.com/kuluruvineeth/CoreAndroidConcepts/blob/5b.2-AddAsyncTaskLoader/Screenshots/img_1.png)