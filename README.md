   implementation('com.squareup.retrofit2:retrofit:2.7.2') {
        // exclude Retrofit’s OkHttp dependency module and define your own module import
        exclude module: 'okhttp'
    }
    implementation 'com.google.code.gson:gson:2.8.6'
    implementation 'com.squareup.retrofit2:converter-gson:2.7.2'
    implementation 'com.squareup.okhttp3:logging-interceptor:3.4.1'
    implementation 'com.squareup.okhttp3:okhttp:3.14.7'
