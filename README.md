# Where do I begin 

Please see [INSTALL.md](./Install.md) to get started with the setup.


# Why so many files

Please go through the [first ten commits](https://github.com/sentry-demos/sentry_react_native/commits/master) (and their git log) messages in chronological order, to see the exact commands that were run, set by step, to get all the autpgenertaed files need keeping in mind that "junk" does not belong in an SCM system. 

Turns out react-native generates it owne gitignore, which is of course part of this repo, so only the those autogenerated files that were needed for the having a baseline set up and the original demo code files are in this repo. So now we are at point, where one can simply clone, make a few edits and like DSN, project name, auth token and be up and running.


# Where's the "original" code

Adam worked on App.js which I took as is from him. Plus 2 image files in the assets dir (which are also present in "original" react-native demo org)


# What else 

It appears to me we wanted to start fresh to create this demo. And while this was a good learning excercise as we expand our demo offering, I would like to "learn/see" how far off was the [original react-native repo ]( https://github.com/sentry-demos/react-native/commit/269f58d63426065a4de67a3f22d2e774787cd996)

Since the assets are taken from there, it makes me wonder a part/whole of it should already be working. I will investigate that as time permits. 



