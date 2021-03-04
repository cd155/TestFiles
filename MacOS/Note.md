- Look at start up item in MacOS
    - Use `launchctl list` check every items launched.
    - Use `launchctl list | grep -v com.apple` check every items launched not belong to Apple.

- Remove start up items
    - Shift + Command + G, enter `/Library/LaunchDaemons`, remove unwanted items from start up.