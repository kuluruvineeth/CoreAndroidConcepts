# Setting up the PreferenceScreen Fragment and CheckedPreference Application

Tasks to be accomplished in this exercise :
- [x] Add the gradle dependency for the support preference fragment.
- [x] Create a class called SettingsFragment that extends PreferenceFragmentCompat.
- [x] In res->xml create a file called pref_visualizer.
- [x] In pref_visualizer create a preference screen containing a single check box preference This check box preference should have a default value of true, the key 'show_bass', a summaryOff of Hidden, a summaryOn of Shown and a title of 'Show Bass'.
- [x] In SettingsFragment's onCreatePreferences method add the preference file using the addPreferencesFromResource method.
- [x] Add a theme for the preference.
- [x] Set the root layout of activity_settings to our newly created SettingsFragment.


## Screenshots

![img1](https://github.com/kuluruvineeth/CoreAndroidConcepts/blob/6.2-MakeAPreferenceFragment/Screenshots/img.png)
![img2](https://github.com/kuluruvineeth/CoreAndroidConcepts/blob/6.2-MakeAPreferenceFragment/Screenshots/img_1.png)
![img3](https://github.com/kuluruvineeth/CoreAndroidConcepts/blob/6.2-MakeAPreferenceFragment/Screenshots/img_2.png)
![img4](https://github.com/kuluruvineeth/CoreAndroidConcepts/blob/6.2-MakeAPreferenceFragment/Screenshots/img_3.png)