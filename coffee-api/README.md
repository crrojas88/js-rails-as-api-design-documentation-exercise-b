# Coffee API

This README would normally document whatever steps are necessary to get the
application up and running.

API Initial Setup:

* CD into coffee-api directory

* Run rake db:migrate

* Run rake db:seed

* How to filter by origin
/coffee?origin= (search origin by full name, or letters included)

* How to limit to some number of results
/coffee?limit= (set number of how many results you want)

* how to specify which page of results
/coffee?page= (specify page number 1...10)