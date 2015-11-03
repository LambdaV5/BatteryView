# BatteryView
[ ![Download](https://api.bintray.com/packages/iamyours/maven/BatteryView/images/download.svg) ](https://bintray.com/iamyours/maven/BatteryView/_latestVersion)
## Gradle
```
compile 'com.iamyours.ui:BatteryView:0.1.2'
```
## example
```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:orientation="vertical" android:layout_width="match_parent"
    android:layout_height="match_parent"

    >
    <com.roger.batteryview.BatteryView
        android:layout_marginTop="50dp"
        android:layout_marginLeft="50dp"
        android:layout_width="30dp"
        android:layout_height="60dp"
        app:batteryColor="@color/colorPrimary"
        app:batteryOrientation="vertical"
        app:percentage="50"
        android:background="#ccc"
        />
    <com.roger.batteryview.BatteryView
        android:layout_marginTop="50dp"
        android:layout_marginLeft="50dp"
        android:layout_width="120dp"
        android:layout_height="60dp"
        app:batteryColor="@color/colorPrimary"
        app:batteryOrientation="horizontal"
        app:percentage="75"
        android:background="#ccc"
        />
</LinearLayout>
```
![image](1.png)
##License
Copyright 2015 Roger.
Licensed under the Apache License, Version 2.0 (the "License"); 
you may not use this file except in compliance with the License.
You may obtain a copy of the License at
[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)
Unless required by applicable law or agreed to in writing, 
software distributed under the License is distributed on an "AS IS" BASIS, 
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and limitations under the License.
