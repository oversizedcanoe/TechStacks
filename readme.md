# Tech Stacks
The purpose of this repo is to list out my preferred languages, libraries, and tools to use for projects. I tend to forget which ones I've used in the past, and  why I chose them, so I'm hoping this will help with the inevitable analysis paralysis that comes with starting a project. I also want to add things I'd like to try in the future.

---

### Front End

 - For large, complex, feature rich websites, Angular is my framework of choice. The batteries included approach to everything, from routing, HTTP requests, and *especially* Dependency Injection, is hard to beat when developing a dynamic, interactive application.
   - I use the Angular CLI to start and develop Angular apps.

 - For smaller -- but still dynamic and interactive -- websites, I have been enjoying React. I know it is fully capable of being used for larger projects (case in point: FaceBook), but for things larger than a hobby site/app I prefer Angular for the reasons above. By keeping the TS and HTML in a single file (unlike Angular), it nudges me to write smaller, simpler components.
   - I have had success using Vite to start and develop React apps.

 - For static websites, I have been using Astro. It has great DX, runs fast, codes similar to React, and probably does a bunch of stuff I don't even know about. I don't think it would be great for a 'Web Application'-type website, but for content-focused sites it works great. I'd like to try out their [templates](https://github.com/withastro/astro/tree/main/examples) one day.

 - Blazor is a wild card. I won't use Blazor unless I specifically have a .NET backend (is it even possible to use a non-C# backend...?). For building an MVP, it's fantastic. I'm not sure how well it would scale with tons of features or interactivity requirements. In my relatively inexperienced opinion, it's got a specific use case as a basic front end for some sort of .NET service or class library. Blazor WASM could definitely help improve this, though.

##### CSS
- I mainly have experience with Bootstrap. I've toyed around with other libraries a handful of times but none of them have ever stuck.
- I've recently tried Pure CSS and it seems useful for simple websites.
- I'd like to try out other CSS libraries in the future, ideally ones which provide components and layout functionality like Bootstrap. A few I'd like to try are Tailwind CSS (or maybe Daisy UI) and Materialize.

### Back End
- For large, complex, feature rich applications, .NET (using C#) is my framework of choice. *Yes, I copied the first sentence from the Angular section.* .NET feels the same as Angular in the sense that it has built in libraries for almost everything, and a great package manager for things it doesn't. Entity Framework Core is also amazing to work with. Whether it is a class library, background service, MVC, or Web API, .NET is my #1.
- For smaller backend applications, including small scripting tasks, I like Python. For APIs specifically, I have used Falcon. It is quick to get up and running, and does the job.

### Database
- For complex projects, I like using SQL Server. It is feature rich and dependable.
- For simple projects and MVPs, I like using SQLite.
- I'd like to try a NoSQL database in the future.

### Desktop
- I don't really build desktop apps. I have experence with WinForms and WPF but that's about it.
- I'd like to try something with Electron in the future.

### Native
- I only have (extremely limited) experience building native apps with Ionic. I didn't do much with it, but it was nice and easy to use.
- I'd like to try Expo and/or React Native in the future.
