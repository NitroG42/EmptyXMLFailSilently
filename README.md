# EmptyXMLFailSilently

**With an empty XML file ic_arrow_2.xml** :

```
./gradlew assembleDebug
> Task :app:processDebugResources FAILED

FAILURE: Build failed with an exception.

* What went wrong:
Execution failed for task ':app:processDebugResources'.
> A failure occurred while executing com.android.build.gradle.internal.tasks.Workers$ActionFacade
   > Android resource linking failed
     /Users/nitrog42/Workspace/droid/EmptyXMLFailSilently/app/src/main/res/mipmap-anydpi-v26/ic_launcher.xml:3: AAPT: error: resource drawable/ic_launcher_background (aka com.nitrog42.emptyxmlfailsilently:drawable/ic_launcher_background) not found.
         
     /Users/nitrog42/Workspace/droid/EmptyXMLFailSilently/app/src/main/res/mipmap-anydpi-v26/ic_launcher_round.xml:3: AAPT: error: resource drawable/ic_launcher_background (aka com.nitrog42.emptyxmlfailsilently:drawable/ic_launcher_background) not found.
         

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output. Run with --scan to get full insights.

* Get more help at https://help.gradle.org

BUILD FAILED in 2s
8 actionable tasks: 1 executed, 7 up-to-date
```
