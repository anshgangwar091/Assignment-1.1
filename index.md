1. How a Website Works

When a user types a URL (Uniform Resource Locator) into a web browser such as Google Chrome, the browser first finds the IP address of the website using DNS (Domain Name System). The browser then sends an HTTP or HTTPS request to the web server. The browser acts as the client, which requests information, while the server receives the request and sends back the required response. If the website needs stored information, the server communicates with a database to retrieve or update data. HTTP stands for Hypertext Transfer Protocol, which is used to transfer data between a browser and a server, while HTTPS stands for Hypertext Transfer Protocol Secure, which encrypts the communication to protect data. This process is called the request-response cycle: the client sends a request, the server processes it, and the server returns a response containing HTML, CSS, JavaScript, images, or other data. The browser then interprets these files and displays the website on the screen. A static website displays mostly fixed content and usually serves the same information to every visitor, whereas a dynamic website can generate or change content according to user input, database information, or other conditions.

2. Difference Between Static and Dynamic Websites

Static Website

Dynamic Website

Displays mostly fixed content.

Content can change based on user actions or data.

Usually uses HTML and CSS.

May use HTML, CSS, JavaScript, and server-side technologies.

Content changes generally require editing the website files.

Content can be updated automatically using a server or database.

Example: A simple personal portfolio page.

Example: Amazon, Facebook, or an online banking website.

3. Basic Components of a Website

Browser: Software such as Chrome that requests and displays web pages.

Client: The user's device or application that sends requests to a server.

Server: A computer or software that processes requests and returns responses.

Database: Stores and manages information used by a website.

HTTP: A protocol used for communication between a client and a server.

HTTPS: A secure version of HTTP that encrypts communication.

4. Practical: Inspecting Requests Using Chrome DevTools

Objective: To observe the network requests made when a website loads.

Procedure:

Open Google Chrome.

Visit https://example.com.

Right-click anywhere on the webpage and select Inspect.

Open the Network tab in DevTools.

Reload the page using Ctrl + R.

Observe the requests that appear in the Network panel.

Click a request to inspect its details, such as the request URL, method, status code, and response headers.

Observation: The Network tab displays the resources requested by the browser while loading the website. These may include the main HTML document, CSS files, JavaScript files, images, and other resources. A successful request commonly returns a status code such as 200 OK.

Result: The request-response process of a website was studied using Chrome DevTools, and the Network tab was used to observe HTTP/HTTPS requests and their responses.

5. steps to Screenshot of the Network Tab

Open https://example.com in Chrome.

Press F12 or Ctrl + Shift + I.

Select the Network tab.

Reload the webpage.

Make sure the list of requests is visible.

Take a screenshot using Win + Shift + S.

Save the screenshot and insert it below this heading in your assignment.