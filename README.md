# Systems Biology Scientific Programming

---
title: "Assignment 1:Server_Client_Interaction"
output: html_document
---

## Basic definitions

1. **HTML**: *Hypertext Markup language* which is an annotating document. Used for creating webpages and web applications. HTML describes the structure of web pages scemahtically.

2. **Javascript**: *High level interpreted programming language* enables interactive web pages (dynamic HTML).

3. **API**: *Application Programming Interface* for building software. Defined methods of communication between multiple components. Describes how to use a library.

4. **SparQL**: *RDF language (Resource Description Framework)* its a semantic query language for databases. For retrieving manipulated data stored in RDF (info that is implemented in web resources).

5. **JSON**: *JavaScript Object Notation* it uses human readable text to transmit data object consisting attribute-value pairs

6. **Client-server** *servers provbide resource/service, clients are server requesters* servers implement API. 


## HTML basics (set-up)
```{r}
<html>                                          - Opening tag
<head>                                          - Info about page
</head>
<body>                                          - Main content
    This is my first web page!
</body>
</html>                                         - Closing tag
```
## JavaScript basics

```{r}
// This is a comment.

/* comment line 1
Multi-line comment
comment line 3*/

var x = 10; // create variable, semi colon to end the statement

alert(x) // print value as popup window

console.log(x) // print to inspector

var objectcurly = {}; // create an object

// objects consist of properties (is) and methods (does)

person.firstname; // dot(.) to retrieve individual value
```

## API key
```{r}
Example: <script async defer src="https://...?key=YOUR_API_KEY&callback=..."  type="text/javascript"></script>
```
Step 1: Get API key

Step 2: Add API key to application

## HTTP response codes
```{r}
* HTTP 200 OK - results are returned 

* HTTP 403 if authorization failed 

* HTTP 400 if request was invalid 

* HTTP 404 if nothing could be found 

* HTTP 500 if internal server error occurred 
```



## OpenPHACTS
```{r}
Example: var sources = new CompoundSearch("open PHACTS server", "API identifier", "API key");
```
Platform connects data from pharmacological and phsiochemical sources. Data is integrated in a consolidated triple store. Can make use of linked data and workflows


## OPS.js
```{r}
```
Javascript NodeJS based library, used for accessing Open PHACTS linked data API.

## Goal 1: Use JavaScript+HTML for a REST service
```{r}
1A. Set up specific call

1B. Make the call

1C. Record the returned answer

2A. Convert returned answer to table/figure

2B. Dynamically insert this output in the HTML
```


## Goal 2: Create HTML page that runs SparQL agianst wikidata SparQL end point
```{r}

```
