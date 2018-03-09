# PG Hybrid Boilerplate

Tabs (multiple views) Framework7 starter app template.

## Setup

1. Using ```git``` to download and serve boilerplate

```console
git clone https://github.com/clydeatuic/pgTabs my-app &&
cd my-app &&
npm install &&
npm run serve
```

2. Create a config.xml file

```xml
<?xml version='1.0' encoding='utf-8'?>
<widget id="uic.edu.ph" version="0.0.1" xmlns="http://www.w3.org/ns/widgets" xmlns:cdv="http://cordova.apache.org/ns/1.0">
    <name>UIC PG Demo Tabs</name>
    <description>
        A basic Framework7 template for PhoneGap.
    </description>
    <author email="dev@cordova.apache.org" href="https://uic.edu.ph/">
        Apache Cordova Team
    </author>
    <content src="index.html" />
    <access origin="*" />
    <allow-intent href="http://*/*" />
    <allow-intent href="https://*/*" />
    <allow-intent href="tel:*" />
    <allow-intent href="sms:*" />
    <allow-intent href="mailto:*" />
    <allow-intent href="geo:*" />
    <platform name="android">
        <allow-intent href="market:*" />
    </platform>
    <platform name="ios">
        <allow-intent href="itms:*" />
        <allow-intent href="itms-apps:*" />
        <preference name="BackupWebStorage" value="none" />
    </platform>
    <preference name="DisallowOverscroll" value="true" />

    <!-- Uncomment to use the latest, fastest iOS WebView (see this post http://devgirl.org/2016/01/11/a-faster-hybrid-app-for-the-new-year/) -->
    <!--<plugin name="cordova-plugin-wkwebview-engine" spec="~1.0.1" />-->

    <platform name="android">
        <icon src="res/icon/android/drawable-ldpi-icon.png" density="ldpi" />
        <icon src="res/icon/android/drawable-mdpi-icon.png" density="mdpi" />
        <icon src="res/icon/android/drawable-hdpi-icon.png" density="hdpi" />
        <icon src="res/icon/android/drawable-xhdpi-icon.png" density="xhdpi" />
        <icon src="res/icon/android/drawable-xxhdpi-icon.png" density="xxhdpi" />
        <icon src="res/icon/android/drawable-xxxhdpi-icon.png" density="xxxhdpi" />
        <splash src="res/screen/android/drawable-land-ldpi-screen.png" density="land-ldpi" />
        <splash src="res/screen/android/drawable-land-mdpi-screen.png" density="land-mdpi" />
        <splash src="res/screen/android/drawable-land-hdpi-screen.png" density="land-hdpi" />
        <splash src="res/screen/android/drawable-land-xhdpi-screen.png" density="land-xhdpi" />
        <splash src="res/screen/android/drawable-land-xxhdpi-screen.png" density="land-xxhdpi" />
        <splash src="res/screen/android/drawable-land-xxxhdpi-screen.png" density="land-xxxhdpi" />
        <splash src="res/screen/android/drawable-port-ldpi-screen.png" density="port-ldpi" />
        <splash src="res/screen/android/drawable-port-mdpi-screen.png" density="port-mdpi" />
        <splash src="res/screen/android/drawable-port-hdpi-screen.png" density="port-hdpi" />
        <splash src="res/screen/android/drawable-port-xhdpi-screen.png" density="port-xhdpi" />
        <splash src="res/screen/android/drawable-port-xxhdpi-screen.png" density="port-xxhdpi" />
        <splash src="res/screen/android/drawable-port-xxxhdpi-screen.png" density="port-xxxhdpi" />
    </platform>


</widget>

```

3. Go to Github and create a repo then upload your codes

4. Go to PG Build and create a public app then link your repo (master branch)

5. Open your QR Code Scanner (make sure to have an internet access) and install the app