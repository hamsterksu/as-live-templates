as-live-templates
=================

android live tempates for Android Studio / Intellij IDEA. 

## Installation

android.xml file should be placed in the following location:

###**Windows:** 
```
<your home directory>\.<product name><version number>\config\templates
```

###**Linux:**
```
~\.<product name><version number>\config\templates
```


###**MacOS:** 
```
~/Library/Preferences/<product name><version number>/templates
```

### Templates list

* ns-app - Add **res-auto** namespace (*XML*)
* ns-android - Add **android** namespace (*XML*)
* ns-tools - "Add **tools** namespace (*XML*)
* ttext - Add **tools:text** attribute (*XML*)

* toast - show toast
* findcast - **findViewById** and cast

* CREATOR - creator for Parcelable

* f_ns - declare **NAMESPACE** constant in class
* f_arg - declare fragment argument: **NAMESPACE + ARGNAME**
* f_new - generate **newInstance** method for fragment
* f_new_args - generate **newInstance** method with **Bundle** and **setArguments**
