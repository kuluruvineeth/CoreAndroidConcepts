# A EditTextPreference Constraints Application

Tasks to be accomplished in this exercise :
- [x] Implement OnPreferenceChangeListener.
- [x] Override onPreferenceChange. This method should try to convert the new preference value
      to a float; if it cannot, show a helpful error message and return false. If it can be converted
      to a float check that that float is between 0 (exclusive) and 3 (inclusive). If it isn't, show
      an error message and return false. If it is a valid number, return true.
- [x] Add the OnPreferenceChangeListener specifically to the EditTextPreference.