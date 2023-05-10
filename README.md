# Lab 3
[Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) this repo and clone it to your machine to get started!

## Team Members
- Dylan Gatua

## Lab Question Answers

Question 1: Why are RESTful APIs scalable?

Answer: RESTful APIs are scalable because they are designed to be stateless, meaning that each request contains all the necessary information to be processed, and the server does not need to keep track of the client's state. This allows the API to handle a large number of requests without being burdened by session management or resource allocation. Additionally, RESTful APIs use standard HTTP methods and can be cached, further improving performance and scalability.


Question 2: According to the definition of "resources" provided in the AWS article above, What are the resources the mail server is providing to clients?

Answer: The resources the mail server is providing to clients are mailboxes, messages, and the ability to send and receive emails.


Question 3: What is one common REST Method not used in our mail server? How could we extend our mail server to use this method?

Answer: One common REST method not used in our mail server is PATCH. We could use it to partially update an existing email by modifying specific fields.

Question 4: API keys are used to authenticate and control access to RESTful APIs by identifying the client making the request. They serve the purpose of enhancing security, managing usage limits, and enabling billing for API usage.

Answer: https://cloud.google.com/endpoints/docs/openapi/when-why-api-key
