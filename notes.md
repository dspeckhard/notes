#Early Computing:
Computers few and far between, needed to allow for multiple users. Multiple terminals, etc. Also, initial adopters in 70s based on mainframe (single super server) and super computer models. User interface was minimal / slow. Most users were technically trained, many were programmers. The user interface and the programming environment were very similar, so many users dabbled in customizing the toolset. 

#Personal Computer Era:
The Home computer allowed for "instant" interaction (assuming neccessary hardware available) and new paradigms of what a computer could be applied to. But, also defined a one user / one machine paradigm that lasted until the mid to late 1990s when the web revitalized the client server model. Initial "homebrew" users were all programmers, or at least tinkerers. 

#Growth of the Commercial Software Market
As Home and (then Business) personal computers took off, users and businesses delegated the development of programs to specialists, either within or outside the organization. This led to the sepration of the user from the programmer, and the need for a programmer to understand the users needs / wants (because the programmer likely wasn't a specialist in the use case the program was meant to solve). It also meant that businesses (and software companies) needed to support non-technical users. This introduced overhead on how many iterations of code could be developed due to the code -> test -> document -> ship production cycle. 

#Desktop vs. Web Apps
Early 2000's, web software overtook desktop development speed based on
- open source OSs (reduced cost for more machines) 
- ease of maintaining Unix based OpenSource OSs
- fewer variables of OS / software (control whole stack except the browser)
- ability to ship code continously (no boxed product / CD pressing, etc., just change the code on the server)
- reduced nature of support required on user end
- Software as a Service business model
- Single interface standard (HTML) available across multiple devices

Most organizations have either moved completely to a web based software delivery for their business processes, or have wrapped legacy code in web front ends for users to interact with (i.e. banks). 

*The AEC Market is 5 - 10 years behind in adopting this revolution, due to need for 3d performance (not available on web based systems) and limited vendors (lockin to Autodesk), etc.*

#AJAX Revolution
Mid 2000's, development of asyncronous front end / back end decoupling allowed for increased User Interface speed, where the back end (server) served data, and the user interface occuered in the browser (more responsive). REST API approach (based on simpler HTML requests, rather than passing more complicated XML data between client and server) was particularly sucessful.

#JSON API / Microservices Revolution
AJAX design pattern created the need for / opportunity for a defined interface btw. the front end / backend code, which allowed for alternate code bases to intercept the data and do other things (other than just render it to HTML for user interface). Web "eco systems" developed, where backend data might be processed by multiple human (UI) or automatic (API / script) forms.

#Open APIs
If APIS are open and documented, the "eco system" can evolve - if the client doesn't work the way you want, build your own, based on the data backend, or smarter processing of the data, etc. Also allows for "composition" of services by putting pieces developed by multiple parties together.

#AEC Market
Moving AEC to a web-based, multiple party infrastruture:
Emerging standards:
- IFC (building / product data)
- BIMSIE (inter-operability)
- BCF (comment / issues /resolution)
