Repo of the code used for this article https://medium.com/@not.achraf/sharing-a-state-between-windows-without-a-server-6d5c1716cbc8

https://notachraf.substack.com/


It is inspired by https://twitter.com/_nonfigurativ_/status/1727322594570027343
Some notes from his tweets:
 - three.js with custom gpgpu particle system. Windows are connected via localConnection
 - Q: How do the windows know their proximity? A: window.getScreenDetails() + localStorage
