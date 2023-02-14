
# Notes

This project was originally cloned from [https://github.com/MicrosoftDocs/mslearn-dotnetmaui-create-multi-page-apps](https://github.com/MicrosoftDocs/mslearn-dotnetmaui-create-multi-page-apps). It is part of the 
[Create multi-page .NET MAUI apps with tab and flyout navigation](https://learn.microsoft.com/en-us/training/modules/create-multi-page-apps/) learning module, which is part of the [Build mobile and desktop apps with .NET MAUI](https://learn.microsoft.com/en-us/training/paths/build-apps-with-dotnet-maui/) learning path. 

The modules includes tab, flyout, and stack navigation. 

Tab and flyouts are useful for pages/data that have a peer relationship, like the sun and moon pages.  

Stack navigation is useful for pages/data that is hierarchical so a user can drill-down into the data. Like country > state/province > city relationship for data. 

URIs and routes are used in .NET MAUI to provide navigation within an app.  It seems simlar to navigating around the WWW with a web browser, or routes in ASP.NET MVC.   Routes also can use query parameters, much like a URL with a query string. E.g. `await Shell.Current.GoToAsync($"astronomicalbodydetails?bodyName={celestialName}");`