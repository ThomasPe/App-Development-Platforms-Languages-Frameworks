App Development: An Interactive Visualization Of Platforms, Languages & Frameworks
================

<a href="http://thomaspe.github.io/App-Development-Platforms-Languages-Frameworks/">View the interactive chart of how platforms, languages and frameworks work together in the app development world.</a>


The data must be a matrix of dependencies. Link Platforms, Languages and Frameworks that work together.

    var data = {
      nodes: 	['C#', 'Windows', 'Xamarin', WinJS],
      matrix: 
      [[0, 1, 1, 0], // C# works on Windows with Xamarin
      [0, 1, 1, 1], // On Windows you can write apps using C#, Xamarin & WinJS
      [1, 1, 0, 0], // Xamarin apps can be written in C# and work on Windows
      [0, 1, 0, 0]] // WinJS is a Framework for Windows
    };


All this work is based on the <a href="http://www.redotheweb.com/DependencyWheel/">DependencyWheel</a>, published by <a href="https://twitter.com/francoisz">François Zaninotto</a> under the MIT license.
