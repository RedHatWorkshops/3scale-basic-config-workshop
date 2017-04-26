# 3Scale Basic Config Workshop


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

The labs are written in [Gitbook](https://www.gitbook.com) format (asciidoc) and can be viewed online or in offline book (pdf, epub, mobi) format. Each Gitbook has a [change request](https://help.gitbook.com/books/what-are-change-requests.html) process, and should have [integration with a Github repo](https://help.gitbook.com/github/can-i-host-on-github.html#github-integration) to allow changes to be sync'ed up between the two. 

* [3Scale Basic Config Workshop Labs Gitbook](https://www.gitbook.com/book/hucmaggie/3scale-workhop-basic/details)
* [3Scale Basic Config Workshop Labs Github](https://github.com/hucmaggie/3scale-basic-config-workshop-labs)

## Contributing

We welcome all forms of contribution (content, issues/bugs, feedback). Please see the [Contribution guidelines for ways to help](./CONTRIBUTING.md)