# 3Scale Workshop


This workshop introduces you to some basic configuration of 3scale briefly touching on the main areas of functionality. We will loosely base it on a very basic POC we would normally roll out. 

The workshop is intended to be delivered in person, but will provide enough guidance for self-paced consumption.

## Agenda

A rough agenda for the workshop looks like this:

* Integrate this simple unmanaged API Endpoint into 3scale 
https://tc-apis.herokuapp.com/flights/intl/flights 
(**Note, this is a test API on Heroku. The first time it is hit every hour is slow)


* Demonstrate the main 3scale API Management features typically required for a basic POC – including:
	* Access Control
	* Policy Enforcement 
	* Analytics
	* Swagger & Basic Developer Portal Configuration

* Gain familiarity with the 2 Web Portals 3scale exposes
	* Admin Portal. Used by: The API Provider – or organization exposing the API, e.g. United Airlines.
	* Developer Portal. Used by: API consumers, e.g. Sites and mobile Apps using the APIs – e.g. Expedia, CheapOAir etc. 

## Slides

The slides are written in [RevealJS](http://lab.hakim.se/reveal-js/#/)/[Hyla](https://github.com/cmoulliard/hyla) which is basically a text (asciidoc) format and then converted into an HTML 5 slideshow presentation. 

* [High-level overview of API management](slides/api.md)

## Labs

The labs are written in [Gitbook](https://www.gitbook.com) format (asciidoc) and can be viewed online or in offline book (pdf, epub, mobi) format. 

* [Lab 00](labs/00.md) - Signup to 3scale 
* [Lab 01](labs/01.md) - Login & Integrate an API endpoint.
* [Lab 02](labs/02.md) - Access Control and Analytics 
* [Lab 03](labs/03.md) - Policy Enforcement
* [Lab 04](labs/04.md) - Swagger & Basic Developer Portal Configuration

## Contributing

We welcome all forms of contribution (content, issues/bugs, feedback). Please see the [Contribution guidelines for ways to help](./CONTRIBUTING.md)