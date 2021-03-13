# README
I have never really liked how much of a pain it is to get up and running with C# plugins when it comes to Rainmeter since you need to reorg the whole examples that are given or start for a blank .dll project but then have a dozen settings that need changed, files that must be imported, and build events that must be added. That is also before we get into that the example are missing basic settings that really should be changed and other build events that should be there to make deploy and debugging far easier.  

## Features:
Auto ILMerge of all referenced .dlls (Note to self if none are used you will get error that mscorlib can not be merged until you turn off the ILMerge plugin)  
Build events to run the dllexporter of final merged .dll so it will play nice with unmanaged code  
Auto kill of Rainmeter before export  
Auto copy of final .dll to plugins dir  
~~A button that gives you a million dollars~~