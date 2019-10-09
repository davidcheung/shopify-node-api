2019-10-09, Version 1.11.1-test
===============================

 * add timeout option (David Cheung)

 * handle empty and already started query on get requests (Brett Knights)

 * with rate limit backoff_level (Brett Knights)


2019-05-31, Version 1.11.0
==========================

 * correct test method (Alex Richter)

 * Adds test (Alex Richter)

 * Adds graphql support (Alex Richter)

 * Use gzip async (Ryan Fink)

 * Fix Buffer.from (Ryan Fink)

 * Use new Buffer for now (Ryan Fink)

 * Adding gzip encode/decode (Ryan Fink)

 * another fix attempt (Brett Knights)

 * added example config to README.md (Brett Knights)

 * added backoff_level as a decimal percent for limiting behaviour (Brett Knights)

 * CHORE: Update README.md markdown styling again (Chris Milliano)

 * CHORE: Update README.md markdown styling (Chris Milliano)

 * CHORE: Update README.md to include useage information about updated functionality (Chris Milliano)

 * CHORE: Remove excessive spacing from additional branch code (Chris Milliano)

 * FEAT: If the user adds a conditional message type assume they do not want all logging. Only show message types the user has requested in their config (Chris Milliano)

 * FEAT: Do not log messages marked BODY (Chris Milliano)


2017-07-17, Version 1.8.0
=========================

 * Update is_valid_signature() to support proxied requests from Shopify (John Lee)

 * API requests don't always return an err for unsuccessful responses (Ghazgkull)

 * testing more node versions (Chris Gregory)

 * moved build image placement (Chris Gregory)

 * adding build status image (Chris Gregory)

 * adding travis-ci automatic build testing (Chris Gregory)

 * Add ability to specifiy https agent (Ryan Fink)

 * Remove crypto dependency. It is included in node (Andrew Assarattanakul)

 * added original request options in callback (Chris Gregory)

 * support patch (Tommi Taskinen)

 * updated readme; removed gittip; added referall links (Chris Gregory)

 * Update README to describe the error response (mozeryansky)

 * prefer error_description for error message and tests (Michael Ozeryansky)

 * install dev dependencies to run tests (Michael Ozeryansky)

 * Upgrade to 1.6.3 to pass in query string parameters as an argument object (Chris Gregory)

 * Adding #get query_data argument info to README.md (Halley Carleton)

 * Allowing data argument for method #get (Halley Carleton)

 * Updating nock version (Halley Carleton)

 * adding travis yaml file (Chris Gregory)

 * add references to shopify docs (Grant Eagon)

 * update syntax so it's less likely to scroll (Grant Eagon)

 * reassign document section hierarchy (Grant Eagon)

 * add install document section (Grant Eagon)

 * add js syntax highlighting (Grant Eagon)

 * updated contributors (Chris Gregory)

 * clarified that the nonce value must be provided by the developer (Chris Gregory)

 * Use BigJSON to parse, in order to handle int64s correctly (Ryan Fink)

 * Add non-state signature validity check (Rick Craig)

 * Shopify.js updated to now verify the OAuth state parameter and nonce. Tests updated in order to correctly pass tests with the state parameter. Version updated to 1.5 (because config requires a new parameter) README updated to include information about state/nonce, and also to improve documentation around private vs public Shopify apps with this package. (Anthony Frehner)

 * Upgrade to 1.4.11 to fix signature verification (Chris Gregory)

 * [#30] Fixed signature verification to take all params except hmac and signature. (Sean Dawson)

 * changed very to verify (gridmechanic)

 * Add Accept header, fix oauth error callback (David Volquartz Lebech)

 * Upgrade to 1.4.9 before June 1st, 2015 to avoid breaking changes to Shopify's API Signature Validation (Chris Gregory)

 * replaced MD5 signature validation with HMAC (Chris Gregory)

 * Moved the request callback given by the user out of a try catch block (mruefenacht)

 * Fix makeRequest for newer node versions (David Volquartz Lebech)

 * make code style match (Blair Anderson)

 * move api limit behind conditional log (Blair Anderson)

 * add http code to error callback (Blair Anderson)

 * updated npm graphic to include download rank (Chris Gregory)

 * Fixed content-length miscalculation for umlaut characters (Chris Gregory)

 * Allow delete request without callback. (Halley Carleton)

 * updated .gitignore (Chris Gregory)

 * updated docs to include is_valid_signature method (Chris Gregory)

 * retry once on network error (Michael Johnston)

 * abstract hostname so can use proxy for testing timeouts (Michael Johnston)

 * on some requests, Shopify retuns an empty body (several spaces) (Marius)

 * Handle cases when Shopify returns one error in "error" field (Marius)

 * simpler error handling (Chris Gregory)

 * removed redundant call to makeRequest (Chris Gregory)

 * fixed conditional which was always true (Marius)


2014-06-26, Version 1.3.0
=========================



2014-06-26, Version 1.3.0
=========================

 * Added API call limit options (Sean Emmel)

 * added badge (Chris Gregory)


2014-06-25, Version 1.2.5
=========================



2014-06-25, Version 1.2.5
=========================

 * fixed minor error in documentation (Chris Gregory)


2014-06-23, Version 1.2.4
=========================

 * signature check is now idempotent and signature check moved before oauth call (Chris Gregory)

 * Added note on instatiation with access_token (Chris Gregory)

 * now accepting gittip (Chris Gregory)

 * giving props (Chris Gregory)


2014-06-12, Version 1.2.3
=========================



2014-06-12, Version 1.2.3
=========================

 * adding test coverage to api enpoints (Chris Gregory)


2014-06-12, Version 1.2.2
=========================



2014-06-12, Version 1.2.2
=========================

 * added testing for shopify signature validation (Chris Gregory)

 * Refactored module for readability, extensibility and efficiency (Chris Gregory)


2014-06-11, Version 1.2.1
=========================

 * added testing instructions (Chris Gregory)


2014-06-11, Version 1.2.0
=========================



2014-06-11, Version 1.2.0
=========================

 * Adding initial tests (Chris Gregory)

 * module now throws instead of returning error for missing config object (Chris Gregory)


2014-06-11, Version 1.1.0
=========================



2014-06-11, Version 1.1.0
=========================

 * callback args now returns header from request. (Chris Gregory)

 * Forgot to update package.json version (Chris Gregory)


2014-04-24, Version 1.0.0
=========================

 * Added missing err in callback (Chris Gregory)

 * use error-first callback style (jesse keane)

 * Added verbose option to suppress console.log messages (Chris Gregory)


2014-03-22, Version 0.1.1
=========================

 * Initial working module, ready for initial testing (Chris Gregory)


2014-03-21, Version 0.1.0
=========================

 * First release!
