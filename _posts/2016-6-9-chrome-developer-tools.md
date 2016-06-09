---
layout: post
title: chrome developer tools
---
###The Chrome Developer Tools,
Are a set of web authoring and debugging tools built into Google Chrome. The DevTools provide web developers deep access into the internals of the browser and their web application. Use the DevTools to efficiently track down layout issues, set JavaScript breakpoints, and get insights for code optimization.
### Accessing the DevTools

To access the DevTools, open a web page or web app in Google Chrome. Either:

- Select the **Chrome menu** ![Chrome Menu](https://developer.chrome.com/devtools/images/chrome-menu.png) at the top-right of your browser window, then select **Tools** &gt; **Developer Tools**.
- Right-click on any page element and select **Inspect Element**.

The DevTools window will open at the bottom of your Chrome browser.

There are several useful shortcuts for opening the DevTools:

- Use 

Ctrl+

Shift+

I (or 

Cmd+

Opt+

I on Mac) to open the DevTools.
- Use 

Ctrl+

Shift+

J (or 

Cmd+

Opt+

J on Mac) to open the DevTools and bring focus to the Console.
- Use 

Ctrl+

Shift+

C (or 

Cmd+

Shift+
### The DevTools window

The DevTools are organised into task-oriented groups in the toolbar at the top of the window. Each toolbar item and corresponding panel let you work with a specific type of page or app information, including 

DOMelements, resources, and sources.

C on Mac) to open the DevTools in Inspect Element mode, or toggle Inspect Element mode if the DevTools are already open.
### Inspecting the DOM and styles

The **[Elements](https://developer.chrome.com/devtools/docs/dom-and-styles)** panel lets you see everything in one DOM tree, and allows inspection and on-the-fly editing of DOM elements. You will often visit the Elements tabs when you need to identify the 

HTML snippet for some aspect of the page. For example, you may be curious if an image has an HTML id attribute and what the value is.
### Improving network performance

The **Network** panel provides insights into resources that are requested and downloaded over the network in real time. Identifying and addressing those requests taking longer than expected is an essential step in optimizing your page.
### Audits

The Audit panel can analyze a page as it loads. Then provides suggestions and optimizations for decreasing page load time and increase perceived (and real) responsiveness. 

### Improving rendering performance

The **Timeline** panel gives you a complete overview of where time is spent when loading and using your web app or page. All events, from loading resources to parsing JavaScript, calculating styles, and repainting are plotted on a timeline.


### JavaScript & 

CSS performance

The **Profiles** panel lets you profile the execution time and memory usage of a web app or page. These help you to understand where resources are being spent, and so help you to optimize your code. The provided profilers are:

- The **CPU profiler** shows where execution time is spent in your page's JavaScript functions.
- The **Heap profiler** shows memory distribution by your page's JavaScript objects and related DOM nodes.
- The **JavaScript** profile shows where execution time is spent in your profile


### Inspecting storage

The **Resources** panel lets you inspect resources that are loaded in the inspected page. It lets you interact with HTML5 Database, Local Storage, Cookies, AppCache, etc.
