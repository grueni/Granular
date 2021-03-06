# Granular - WPF for JavaScript!
Granular is a re-implementation of WPF, compiled to JavaScript, allowing WPF applications to run in the browser (using Saltarelle C# to JavaScript compiler).

### Why?
WPF defines many advanced UI concepts (such as visual / logical trees, layouts, routed events, resources, bindings and many others), and it also naturally supports MVVM and other UI patterns, with Granular we can enjoy all of them in the web.

### Features
Granular supports many of WPF features, such as xamls, templates, binding, animations and many others.    
A full list of the currently implemented features can [be found here](https://github.com/yuvaltz/Granular/wiki/Supported-features)

### Live demo
**[GranularPad](http://yuvaltz.github.io/granularpad)** is a good showcase of the current Granular framework capabilities.  
(Don't forget to inspect the visual tree in the DOM :)

### A small example of how it works
The following solution contains two projects:

1. WPF application - This is the project that's being developed and tested, in this case, it contains a window with templated buttons (which incorporates many of WPF capabilities).

2. Web application - Containing only links to the first WPF application files, it references Granular (instead of WPF) and it's being compiled to JavaScript using Saltarelle.

![Visual Studio - Solution window](http://yuvaltz.github.io/granular/wiki/tldr/solution.png)

This is what the **WPF application** looks like (as you would expect)

![WPF application window](http://yuvaltz.github.io/granular/wiki/tldr/wpf-application.png)

And this is what the **Web application** looks like (exactly the same, except it has a browser around it :)

![Web application window](http://yuvaltz.github.io/granular/wiki/tldr/web-application.png)

The main advantage of this approach is that the development and testing is done solely in Visual Studio, away from any browser or JavaScript debugger.  
Also there is no need to deal with all the html/css and fashionable JS frameworks mess, Granular exposes the WPF strong and well-defined APIs, and the whole development process is much cleaner and faster.

**Try it yourself - [sample solution sources](http://yuvaltz.github.io/granular/wiki/tldr/GranularApplication1.zip)**  

### Moving forward
Granular is still under development, and there are a lot of ways it can be moved forward. Any help from developers who are passionate about WPF (or *not-so-passionate* about the html/css ecosystem) would be much appreciated :)
