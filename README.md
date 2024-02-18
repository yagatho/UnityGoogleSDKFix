# UnityGoogleSDKFix
"The developer of androidx.fragment:fragment has reported version 1.0.0 as outdated" Error fix


1) Create a folder Assets/Editor

2) Add a file i sent you to the folder you just created

3) Download https://github.com/googlesamples/unity-jar-resolver#android-resolver-usage and import to the Unity Project (.unitypackage file)

4) Force Resolve (Assets > External Dependency Manager > Android Resolver > Force Resolve)

5) Then remove {yourProject}/Libraries/Bee/Android folder (if you have this one)

6) Build
