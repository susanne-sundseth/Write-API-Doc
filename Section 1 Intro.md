# Section 1 Introduction

## What is an API?
An _application programming interface_ (API) enables two differen software applications to interact with each other to exchange data in a reliable way.

## Benefits of using API
By using an API, an application has immediate access to modules and functionality that is already developed in another application. You can leverage and reuse existing functionality from another application in the context of your own app so you can offer more functionality to your customers.

## How does an API work?
An application sends a _request_ to use the functionality.The receiving application performs the work and returns a _response_. The requesting app consumes the result provided in the response, showing or using the data/info provided.

An example is logging into a website using your Google login. The website is using a Google API that requests your Google credentials from the Google server. The response from Google includes your credentials and enables you to log in to the site.

## What is API documentation?
API doc is doc for a software developer audience. It explains these technical details:
* What the API can do for an application that consumes the API - what is its intended use, functionality, etc.
* How to connect to the API, configuration details
* How to authenticate after connection is made
* Types of requests that can be sent to the API and the parameters of the requests. The code for the request might be provided in several languages. (See [Update a charge](https://docs.stripe.com/api/charges/update) in the Stripe doc.)
* Types of responses after the API request is being processed and the end results

See these examples of API doc:
* [Stripe](https://stripe.com/docs/api)
* [SAP](https://api.sap.com/api/storage_manager/resource)
* [Apple](https://developer.apple.com/documentation/)
* [Facebook](https://developers.facebook.com/docs/)
* [Google](https://developers.google.com/workspace/products)

Poorly written API doc usually includes requests and responses only. 

## Types of APIs
* Standard API: Direct connection protocol which allows two application to connect
* Web API: Transfers the request and response via https; applications are exposed to the internet

## API Documentation Framework and Structure
Start the documentation process by automatically generating doc from the API design annotation using tools such as [Swagger](https://swagger.io/solutions/api-documentation/). Then, provide additional details such as:
* How to authenticate amd access the API programatically in the supported language.
* Types of requests the API accepts such as moudles and functionality provided via the API. Also include details required in the request to access the functionality such as paramaters, syntax, and samples.
* Types of responses the API returns including errors.

### Testing an API call
You can use Postman to send an API call so you can test it within your application.









