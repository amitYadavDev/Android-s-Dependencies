dependencies {

    implementation 'androidx.core:core-ktx:1.10.1'
    implementation 'androidx.appcompat:appcompat:1.6.1'
    implementation 'com.google.android.material:material:1.9.0'
    implementation 'androidx.constraintlayout:constraintlayout:2.1.4'

    implementation "androidx.paging:paging-common-ktx:3.1.1"
    implementation 'androidx.paging:paging-runtime-ktx:3.1.1'

    implementation 'androidx.fragment:fragment-ktx:1.6.0'
    implementation 'androidx.lifecycle:lifecycle-viewmodel-ktx:2.6.1'
    implementation "androidx.lifecycle:lifecycle-viewmodel-ktx:2.6.1"
    implementation 'androidx.databinding:databinding-runtime:8.0.2'
    implementation 'androidx.swiperefreshlayout:swiperefreshlayout:1.1.0'

    implementation("com.google.dagger:hilt-android:2.44")
    kapt("com.google.dagger:hilt-android-compiler:2.44")

    implementation 'com.github.bumptech.glide:glide:4.15.1'

    implementation 'com.squareup.retrofit2:converter-gson:2.9.0'
    implementation 'com.squareup.retrofit2:retrofit:2.9.0'
    implementation "org.jetbrains.kotlinx:kotlinx-serialization-json:1.4.0"
    implementation 'com.squareup.okhttp3:logging-interceptor:4.11.0'

    testImplementation 'androidx.arch.core:core-testing:2.2.0@aar'
    testImplementation 'org.mockito:mockito-core:3.12.4'
    testImplementation 'junit:junit:4.13.2'
    androidTestImplementation 'androidx.test.ext:junit:1.1.5'
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.5.1'
    androidTestImplementation 'androidx.arch.core:core-testing:2.2.0'

}
