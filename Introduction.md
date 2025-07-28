**Asp.Net Core - Learning - Handy Notes.**

for course the course project repo: https://github.com/Harsha-Global/AspNetCore-Harsha

**below is my running notes**

1. Kestral server is a cross-platform web server for ASP.Net core, It is lightweight and suitable for serving dynamic content. Ideal for development and internal networks. Typically used in conjunction with a reverse proxy for production environments.
   
   _Responsibilities:_
   
         HTTP Requests Handling: Handles incoming HTTP requests and responses
         Hosting: Hosts the ASP.NET Core application.
         Configuration: Supports various configurations such as HTTP/2, HTTPS, etc.
2. Reverse Proxy Servers : A reverse proxy server forwards client requests to backend servers and returns the responses to the clients. Common reverse proxy servers include Nginx, Apache, and IIS.
   
   _Responsibilities:_
   
         Load Balancing: Distributes incoming requests across multiple servers.
         SSL Termination: Handles SSL/TLS encryption and decryption.
         Caching: Caches responses to improve performance.
         Security: Provides additional security features like request filtering, IP whitelisting, and rate limiting.
3. Responsibilities of Kestrel and Reverse Proxy Servers
   
    _Kestrel:_
   
           Serves HTTP requests directly.
           Provides efficient request processing.
           Should be used behind a reverse proxy for additional security and stability.
   
     _Reverse Proxy:_
   
           Acts as an intermediary between clients and Kestrel.
           Provides SSL termination, load balancing, and security features.
           Enhances the overall performance and security of the application.
           _Benefits of Reverse Proxy Servers_
                         Load Balancing, Caching, URL Rewriting, Decompressing the requests, Authentication, Decryption of SSL Certificates
           _IIS express_
                         HTTP access logs, Port sharing, Windows authentication, Management console, Process activation, Configuration API, Request filters, HTTP redirect rules
   
4. launchSettings.json - is a configuration file in ASP.NET Core projects used to define settings for how the application is launched during development. This includes settings for different environments, URLs, and other debugging options.
   
     configures how an ASP.NET Core application is launched during development.
     It can define multiple profiles, each with its own settings for URLs, environment variables, and launch options.
     The iisSettings section configures IIS Express settings, while the profiles section defines different launch profiles for the application.
5.  
