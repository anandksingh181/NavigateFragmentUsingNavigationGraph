//https://developer.android.com/guide/navigation
// https://developer.android.com/guide/navigation/design#xml

    implementation ("androidx.navigation:navigation-fragment-ktx:2.7.7")
    implementation ("androidx.navigation:navigation-ui-ktx:2.7.7")


      <androidx.fragment.app.FragmentContainerView
        android:id="@+id/nav_host_fragment"
        android:name="androidx.navigation.fragment.NavHostFragment"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
         app:defaultNavHost="true"
        app:navGraph="@navigation/nav_graph" />
