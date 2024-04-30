# fix-query-all-package-permission
Ignore Query All Permission When Publishing app to google Play Store


<manifest xmlns:android="http://schemas.android.com/apk/res/android"
  xmlns:tools="http://schemas.android.com/tools"
  package="com.example">

  <!-- Permissions -->
  <uses-permission android:name="android.permission.INTERNET" />
  <uses-permission android:name="android.permission.QUERY_ALL_PACKAGES" tools:node="remove" />

</manifest>
