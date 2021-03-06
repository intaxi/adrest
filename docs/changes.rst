2012-11-19  klen  2.0.6

	* Fix OPTIONS method in RPC calls

2012-11-13  klen  2.0.5

	* Fix serialization errors

2012-10-25  klen  2.0.4

	* Change serialize parameters

2012-10-10  klen  2.0.2

	* Refactored RPC support.

2012-10-08  klen  1.9.10

	* Fix serialization

2012-10-03  klen  1.9.9

	* Fix access logging

2012-09-28  klen  1.9.4

	* Upgrade default serialization

2012-09-26  klen  1.9.1

	* Added exclude support to filters (field__not=...). Thanks Lispython
	* Refactor authentication. Some custom authenticators can be not worked.

2012-09-21  klen  1.8.9

	* Fix adrest's admin integration'
	* Fix adrest's log saving

2012-09-05  klen  1.8.7

	* Fix FrozenDict repr in logs

2012-09-03  klen  1.8.5

	* Fix 'get_resources'

2012-09-01  klen  1.8.4

	* Beta Google Analytics support

2012-08-31  klen  1.8.3

	* Support multivalues in FormParser
	* request.data is immutable now

2012-08-28  klen  1.8.1

	* Fix bulk operation

2012-08-17  klen  1.8.0

	* Code-refactoring

2012-07-17  klen  1.7.0

	* Added BSON support

2012-07-16  klen  1.6.0

	* Upgrade 'adrest_include'

2012-06-26  klen  1.5.0

	* Added manytomany field tests.

2012-06-07  klen  1.4.3

	* Fixed RPC callbacks.

2012-06-01  klen  1.4.0

	* Upgraded PUT and DELETE methods.
	* Support for many resources.

2012-05-29  klen  1.3.0

	* Fixed parsing of resources

2012-05-24  klen  1.2.11

	* API-map has been updated.
	* Fixed RPC headers.
	* Added JavaScript templates.
	* Added `adrest_jsonify` tag.

2012-05-23  klen  1.2.2

	* Add JSONP emitters, add jsonp support to rpc

2012-05-22 1.2.1

	* Add simple JSON RPC

2012-05-11 1.1.21

	* Parse resources from POST and PUT
	* Fix pagination

2012-04-28 1.1.20

	* Fix accesskey admin

2012-04-26 1.1.19

	* Not resource checking on options request (ALLOW_OPTIONS)

2012-04-09 1.1.17

	* Add field label to map.

2012-04-09 1.1.15

	* Delete returned empty response.

2012-04-06 1.1.14

	* Add ordering to adrest models

2012-04-03 1.1.12

	* Minor fix of allow header

2012-04-01 1.1.11

	* Do not change data in request from forms

2012-03-29 1.1.10

	* Add ADREST_ACCESSKEY option
	* Fix PUT and PATH requests

2012-03-19 1.1.7

	* Allows fields query (field__startswith) in GET filters

2012-03-07 1.1.6

	* Authenticators refactoring

2012-03-06 1.1.3

	* More usefull api map

2012-02-29 1.1.2

	* Fix accesskey admin

2012-02-28 1.1.0

	* Add not string content for HttpError
	* Add TextEmitter
	* Add SerializedHttpResponse (HttpResponse now returned as is)
	* Add api owned signals

2012-02-27 1.0.18

	* More information in adrest signals.
	* Fix API urls

2012-02-23 1.0.15

	* Add 'api_prefix' option to API
	* Fix templates
	* Append http HEAD method support by default
	* New resource method: as_url
	* Resources now parse from URL and GET
	* get_resources_from_uri -> get_resources

2012-02-17 1.0.6

	* More accurate html (@hogart)
	* Append ADREST temlatetags (adrest_include)

2012-02-13 1.0.4

	* !!! No backward compatible (get_filter_options -> get_queryset)

2012-02-12 1.0.3

	* More information in mail about errors
	* Tests refactoring (@lispython)
	* Fixed json emmiter (@lispython)
	* Added pagination headers (@lispython)

2012-01-30 1.0.2

	* Minor release

2012-01-30 1.0.1

	* Add API errors email notifications

2012-01-27 1.0.0

	* Global refactoring
	* Fix access log

2012-01-25 0.7.93

	* Minor fix of api map
	* Set is now json serialized

2011-12-23 0.7.92

	* Model in resource maybe in string format

2011-11-23 0.7.9

	* Reverse uri in tests by resource name

2011-11-14 0.7.7

	* Fix settings and cross domain 'OPTIONS'

2011-11-11 0.7.5

	* Fix filter_options

2011-11-05 0.7.4

	* Fix precache queryset in handlers

2011-11-05 0.7.2

	* Minor fix

2011-10-28 0.7.1

	* Add version information to django access admin

2011-10-27 0.7.0

	* Add version to access log
	(Manual migration: ALTER TABLE adrest_access ADD COLUMN version varchar(25);)

2011-10-26 0.6.62

	* Fix throttle cache key length

2011-10-13 0.6.5

	* Fix prefix on partitial form

2011-10-05 0.6.4

	* Allow to create api without version

2011-10-03 0.6.3

	* Add django 1.3.1 support and some test utils

2011-09-23 0.6.0

	* Allow filter has many values from GET

2011-09-23 0.5.97

	* Fix partitial form

2011-09-22 0.5.95

	* Fix map for user auth

2011-09-22 0.5.94

	* Fix partitial form.

2011-09-20 0.5.93

	* Add html map

2011-09-19 0.5.92

	* Add fields to map
	* Fix check owner code (if child FK to parent is None -- it's, nobody owns this
	child, so everyone can get it)


2011-09-01 0.5.3

	* Extract check owners method


2011-08-26 0.5.2

	* Upgrade JSON emitter
	* Add XML emitter


2011-08-24 0.4.7

	* Add some tests


2011-08-18 0.4.4

	* Add some tests
	* Add map of api resources
	* Begin code refactoring


2011-08-04 0.3.11

	* Fix access key admin


2011-07-22 0.3.1

	* Fix access log bug


2011-07-19 0.2.98

	* Fix put method


2011-07-18 0.2.97

	* In OPTIONS method always used only JSONEmitter


2011-06-16 0.2.96

	* Allow disable authentication on OPTIONS http methods


2011-06-15 0.2.95

	* Add OPTIONS method


2011-06-13 0.2.92

	* Fix access for nested objects


2011-05-27 0.2.9

	* Fix DEBUG mode


2011-05-23 0.2.7

	* Fix statuses. https://github.com/klen/adrest/issues/4


2011-05-03 0.2.6

	* Fix handlers and forms


2011-05-03 0.2.5

	* Add form_exclude option to resource


2011-04-27 0.2.4

	* Some more frendly Access logs


2011-04-25 0.2.3

	* Fix accesslog truncate content
	* Improve access log admin


2011-04-25 0.2.1

	* Add `log` resource param
	* Truncate response content in log to 5000 symbols
	* Add throttle

2011-04-22 0.1.9

	* Add server timestamp to all request

2011-04-21 0.1.8

	* Minor fixes

2011-04-18 0.1.5

	* Fix empty content-type

2011-04-18 0.1.4

	* Add api_request_started and api_request_finished signals

2011-04-17 0.1.3

	* Add method field in access log model

2011-04-15 0.1.2

	* Fix tests fail for PUT requests

2011-04-15 0.1.1

	* Fix bug with empty request.data on PUT method when content-type is 'application/x-www-form-urlencoded'

2011-04-12 0.1.0

	* Fix invalid identifier in url
	* Add queryset parameter to handler class

2011-04-07 0.0.8

	* Add owner resource checks

2011-04-07 0.0.7

	* Fix url regex generate bug

2011-04-04 0.0.6

	* Many bugs fixed
	* Access logging work on

2011-03-31 0.0.2

	* First public release
