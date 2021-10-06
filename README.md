# VedioPayer

Abstract
⮚	We will be building a simple application in which we will be building a simple Vedioplayer where we can Play any vedios that we have present in our internal storage. And also have a swipe forward-backward function and swipe up to inc-dec volume function.

⮚	And it’s a java based project.


Technology Used

⮚	Better Player dependency to play vedios.

maven { url 'https://jitpack.io' }

Add this in your module's build.gradle file:
dependencies {
    // ... other dependencies add in app level dependency
    implements 'com.github.halilozercan:BetterVideoPlayer:kotlin-SNAPSHOT'
}



⮚	And DEXTER Library for Permmsion.

implementation 'com.karumi:dexter:6.2.3'




