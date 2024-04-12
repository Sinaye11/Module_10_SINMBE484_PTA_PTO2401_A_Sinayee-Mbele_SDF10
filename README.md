## [SDF10] API Learning Reflection 🧠

Welcome to the [SDF10] API Learning Reflection! Through this exercise, you will reflect on key concepts, practical experiences, and the tools you've encountered or used in API interactions.

1. **Understanding and Application**: Reflecting on the key concepts, can you explain in your own words what an API is and its significance in software development? Provide an example of how you have used or encountered an API in a project or a practical scenario.

[	API is an acronym for Application Programming Interface, it contains a set of rules and protocols which enable different software applications to interact with each other. They can be seen as a bridge allowing data exchange and interaction between different software components to work concurrently. APIs are important in software development as they can be blended with new applications with existing software systems. Allowing developers to build upon existing functionalities without having to start from scratch, increases development speed. 

A real-world scenario, utilizing a mobile app to get the latest headline news for a user. Instead of building an independent news system, one may utilize an API like Google News API and integrate it to the news system, as it will fetch, parse, and display the most recent news articles to users. A simple inclusion like this saves a tremendous amount of development time while delivering accurate relevant, up-to-date content.]

2. **Conceptual Distinctions**: How would you differentiate between an interface and an API? 

[	An interface is best described as a point where two things meet and interact, and can be seen as a contract that stipulates how a component can be accessed.  They define a set of methods that a class can provide. 

An Application Programming Interface (API) is a mechanism that allows two software components to talk to each other using a set of protocols.

Therefore the difference is that an interface defines a set of methods that a class will have to implement, focused on defining behavior however an API provides a much broader set of rules and tools for building software, to allow interaction between different components. Interfaces are a part of APIs but APIs encompass a much broader scope of functionalities and interactions. ]

3. **Components and Types of APIs**: Can you identify the main components of an API and describe their roles? Reflect on the different types of APIs mentioned (e.g., Web APIs, RESTful APIs) and discuss which type you find most intriguing or useful, and why.

[ The main components of an API and their roles:
•	API Endpoints: These are URLs that represent specific resources or functionalities that are provided by the API. Every endpoint serves a certain purpose, like retrieving data, performing actions, and executing operations within the system.

•	HTTP Request Methods: Used by APIs to show the desired action to perform for an endpoint.  Common methods include GET(retrieves resources), POST(creates new resources) PUT(updates an existing resource) and. DELETE(deletes a resource) 

•	Parameters: additional data that is provided along with API requests that modify the behavior of the requested operation or filter and refine returned results. These can be put in the URLs, request headers, and query strings, however, this is all dependent on the API's design and conventions.

•	Request and Response Formats: APIs define the format in which clients should send requests and expect responses. Well-known formats are JSON(JavaScript Object Notation) and XML(eXtensible Markup Language) 

•	Authentication and Authorization: A lot of APIs require authentication to be granted access to the protected resources. The authentication mechanism like API Keys guarantees that only authorized users may  interrelate with the API. The authorization mechanism defines set protocols and access rights that will be granted to an authenticated user, this will control their ability to write, read, or make any modification to the resources. 

•	Documentation: This just simply provides well-detailed information about the available endpoints, required parameters, authentication requirements, and usage examples. Documented APIs make it easier for developers to combine with the API and build applications that leverage its capabilities. 

I find Restful APIs more useful as opposed to other APIs. These APIs provide a standard approach to designing web APIs, which promotes simplicity scalability, and interoperability. They make use of HTTP protocols and provide an advantage to existing web infrastructure  which makes it easy to understand, utilize, and use with other systems. RESTful APIs provide a robust foundation that builds distributed systems and allows for seamless communication between different software components.]

4. **Practical Application and Tools**: Reflect on your experience with API exploration and implementation. Have you used any specific tools (such as Curl or API exploration tools) or libraries to interact with APIs? 

[Learning about APIs has opened a whole new perspective when it comes to software development. The fact that one can get data, do certain actions and integrate that with different platforms whilst using a few lines of code is mind-blowing. The tool I have made use of is CURL and worked with Twilio. I am currently interacting with the Spotify API.]

5. **Learning and Improvement**: Considering the key concepts and your practical experiences, identify one area related to APIs where you feel confident and one area where you see a need for improvement. What steps will you take to enhance your understanding and skills in the area you wish to improve?

[	I am confident in my understanding of APIs and how they work, I can confidently say I understand my day-to-day Applications a bit more. It’s got me very curious to learn more about APIs. For improvement purposes, I just need a few more practical sessions. The steps I will take to enhance my understanding is to watch a few more API tutorials and code along.]
