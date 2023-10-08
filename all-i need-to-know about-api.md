## What is an API?
```An API, which stands for application programming interface, is a set of protocols that enable different software components to communicate and transfer data. Developers use APIs to bridge the gaps between small, discrete chunks of code in order to create applications that are powerful, resilient, secure, and able to meet user needs. Even though you can't see them, APIs are everywhere—working continuously in the background to power the digital experiences that are essential to our modern lives.```

Here, we'll give a high-level overview of how APIs work before reviewing the different types of APIs and how they are used. We'll also discuss some common use cases for APIs—and offer a few real-world API examples that can help you get started.

What is an API?

How do APIs work?
Different types of APIs
Common API use cases
Real-world examples of APIs
Questions about APIs
How do APIs work?
APIs work by sharing data between applications, systems, and devices. This happens through a request and response cycle. A user initiates a request for data by interacting with an application. The request is sent to the API, which retrieves the data and returns it to the user.

In order to better understand this process, it can be useful to think of APIs like restaurants. In this metaphor, the customer is like the user, who tells the waiter what she wants. The waiter is like an API, receiving the customer's order and translating it into easy-to-follow instructions for the kitchen—sometimes using specific codes or abbreviations that the kitchen staff will recognize. The kitchen staff is like the API server because it creates the order according to the customer's specifications and gives it to the waiter, who then delivers it to the customer.

Once that metaphor makes sense, you can go a level deeper and start reviewing the different components of an API, starting with the API client. The API client is responsible for assembling requests in response to user actions and sending them to the appropriate API endpoint. Endpoints are Uniform Resource Identifiers (URIs) that provide access to specific resources in a database. For instance, if a user wants to see all of the products at an e-commerce store, the API client will send a GET request to the /products endpoint.

What is the history of APIs?
In order to fully understand the role that APIs play in our lives, it's important to understand how they have evolved. APIs have been around for decades, with modern web APIs first taking shape in the early 2000s. The history of APIs since that period can be roughly broken down into the following five phases:

Phase 1: Commercial APIs
In the early 2000s, web APIs emerged as a new method for emerging startups to not only make products and services available online, but to also enable partners and third-party resellers to extend the reach of their platforms. This era of APIs was defined by Salesforce, eBay, and Amazon, and these companies continue to dominate the API playing field today.

Phase 2: Social media APIs
A shift in the API landscape occurred in the mid-2000s, as a new group of companies—such as Flickr, Facebook, and Twitter—realized that APIs could change the way we share information with one another. While these APIs weren't as intrinsically linked to revenue as their commercial predecessors, they nevertheless provided significant value to their organizations. For instance, Facebook launched version 1.0 of its API in August of 2006, which allowed developers to access Facebook users' friends, photos, events, and profile information. This API played a crucial role in establishing Facebook as one of the most popular social networks in the world.

Phase 3: Cloud APIs
In 2006, Amazon introduced Amazon Simple Storage (S3), which marked yet another turning point in the history of APIs. S3 is a basic storage service in which resources are accessible via API and CLI, and its pay-as-you-go model provides a cost-efficient way for organizations to monetize digital assets in the online economy. Just six months later, Amazon released Amazon Elastic Compute (EC2), which enabled developers to use web APIs to deploy infrastructure that would power the next generation of applications. Both S3 and EC2 continue to play an essential role in application development today.

Phase 4: APIs for mobile applications
The world was introduced to Apple's iPhone and Google's Android in 2007. The ability to carry the web in our pockets radically changed how we live—and spurred a massive investment in mobile applications that are powered by APIs.

For instance, Twilio launched its API-as-a-product platform in 2007, which allowed developers to make and receive phone calls from any cloud application. Instagram then launched its photo-sharing iPhone application in October 2010, and it had one million users just three months later. Instagram did not initially provide an API, but it began work on one in early 2011 in response to user demand. These API-first companies played an essential role in creating the blueprint for how APIs are delivered today.

Phase 5: APIs for connected devices
Around 2010, some developers began using APIs to connect everyday objects—such as cameras, thermostats, speakers, microphones, and sensors—to the cloud. This next generation of devices, which includes Fitbit, Nest, Alexa, can send and receive data, content, media, and other digital resources, further changing the way we interact with the world around us.

What are the different types of APIs, and how are they used?
There are many different types of APIs and ways to categorize them. For instance, you can categorize APIs by who has access to them. This organizational framework includes:

Private APIs: Private APIs, also known as internal APIs, are used to connect different software components within a single organization, and they are not available for third-party use. For instance, a social media application might have a private API that handles the login workflow, another private API that handles the feed, and yet another private API that facilitates communication between users. Some applications may include dozens or even hundreds of private APIs.
Public APIs: Public APIs provide public access to an organization's data, functionality, or services, which third-party developers can integrate into their own applications. Some public APIs are available for free, while others are offered as billable products. For instance, an e-commerce application may incorporate a public payment API, such as Stripe, to handle payment processing without having to build that functionality from scratch.
Partner APIs: Partner APIs enable two or more companies to share data or functionality in order to collaborate on a project. They are not available to the general public and therefore leverage authentication mechanisms to ensure they are only used by authorized partners.
Diagram: Different types of APIs Postman. Illustration.
You can also categorize APIs according to their architectural style, of which there are many. The most frequently used architectural styles are:

REST: As discussed above, REST is the most popular API architecture for transferring data over the internet. In a RESTful context, resources are accessible via endpoints, and operations are performed on those resources with standard HTTP methods such as GET, POST, PUT, and DELETE.
SOAP: SOAP, which stands for Simple Object Access Protocol, uses XML to transfer highly structured messages between a client and server. SOAP is often used in enterprise environments or legacy systems, and while it includes advanced security features, it can be slower than other API architectures.
GraphQL: GraphQL is an open source query language that enables clients to interact with a single API endpoint to retrieve the exact data they need, without chaining multiple requests together. This approach reduces the number of round trips between the client and server, which can be useful for applications that may run on slow or unreliable network connections.
Webhooks: Webhooks are used to implement event-driven architectures, in which requests are automatically sent in response to event-based triggers. For instance, when a specific event occurs in an application, such as a payment being made, the application can send an HTTP request to a pre-configured webhook URL with the relevant event data in the request payload. The system that receives the webhook can then process the event and take the appropriate action.
gRPC: RPC stands for Remote Procedure Call, and gRPC APIs were originated by Google. In gRPC architectures, a client can call on a server as if it were a local object, which makes it easier for distributed applications and systems to communicate with one another.
Private, partner, and public APIs. Illustration.
What are some common API use cases?
APIs are extremely versatile, and they support a wide range of use cases that includes:

Integrating with internal and external systems
One of the most common reasons developers turn to APIs is to integrate one system with another. For instance, you can use an API to integrate your customer relationship management (CRM) system with your marketing automation system, which would allow you to automatically send a marketing email when a sales representative adds a new prospective customer to the CRM.

Adding or enhancing functionality
APIs let you incorporate additional functionality into your application, which can improve your customers' experience. For instance, if you're working on a food delivery application, you might incorporate a third-party mapping API to let users track their order while it's en route.

Connecting IoT devices
APIs are essential to the Internet of Things (IoT) ecosystem, which includes devices such as smart watches, fitness trackers, doorbells, and home appliances. Without APIs, these devices would not be able to connect to the cloud—or to one another—which would render them useless.

Creating more scalable systems
APIs are used to implement microservice-based architectures, in which applications are built as a collection of small services that communicate with one another through private APIs. Microservices are managed, deployed, and provisioned independently of one another, which enables teams to scale their systems in a reliable yet cost-efficient way.

Reducing costs
APIs help organizations reduce operational costs by automating time-intensive tasks, such as sending emails, pulling reports, and sharing data between systems. They can also reduce development costs by enabling teams to reuse existing functionality, instead of reinventing the wheel.

Improving organizational security and governance
APIs power many workflows that are essential for organizational security. For instance, single sign-on (SSO), which enables users to use one username and password for multiple systems, is made possible by APIs. APIs are also used to enforce and automate corporate governance rules and policies, such as a requirement that expenses be approved before employees are reimbursed.

This list is far from exhaustive, and it will keep growing as developers continue to create innovative solutions that change the ways we live, work, and interact with one another.

Private, partner, and public APIs. Illustration.
What are some real-world examples of APIs?
If you're looking for real-world examples of APIs, a good place to start is a public API catalog, such as Postman's Public API Network. The Public API Network, which supports a community of over 25 million developers, is a searchable, highly organized library of APIs that makes it easy to find the API that's right for you. You can use the network's search functionality if you're looking for something specific, or browse by category if you want to get inspired. Some companies that have published great examples of APIs on the Public API Network include Salesforce, Notion, Discord, Pinterest, and DoorDash.

Other common questions about APIs
Who works with APIs?
While developers are most likely to work with APIs as part of their job, Postman's State of the API report found that many non-developers, such as product managers, business analysts, and customer support professionals, work with APIs, as well.

Which industries use APIs?
APIs are used extensively in the technology industry, as they are the primary building blocks of applications and other digital services. Financial institutions also rely on APIs to facilitate their customers' transactions, and healthcare providers use APIs to manage patient data and keep it secure.

What is the API-first strategy?
The API-first strategy is an approach to software development in which applications are designed and built as a collection of internal and external services that are delivered through APIs. APIs are the building blocks of these applications, and the API-first strategy helps teams prioritize their quality, security, and performance.

What are some tools that can help you build and integrate APIs?
API development is an iterative and collaborative process, so it's important to leverage the appropriate tooling to ensure everything runs as smoothly as possible. For instance, teams should use a source control management tool like GitHub or BitBucket to keep track of API changes, and a CI/CD pipeline such as Jenkins or CircleCI will help them automate the API testing and deployment processes. It's also essential for teams to use an API platform that integrates with these tools, which will reduce friction and augment existing workflows.

How do you build an API?
The API development process can vary widely according to the API's purpose, language, and scope. Nevertheless, every new API will need to be designed, implemented with an API development framework, and thoroughly tested to ensure it's working as expected. Learn more about how to build an API.

What is API management?
API management is the practice of establishing efficient, standardized processes for working with APIs. Organizations who prioritize API management typically leverage an API platform like Postman, which can help them design, develop, test, secure, deploy, and monitor APIs at scale. This improves collaboration by reducing redundant work, increases visibility into API-related projects, and supports greater organizational alignment.

What is the difference between SOAP APIs and REST APIs?
SOAP (Simple Object Access Protocol) and REST (Representational State Transfer) are two of the most common architectural styles for building APIs. SOAP APIs use XML and include built-in features for security and error handling, which makes them well-suited for enterprise environments with strict standards. On the other hand, REST APIs use JSON for resource representation, which is less verbose than XML. REST APIs are usually easier to understand, consume, and integrate than SOAP APIs, but they lack some of SOAP's advanced features. Learn more about the differences between SOAP and REST.

What is the difference between APIs and webhooks?
Webhooks are lightweight callback functions that facilitate event-driven communication between APIs. In the traditional request-response cycle, an API client actively sends a request to an API server in order to retrieve data or perform actions. In contrast, a webhook listens for a specific event, such as a new user account being created or a payment being made, and performs a pre-configured action in response. This eliminates the need for the API client to poll the server, as the server will automatically perform the appropriate action or return the relevant data when the specified event occurs.

What is the difference between service-oriented architecture (SOA) and microservice architecture?
Service-oriented architectures (SOAs) and microservice architectures are both comprised of modular services that perform specific business functions, but they have several key differences. For instance, microservices communicate with one another through APIs, whereas SOA services rely on an enterprise service bus (ESB) for routing, transforming, and managing messages. Additionally, SOA services tend to use SOAP, whereas microservices tend to use lightweight protocols like REST. Finally, SOA services are less granular than microservices, and they may also be dependent on one another.
