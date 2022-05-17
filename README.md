# get-it-done
week6 module project 

## what you will learn
- Explain the difference between a client-side API and a server-side API
- Explain the client-server model and request-response pattern
- Explain and implement the differences between HTTP GET requests using XMLHTTP request, jQuery AJAX, and the fetch API
- Explain HTTP response codes and handle response metadata with fetch API 
- Parse JSON to dynamically generate HTML 
- Explain the benefits and challenges of working with asynchronous JavaScript
- Explain and implement query string parameters

## fetch syntax 
    var requestUrl="https://dfkdf./api/"
    fetch(requestUrl)
    .then(function(response){
    return response.json();
    })
    .then (function(data){
    console.log(data);
    });

## 6.1 workflow
 1. Set up the project with initial files and define remaining work. 
 2. Create a new JavaScript file to request data from the GitHub API. 
 3. Capture the returned data from the API. 
 4. Update request logic with dynamic variables.  

 