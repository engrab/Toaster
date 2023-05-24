# Toaster
This is toaster library for demo of creating libaray.
To get a Git project into your build:
Step 1. Add the JitPack repository to your build file
gradle
Add it in your root build.gradle at the end of repositories:
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
  Step 2. Add the dependency
  gradle
  dependencies {
	        implementation 'com.github.engrab:Toaster:Tag'
	}
