debug:
	./gradlew DSD

release:
	./gradlew DSR

clean:
	./gradlew clean

uninstall:
	adb uninstall com.android.demo

md5:
	./gradlew md5

GodzUDB:
	./gradlew :Godzilla:UpdateDataBugly

UTUDB:
	./gradlew :UnityfakeRelease
	./gradlew :unityfake:UpdateDataBugly
	./gradlew md5

bugly:
	adb install -t tools/bugly_base/app-debug.apk

pipinstall:
	./gradlew pipInstall



