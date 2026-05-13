RL Zone Finder Android APK Project, fixed Gradle version

This version fixes the Gradle build failure at app/build.gradle line 26 by using proper Groovy syntax.

Upload the CONTENTS of this folder to the repository root.

Your repository root must show:
.github
app
README_BUILD_APK.txt
build.gradle
settings.gradle

Build:
1. Go to Actions.
2. Run Build Android APK.
3. Download artifact rl-zone-finder-apks.
4. Extract it.
5. Install RL-Zone-Finder-release.apk first.

Features:
- normal search box, no autocomplete preview
- driving-distance calculation
- zone classification
- zone rates:
  Zone 1: Rs 1,200
  Zone 2: Rs 1,600
  Zone 3: Rs 2,000
  Zone 4: Rs 2,500
