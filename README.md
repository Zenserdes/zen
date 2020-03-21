# Zenserdes

## About
Nowadays, modern libraries are developed with performance as merely a secondary goal. However, utilizing extremely performance libraries (i.e. libraries written in C or assembly) from higher level languages (such as JS or Python) is often times a burden that developers simply don't care about, and shouldn't. Moreoever, existing libraries are typically unable to progress in performance due to their requirement of backwards compatibility.

Zenserdes is a project geared towards reversing this trend. **The Zerdes Project wishes provide appealing libraries to use with highly performant internals, to reverse the trend of developer waste** (which is understandable).  To achieve this goal, The *Zen of Zenserdes* has been established, as guidelines to follow.

## The Zen of Zenserdes

1. Public APIs are to be broken, if it results in performance.

   Too often have big existing libraries been chained from progress by the necessity of backwards compatibility. The Zenserdes Project says no more. If there are performance gains to be made, breaking the public API is *always* ok. A user of library from The Zenserdes Project should not expect backwards compatibility.

2. Boilerplate Free, to a Degree.

   Many popular serialization librarires require the user to setup lots of boilerplate before they can even be ran. This is extra code that the user has to write, and extra code that must run, degrading performance. The library should offer simplistic ways to *stay out of the way of the user*. The user's time is important to them, and the less documentation they need to read, the less documentation that needs to get written. Of course, sometimes boilerplate is a necessity for performance, of which there should always be the optional route of allowing.

3. Writtten for Excellence.

   Sometimes it is a necessity for a company to produce targets in other languages. Whilst these libraries are completely usable, thoroughly tested, and well planned, their performance may be suboptimal compared to a library written by someone who knows the language inside out. The goal of Zenserdes is to produce high performing serialization libraries.

## Who is behind The Zenserdes Project?

**You!** Shape the future today by providing high performing libraries in your favorite language, today. Of course, you've never needed to be a part of The Zenserdes Project to do so, but perhaps it might be beneficial that your users know what they're getting into when they use a Zenserdes library.

If you'd like to help out, file an issue on this repository so I can get in touch!
