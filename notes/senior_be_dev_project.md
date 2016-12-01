# Objective

You will be building a simple REST API for a movie database. This API will be built using Node.js, with whatever mechanisms and standards that you feel will fit the scenario. The API will support two object types: `movie` and `theater`, and will have a single endpoint that will speak to an external API. Your API should use MongoDB as the storage engine.

## API Example

You can use the following API as an example movie API:
* https://www.themoviedb.org/documentation/api
* http://docs.themoviedb.apiary.io

# Requirements

The deliverable should be sent via GitHub repository, and include a dump of the storage engine and sample requests in a Postman export. In addition, the API must be built with the following technologies:

* Node.js
* MongoDB
* Google Maps API
* [Postman](https://www.getpostman.com/) (for testing)

## Objects

You should have both a `movie` and `theater` object type. It is completely up to you what fields should be included on each of these object types.

## Object Functionality

The following endpoints should be supported for each object type:
* List - we should be able to pull a list of objects
  * Pagination required
  * Filtering optional
* Single - we should be able to pull a single object
  * Pulling related objects optional
* Create - we should be able to create a new object
  * Validation optional
* Update - we should be able to update existing objects
  * Validation optional

optional - *every wrong request should return user-friendly message*

## Custom Endpoint

Create an endpoint that will find all theaters or movies playing near an address. You can implement it to search by movie or theater. Utilize the Google Maps API to perform the address lookup.

## One more thing

You should think of this APP like it's first stage of the large enterprise system. 
You shouldn't simplify your approach (Meaning: yes, you have a little app, but imagine that it's only the first part of requirements and tomorrow you will work on expansion of this app)  
  
