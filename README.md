# Unique API Identifiers
This is a project to develop naming specifications (nomenclature) to uniquely identify APIs available on the Web.

# Draft Proposal
The proposed nomenclature for APIs is: {vendor}:{protocol}:{domain}:{resource}:{version}:{category}

The description of each field used in this API nomenclature specification is as follows: 

- **vendor** - The organization providing the API (e.g., twitter).
- **protocol** - The transport protocol used by the API (e.g., https).
- **domain** - The WWW domian name of the API (e.g., twitter.com).
- **resource** - The specific resource of the API (e.g., search).
- **version** - The specific version of the API (e.g., 1.3).
- **category** - A general or specific resource or class (e.g., business or social).

## Examples
Here are some examples of unique identifiers for some of the leading APIs.

- twilio:http1:twilio.com:2010-04-01:sms
- stripe:http1:stripe.com:v1:payments
- spotify:http1:spotify.com:v1:music
- youtube:public:http1:youtube.com:v3:videos
- twitter:http1:twitter.com:v2:social
- reddit:http1:reddit.com:v1:subreddits

## References
The proposed API nomenclature is inspired by Common Platform Enumeration (CPE) standard adopted by NIST for naming Software and IT systems.

- (**Common Platform Enumeration (CPE) Dictionary**](https://nvd.nist.gov/products/cpe)
- (**Common Platform Enumeration (CPE) Documentation**](https://nvlpubs.nist.gov/nistpubs/Legacy/IR/nistir7695.pdf)

CPE provides a good reference model that can be used to identify Web APIs globally.

## Contribute / Support
We are using Github issues to drive the conversation. We are just getting started so make sure you share your feedback.

## Project Supporters
This project is currently being driven by following contributors, but we are looking for more individuals/organizations to contribute.

- [Postman](https://postman.com)
- [TeejLab](https://apidiscovery.teejlab.com/)
- [API Evangelist](https://apievangelist.com)

If you'd like to get involved feel free to reach out / contribute and we'll add your name to the list.
