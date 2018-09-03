# API Docs for UnelmaMail
api documentation for UnelmaMail

## API Documentation
You need to add parameter api_token=YOUR_API_TOKEN to each request to the API system 

Example: https://www.unelmamail.com/api/v1/lists?api_token=YOUR_API_TOKEN

Grab your free YOUR_API_TOKEN = Sign up for free account at UnelmaMail.com at
https://www.core.unelmamail.com/subscriptions/select-plan 

## LISTS

HTTP METHOD: POST, GET
ENDPOINT: /api/v1/lists

```
curl -X POST -H "accept:application/json" -G \
https://www.core.unelmamail.com/api/v1/lists? \
-d api_token=LOcCqPk4wDcjxrRqWxUsJPW9xC5Htof1X8fwSCSHjKTaRGP1Pvd1JklGKH69 \
-d name=List+1 \
-d from_email=admin@abccorp.org \
-d from_name=ABC+Corp. \
-d default_subject=Welcome+to+ABC+Corp. \
-d contact[company]=ABC+Corp. \
-d contact[state]=Armagh \
-d contact[address_1]=14+Tottenham+Court+Road+London+England \
-d contact[address_2]=44-46+Morningside+Road+Edinburgh+Scotland+EH10+4BF \
-d contact[city]=Noname \
-d contact[zip]=80000 \
-d contact[phone]=123+456+889 \
-d contact[country_id]=1 \
-d contact[email]=info@abccorp.org \
-d contact[url]=http://www.abccorp.org \
-d subscribe_confirmation=1 \
-d send_welcome_email=1 \
-d unsubscribe_notification=1
```
verb: GET endpoint: /api/v1/lists 
```
curl -X GET -H "accept:application/json" -G \
https://www.core.unelmamail.com/api/v1/lists? \
-d api_token=LOcCqPk4wDcjxrRqWxUsJPW9xC5Htof1X8fwSCSHjKTaRGP1Pvd1JklGKH69
```

## CAMPAIGNS

## SUBSCRIBERS

## FILES

