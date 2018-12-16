Google Map SetUp

- Google Play Services
- Permissions
- API Key
- Check for Play Services
- Adding Map Fragments
- Initialize the Map

1. Go to >> SDK Manager >> SDK Tools >> install google play service

 For API Key : 
1. go to url:console.developers.google.com
2. unable API & Services
3. Maps SDK for Android
4. Manage
5. credentials
6. credentials in API Manager
7. create credentials >> API Key
8. Restrict Key
9. Android App >> add package name and fragment >> cd .android >> keytool -list -v -keystore mystore.keystore >>no password
10. Copy SH1 Key and paste >> save

11. AndroidManifest.xml >>  <meta-data android:name="API_KEY"
            android:value="AIzaSyDBQfcC7_dpTBbuUIjgeE8mSv6o9H9UlfI"/>
    </application>
