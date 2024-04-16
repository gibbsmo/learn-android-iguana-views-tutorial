# learn-android-iguana-views-tutorial

This branch follows the android developer tutorial found at the following link:
[Build Your First Android App in Kotlin](https://developer.android.com/codelabs/build-your-first-android-app-kotlin#0)


Easy tutorial in general, but the vertical/horizontal bias elements probably need a better tutorial than this one. Bigger open question is do design use views or navigation now for modern designs?

### Test Devices
- Pixel 3a emulator
- Pixel 3a phone (android v12)
- Samsung Galaxy S8 Tablet (android v14)


### Significant Deltas from Tutorial

The biggest issue is the color palette for the defaul app has changed making the color selections specified by the tutorial generate warnings.

1. Step 3.3: the default project for "Basic Activity" has changed - see snapshot below
2. Step 4.3: top layer is now a NestedScrollView in this tutorail (which contains the previous ConstraintLayout).
3. Step 4.7: icon menus for orientation and night mode have change - icons remains the same, menu options different.
4. Step 6: vertical orientataion of buttons and text view was swapped.  Just work around this.
5. Step 8: see Grale Kotlin Compile Directives below


delta snapshots:

<details>
  <summary>Default Project Options Modified</summary>

  ![image](https://github.com/gibbsmo/learn-android-iguana-views-tutorial/assets/167124614/06a9982f-a85c-40dd-ba3c-d37cb4cc7f59)
</details>

### Gradle Kotlin Compile Directives

Information in the tutorial is out-of-date.  You need to review the latest Android documentation to see how to add 'safe args' to the project.  This will affect both the project and top-level module gradle files.

[Enable Safe Args](https://developer.android.com/guide/navigation/use-graph/safe-args#kts)



## Final Screen shots (Pixel 3a)

![image](https://github.com/gibbsmo/learn-android-iguana-views-tutorial/assets/167124614/2c371acf-afe4-4796-adcd-ddce4939f0d8)


