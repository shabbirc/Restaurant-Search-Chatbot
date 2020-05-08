## Generated Story-01
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location": "delhi"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart 


## Generated Story-02
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "mumbai"}
    - slot{"location": "mumbai"}
    - action_check_location
    - slot{"location": "mumbai"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* affirm{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart 

## Generated Story-03
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "mbusmkwoid"}
    - slot{"location": "mbusmkwoid"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "notfound"}
    - utter_location_notfound
* restaurant_search{"location": "bangalore"}
    - slot{"location": "bangalore"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_price
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart 

	
## Generated Story-04
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "mbumkdjjo"}
    - slot{"location": "mbumkdjjo"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "notfound"}
    - utter_location_notfound
* restaurant_search{"location": "mumbai"}
    - slot{"location": "mumbai"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "south indian"}
    - slot{"cuisine": "south indian"}
    - utter_ask_price
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - action_restaurant
    - slot{"restaurant_found": "notfound"}
    - utter_final_bye 
    - action_restart 

## Generated Story-05
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "rishikesh"}
    - slot{"location": "rishikesh"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "tier3"}
    - utter_foodie_not_working
* restaurant_search{"location": "hyderabad"}
    - slot{"location": "hyderabad"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "south indian"}
    - slot{"cuisine": "south indian"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "notfound"}
    - utter_final_bye 
    - action_restart 
	
## Generated Story-06
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "haridwar"}
    - slot{"location": "haridwar"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "tier3"}
    - utter_foodie_not_working
* restaurant_search{"location": "allahabad"}
    - slot{"location": "allahabad"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart

## Generated Story-07
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "surat"}
    - slot{"location": "surat"}
    - action_check_location
    - slot{"location": "surat"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* affirm{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart
	
	
## Generated Story-08
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "ooty"}
    - slot{"location": "ooty"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "tier3"}
    - utter_foodie_not_working
* restaurant_search{"location": "bangalore"}
    - slot{"location": "bangalore"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* affirm{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

	
	
## Generated Story-09
* greet
    - utter_greet
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location": "delhi"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_price
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart
	
## Generated Story-10
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "pune"}
    - slot{"location": "pune"}
    - action_check_location
    - slot{"location": "pune"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart
	
	
## Generated Story-11
* greet
    - utter_greet
* restaurant_search{"location": "manali"}
    - slot{"location": "manali"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "tier3"}
    - utter_foodie_not_working
* restaurant_search{"location": "srinagar"}
    - slot{"location": "srinagar"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_price
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* affirm{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

	
## Generated Story-12
* greet
    - utter_greet
* restaurant_search{"location": "pune"}
    - slot{"location": "pune"}
    - action_check_location
    - slot{"location": "pune"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "south indian"}
    - slot{"cuisine": "south indian"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart
	
## Generated Story-13
* greet
    - utter_greet
* restaurant_search{"location": "mbunvkdi"}
    - slot{"location": "mbunvkdi"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "notfound"}
    - utter_location_notfound
* restaurant_search{"location": "mysore"}
    - slot{"location": "mysore"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "south indian"}
    - slot{"cuisine": "south indian"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "notfound"}  
    - utter_final_bye 
    - action_restart
	
	
## Generated Story-14
* greet
    - utter_greet
* restaurant_search{"location": "graaar"}
    - slot{"location": "graaar"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "notfound"}
    - utter_location_notfound
* restaurant_search{"location": "agra"}
    - slot{"location": "agra"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* affirm{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart
	
## Generated Story-15
* greet
    - utter_greet
* restaurant_search{"location": "jaipur"}
    - slot{"location": "jaipur"}
    - action_check_location
    - slot{"location": "jaipur"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "south indian"}
    - slot{"cuisine": "south indian"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart

## Generated Story-16
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location": "delhi"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart
	
## Generated Story-17
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian", "location": "goa"}
    - slot{"cuisine": "italian"}
    - slot{"location": "goa"}
    - action_check_location
    - slot{"location": "goa"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* affirm{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
	
## Generated Story-18
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian", "location": "ptnsneha"}
    - slot{"cuisine": "italian"}
    - slot{"location": "ptnsneha"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "notfound"}
    - utter_location_notfound
* restaurant_search{"location": "patna"}
    - slot{"location": "patna"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - slot{"restaurant_found": "notfound"}  
    - utter_final_bye 
    - action_restart
	
## Generated Story-19
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "haridwar"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "haridwar"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "tier3"}
    - utter_foodie_not_working
* restaurant_search{"location": "allahabad"}
    - slot{"location": "allahabad"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* affirm{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
	
## Generated Story-20
* greet
    - utter_greet
* restaurant_search{"location": "kolkata"}
    - slot{"location": "kolkata"}
    - action_check_location
    - slot{"location": "kolkata"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart
	

## Generated Story-21
* greet
    - utter_greet
* restaurant_search{"cuisine": "south indian", "location": "ooty"}
    - slot{"cuisine": "south indian"}
    - slot{"location": "ooty"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "tier3"}
    - utter_foodie_not_working
* restaurant_search{"location": "bengaluru"}
    - slot{"location": "bengaluru"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart
	
## Generated Story-22
* greet
    - utter_greet
* restaurant_search{"cuisine": "american", "location": "rohtak"}
    - slot{"cuisine": "american"}
    - slot{"location": "rohtak"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "notfound"}
    - utter_location_notfound
* restaurant_search{"location": "chandigarh"}
    - slot{"location": "chandigarh"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* affirm{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart
	
	
## Generated Story-23
* greet
    - utter_greet
* restaurant_search{"location": "hwusirinc"}
    - slot{"location": "hwusirinc"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "notfound"}
    - utter_location_notfound
* restaurant_search{"location": "jammu"}
    - slot{"location": "jammu"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "south indian"}
    - slot{"cuisine": "south indian"}
    - utter_ask_price
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart

## Generated Story-24
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "gwalior"}
    - slot{"location": "gwalior"}
    - action_check_location
    - slot{"location": "gwalior"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "american"}
    - slot{"cuisine": "american"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* affirm{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details

## Generated Story-25
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "filmkidiejf"}
    - slot{"location": "filmkidiejf"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "notfound"}
    - utter_location_notfound
* restaurant_search{"location": "faridabad"}
    - slot{"location": "faridabad"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "mexican"}
    - slot{"cuisine": "mexican"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - slot{"restaurant_found": "notfound"}  
    - utter_final_bye 
    - action_restart

	
## Generated Story-26
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location": "delhi"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* affirm{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart


## Generated Story-27
* greet
    - utter_greet
* restaurant_search{"location": "mumbai"}
    - slot{"location": "mumbai"}
    - action_check_location
    - slot{"location": "mumbai"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "american"}
    - slot{"cuisine": "american"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* affirm{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## Generated Story-28
* greet
    - utter_greet
* restaurant_search{"location": "ahmedabad"}
    - slot{"location": "ahmedabad"}
    - action_check_location
    - slot{"location": "ahmedabad"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "american"}
    - slot{"cuisine": "american"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* affirm{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details


## Generated Story-29
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_location
* restaurant_search{"location": "bangalore"}
    - slot{"location": "bangalore"}
    - action_check_location
    - slot{"location": "bangalore"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* affirm{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details

## Generated Story-30
* greet
    - utter_greet
* restaurant_search{"cuisine": "mexican"}
    - slot{"cuisine": "mexican"}
    - utter_ask_location
* restaurant_search{"location": "mumbai"}
    - slot{"location": "mumbai"}
    - action_check_location
    - slot{"location": "mumbai"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* affirm{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - export

## Generated Story-31
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_location
* restaurant_search{"location": "bangalore"}
    - slot{"location": "bangalore"}
    - action_check_location
    - slot{"location": "bangalore"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* affirm{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details


## Generated Story-32
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_location
* restaurant_search{"location": "kolkata"}
    - slot{"location": "kolkata"}
    - action_check_location
    - slot{"location": "kolkata"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* affirm{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details


## Generated Story-33
* greet
    - utter_greet
* restaurant_search{"cuisine": "north indian", "location": "delhi"}
    - slot{"cuisine": "north indian"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location": "delhi"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* affirm{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details

## Generated Story-34
* greet
    - utter_greet
* restaurant_search{"cuisine": "north indian", "location": "delhi"}
    - slot{"cuisine": "north indian"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location": "delhi"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart

## Generated Story-35
* greet
    - utter_greet
* restaurant_search{"location": "chandigarh"}
    - slot{"location": "chandigarh"}
    - action_check_location
    - slot{"location": "chandigarh"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "north indian"}
    - slot{"cuisine": "north indian"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart

## Generated Story-36
* greet
    - utter_greet
* restaurant_search{"location": "jaipur"}
    - slot{"location": "jaipur"}
    - action_check_location
    - slot{"location": "jaipur"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "north indian"}
    - slot{"cuisine": "north indian"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - slot{"restaurant_found": "notfound"}  
    - utter_final_bye 
    - action_restart

## Generated Story-37
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian", "location": "ptsnkela"}
    - slot{"cuisine": "italian"}
    - slot{"location": "ptsnkela"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "notfound"}
    - utter_location_notfound
* restaurant_search{"location": "pune"}
    - slot{"location": "pune"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* affirm{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_01
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location": "delhi"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Chinese"}
    - slot{"cuisine": "Chinese"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* affirm{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_02
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "mumbai"}
    - slot{"location": "mumbai"}
    - action_check_location
    - slot{"location": "mumbai"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_price
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart

## interactive_story_03
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "jaipur"}
    - slot{"location": "jaipur"}
    - action_check_location
    - slot{"location": "jaipur"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "north indian"}
    - slot{"cuisine": "north indian"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_04
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "chennai"}
    - slot{"location": "chennai"}
    - action_check_location
    - slot{"location": "chennai"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "south indian"}
    - slot{"cuisine": "south indian"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}      
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart

## interactive_story_05
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "pune"}
    - slot{"location": "pune"}
    - action_check_location
    - slot{"location": "pune"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_price
* restaurant_search
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart

## interactive_story_06
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "surat"}
    - slot{"location": "surat"}
    - action_check_location
    - slot{"location": "surat"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "south indian"}
    - slot{"cuisine": "south indian"}
    - utter_ask_price
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - action_restaurant
    - utter_ask_whethermail
    - slot{"restaurant_found": "notfound"}
    - utter_final_bye 
    - action_restart

## interactive_story_06_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "mysore"}
    - slot{"location": "mysore"}
    - action_check_location
    - slot{"location": "mysore"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart

## interactive_story_07
* greet
    - utter_greet
* unrelated_query{"unrelated_query": "stock"}
    - utter_unrelated_query
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "pune"}
    - slot{"location": "pune"}
    - action_check_location
    - slot{"location": "pune"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "american"}
    - slot{"cuisine": "american"}
    - utter_ask_price
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - action_restaurant
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_08
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_location
* restaurant_search{"location": "mumbai"}
    - slot{"location": "mumbai"}
    - action_check_location
    - slot{"location": "mumbai"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_09
* greet
    - utter_greet
* restaurant_search{"cuisine": "american"}
    - slot{"cuisine": "american"}
    - utter_ask_location
* restaurant_search{"location": "udaipur"}
    - slot{"location": "udaipur"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "tier3"}
    - utter_foodie_not_working
    - utter_ask_location
    - utter_ask_location
* restaurant_search{"location": "hyderabad"}
    - slot{"location": "hyderabad"}
    - utter_ask_cuisine
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_10
* greet
    - utter_greet
* unrelated_query{"unrelated_query": "weather"}
    - utter_unrelated_query
* restaurant_search{"location": "Vijaywada"}
    - slot{"location": "Vijaywada"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "tier3"}
    - utter_foodie_not_working
* restaurant_search{"location": "hyderabad"}
    - slot{"location": "hyderabad"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "notfound"}
    - utter_final_bye 
    - action_restart

## interactive_story_11
* greet
* restaurant_search{"location": "vadodara"}
    - slot{"location": "vadodara"}
* restaurant_search{"location": "vadodara"}
    - slot{"location": "vadodara"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "mexican"}
    - slot{"cuisine": "mexican"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "notfound"}  
    - utter_final_bye 
    - action_restart

## interactive_story_12
* greet
    - utter_greet
* restaurant_search{"cuisine": "north indian"}
    - slot{"cuisine": "north indian"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location": "delhi"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_13
* greet
    - utter_greet
* restaurant_search{"cuisine": "mexican"}
    - slot{"cuisine": "mexican"}
    - utter_ask_location
* restaurant_search{"location": "mumbai"}
    - slot{"location": "mumbai"}
    - action_check_location
    - slot{"location": "mumbai"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_14
* greet
    - utter_greet
* unrelated_query{"unrelated_query": "stock"}
    - utter_unrelated_query
* restaurant_search{"cuisine": "south indian"}
    - slot{"cuisine": "south indian"}
    - utter_ask_location
* restaurant_search{"location": "kochi"}
    - slot{"location": "kochi"}
    - action_check_location
    - slot{"location": "kochi"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart


## interactive_story_15
* greet
    - utter_greet
* restaurant_search{"cuisine": "american"}
    - slot{"cuisine": "american"}
    - utter_ask_location
* restaurant_search{"location": "kochi"}
    - slot{"location": "kochi"}
    - action_check_location
    - slot{"location": "kochi"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart

## interactive_story_16
* greet
    - utter_greet
* restaurant_search{"cuisine": "north indian"}
    - slot{"cuisine": "north indian"}
    - utter_ask_location
* restaurant_search{"location": "ahmedabad"}
    - slot{"location": "ahmedabad"}
    - action_check_location
    - slot{"location": "ahmedabad"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_17
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_location
* restaurant_search{"location": "surat"}
    - slot{"location": "surat"}
    - action_check_location
    - slot{"location": "surat"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_18
* greet
    - utter_greet
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - utter_ask_location
* restaurant_search{"location": "bangalore"}
    - slot{"location": "bangalore"}
    - action_check_location
    - slot{"location": "bangalore"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_19
* greet
    - utter_greet
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - utter_ask_location
* restaurant_search{"location": "pune"}
    - slot{"location": "pune"}
    - action_check_location
    - slot{"location": "pune"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - action_restaurant
    - slot{"restaurant_found": "notfound"}  
    - utter_final_bye 
    - action_restart

## interactive_story_20
* greet
    - utter_greet
* unrelated_query{"unrelated_query": "scooter"}
    - utter_unrelated_query
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - utter_ask_location
* restaurant_search{"location": "bokoro"}
    - slot{"location": "bokoro"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "tier3"}
    - utter_foodie_not_working
* restaurant_search{"location": "bokaro steel city"}
    - slot{"location": "bokaro steel city"}
    - action_check_location
    - utter_ask_cuisine
* restaurant_search{"cuisine": "south indian"}
    - slot{"cuisine": "south indian"}
    - action_restart
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail  
* affirm
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_21
* greet
    - utter_greet
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - utter_ask_location
* restaurant_search{"location": "vadodara"}
    - slot{"location": "vadodara"}
    - action_check_location
    - slot{"location": "vadodara"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - action_restaurant
    - slot{"location": "vadodara"}
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm{"affirm": "yup"}
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_22
* greet
    - utter_greet
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - utter_ask_location
* restaurant_search{"location": "surat"}
    - slot{"location": "surat"}
    - action_check_location
    - slot{"location": "surat"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "north indian"}
    - slot{"cuisine": "north indian"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
   - utter_ask_whethermail
* affirm{"affirm": "yup"}
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_23
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"location": "surat"}
    - action_check_location
    - slot{"location": "surat"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "north indian"}
    - slot{"cuisine": "north indian"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm{"affirm": "yup"}
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_24
* greet
    - utter_greet
* unrelated_query{"unrelated_query": "car"}
    - utter_unrelated_query
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - utter_ask_location
* restaurant_search{"location": "surat"}
    - slot{"location": "surat"}
    - action_check_location
    - slot{"location": "surat"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "south indian"}
    - slot{"cuisine": "south indian"}
    - action_restaurant
    - slot{"restaurant_found": "found"}  
    - utter_ask_whethermail
* affirm{"affirm": "yea"}
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_25
* greet
    - utter_greet
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - utter_ask_location
* restaurant_search{"location": "junk"}
    - slot{"location": "junk"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "tier3"}
    - utter_foodie_not_working
* restaurant_search{"location": "surat"}
    - slot{"location": "surat"}
    - action_check_location
    - slot{"location": "surat"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "south indian"}
    - slot{"cuisine": "south indian"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* deny{"deny": "nay"}
    - utter_final_bye 
    - action_restart

## interactive_story_26
*greet
    - utter_greet
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - utter_ask_location
* restaurant_search{"location": "pune"}
    - slot{"location": "pune"}
    - action_check_location
    - slot{"location": "pune"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm{"affirm": "yay"}
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_27
* greet
    - utter_greet
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - utter_ask_location
* restaurant_search{"location": "surat"}
    - slot{"location": "surat"}
    - action_check_location
    - slot{"location": "surat"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "mexican"}
    - slot{"cuisine": "mexican"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* deny{"deny": "nope"}
    - utter_final_bye 
    - action_restart

## interactive_story_28
* greet
    - utter_greet
* restaurant_search{"location": "noida", "cuisine": "mexican"}
    - slot{"cuisine": "mexican"}
    - slot{"location": "noida"}
    - action_check_location
    - slot{"location": "noida"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm{"affirm": "yay"}
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_29
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location": "delhi"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* deny{"deny": "nope"}
    - utter_final_bye 
    - action_restart

## interactive_story_30
* greet
    - utter_greet
* restaurant_search{"cuisine": "american", "location": "bangalore"}
    - slot{"cuisine": "american"}
    - slot{"location": "bangalore"}
    - action_check_location
    - slot{"location": "bangalore"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - slot{"restaurant_found": "notfound"}
    - utter_final_bye 
    - action_restart

## interactive_story_30_1
* greet
    - utter_greet
* unrelated_query{"unrelated_query": "shares"}
    - utter_unrelated_query
* restaurant_search{"cuisine": "north indian", "location": "ahmadabad"}
    - slot{"cuisine": "north indian"}
    - slot{"location": "ahmadabad"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "tier3"}
    - utter_foodie_not_working
* restaurant_search{"location": "ahmedabad"}
    - slot{"location": "ahmedabad"}
    - action_check_location
    - utter_ask_price
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm{"affirm": "yay"}
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_30
* greet
    - utter_greet
* restaurant_search{"cuisine": "south indian", "location": "kolkata"}
    - slot{"cuisine": "south indian"}
    - slot{"location": "kolkata"}
    - action_check_location
    - slot{"location": "kolkata"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - slot{"location": "kolkata"}
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* deny{"deny": "nay"}
    - utter_final_bye 
    - action_restart

## interactive_story_31
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "price": "between 300 to 700"}
    - slot{"cuisine": "chinese"}
    - slot{"price": "between 300 to 700"}
    - utter_ask_location
* restaurant_search{"location": "ranchi"}
    - slot{"location": "ranchi"}
    - action_check_location
    - slot{"location": "ranchi"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"restaurant_found": "notfound"}
    - utter_final_bye 
    - action_restart

## interactive_story_32
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian", "price": "lesser than 300"}
    - slot{"cuisine": "italian"}
    - slot{"price": "lesser than 300"}
    - utter_ask_location
* restaurant_search{"location": "jamshedpur"}
    - slot{"location": "jamshedpur"}
    - action_check_location
    - slot{"location": "jamshedpur"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart

## interactive_story_33
* greet
    - utter_greet
* restaurant_search{"cuisine": "north indian", "location": "jaipur"}
    - slot{"cuisine": "north indian"}
    - slot{"location": "jaipur"}
    - action_check_location
    - slot{"location": "jaipur"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart

## interactive_story_34
* greet
    - utter_greet
* restaurant_search{"cuisine": "south indian", "location": "comimbatore"}
    - slot{"cuisine": "south indian"}
    - slot{"location": "comimbatore"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "tier3"}
    - utter_foodie_not_working
* restaurant_search{"location": "madurai"}
    - slot{"location": "madurai"}
    - action_check_location
    - slot{"location": "madurai"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart

## interactive_story_35
* greet
    - utter_greet
* restaurant_search{"cuisine": "american", "location": "pune"}
    - slot{"cuisine": "american"}
    - slot{"location": "pune"}
    - action_check_location
    - slot{"location": "pune"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm{"affirm": "aye"}
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_36
* greet
    - utter_greet
* unrelated_query{"unrelated_query": "stock"}
    - utter_unrelated_query
* restaurant_search{"cuisine": "chinese", "location": "prayagraj"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "prayagraj"}
    - action_check_location
    - slot{"location": "prayagraj"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* deny{"deny": "nope"}
    - utter_final_bye 
    - action_restart

## interactive_story_37
* greet
    - utter_greet
* restaurant_search{"location": "raipur", "price": "between 300 to 700"}
    - slot{"location": "raipur"}
    - slot{"price": "between 300 to 700"}
    - action_check_location
    - slot{"location": "raipur"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "north indian"}
    - slot{"cuisine": "north indian"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* deny{"deny": "nay"}
    - utter_final_bye 
    - action_restart

## interactive_story_38
* greet
    - utter_greet
* restaurant_search{"location": "bangalore", "cuisine": "south indian"}
    - slot{"cuisine": "south indian"}
    - slot{"location": "bangalore"}
    - action_check_location
    - slot{"location": "bangalore"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart

## interactive_story_39
* greet
    - utter_greet
* restaurant_search{"location": "chennai", "price": "lesser than 300"}
    - slot{"location": "chennai"}
    - slot{"price": "lesser than 300"}
    - action_check_location
    - slot{"location": "chennai"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "american"}
    - slot{"cuisine": "american"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm{"affirm": "yup"}
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_40
* greet
    - utter_greet
* restaurant_search{"location": "delhi", "price": "more than 700"}
    - slot{"location": "delhi"}
    - slot{"price": "more than 700"}
    - action_check_location
    - slot{"location": "delhi"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* deny{"deny": "non"}
    - utter_final_bye 
    - action_restart

## interactive_story_41
* greet
    - utter_greet
* restaurant_search{"location": "mumbai", "price": "more than 700"}
    - slot{"location": "mumbai"}
    - slot{"price": "more than 700"}
    - action_check_location
    - slot{"location": "mumbai"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_42
* greet
    - utter_greet
* restaurant_search{"price": "between 300 to 700", "location": "pune"}
    - slot{"location": "pune"}
    - slot{"price": "between 300 to 700"}
    - action_check_location
    - slot{"location": "pune"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "mexican"}
    - slot{"cuisine": "mexican"}
    - action_restaurant
    - slot{"location": "pune"}
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart

## interactive_story_43
* greet
    - utter_greet
* restaurant_search{"location": "indore", "price": "between 300 to 700"}
    - slot{"location": "indore"}
    - slot{"price": "between 300 to 700"}
    - action_check_location
    - slot{"location": "indore"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "north indian"}
    - slot{"cuisine": "north indian"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm{"affirm": "yes"}
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_44
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "price": "between 300 to 700"}
    - slot{"cuisine": "chinese"}
    - slot{"price": "between 300 to 700"}
    - utter_ask_location
* restaurant_search{"location": "vadodara"}
    - slot{"location": "vadodara"}
    - action_check_location
    - slot{"location": "vadodara"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_45
* greet
    - utter_greet
* unrelated_query{"unrelated_query": "stock"}
    - utter_unrelated_query
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "mumbai"}
    - slot{"location": "mumbai"}
    - action_check_location
    - slot{"location": "mumbai"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "north indian"}
    - slot{"cuisine": "north indian"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm{"affirm": "yeah"}
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_46
* greet
    - utter_greet
* restaurant_search{"cuisine": "south indian", "price": "between 300 to 700"}
    - slot{"cuisine": "south indian"}
    - slot{"price": "between 300 to 700"}
    - utter_ask_location
* restaurant_search{"location": "mysore"}
    - slot{"location": "mysore"}
    - action_check_location
    - slot{"location": "mysore"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* deny{"deny": "nope"}
    - utter_final_bye 
    - action_restart

## interactive_story_47
* greet
    - utter_greet
* restaurant_search{"cuisine": "north indian", "price": "between 300 to 700"}
    - slot{"cuisine": "north indian"}
    - slot{"price": "between 300 to 700"}
    - utter_ask_location
* restaurant_search{"location": "mysore"}
    - slot{"location": "mysore"}
    - action_check_location
    - slot{"location": "mysore"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart


## interactive_story_48
* greet
    - utter_greet
* restaurant_search{"price": "lesser than 300", "cuisine": "mexican"}
    - slot{"cuisine": "mexican"}
    - slot{"price": "lesser than 300"}
    - utter_ask_location
* restaurant_search{"location": "bangalore"}
    - slot{"location": "bangalore"}
    - action_check_location
    - slot{"location": "bangalore"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - utter_final_bye 
    - action_restart


## interactive_story_49
* greet
    - utter_greet
* restaurant_search{"price": "more than 700", "cuisine": "mexican"}
    - slot{"cuisine": "mexican"}
    - slot{"price": "more than 700"}
    - utter_ask_location
* restaurant_search{"location": "mumbai"}
    - slot{"location": "mumbai"}
    - action_check_location
    - slot{"location": "mumbai"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart


## interactive_story_50
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "price": "between 300 to 700"}
    - slot{"cuisine": "chinese"}
    - slot{"price": "between 300 to 700"}
    - utter_ask_location
* restaurant_search{"location": "indore"}
    - slot{"location": "indore"}
    - action_check_location
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_51
* greet
    - utter_greet
* restaurant_search{"location": "vadodara", "price": "between 300 to 700", "cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "vadodara"}
    - slot{"price": "between 300 to 700"}
    - action_check_location
    - slot{"location": "vadodara"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm{"affirm": "yeah"}
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart
    
## interactive_story_52
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian", "location": "udaipur", "price": "lesser than 300"}
    - slot{"cuisine": "italian"}
    - slot{"location": "udaipur"}
    - slot{"price": "lesser than 300"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "tier3"}
    - utter_foodie_not_working
* restaurant_search{"location": "ajmer"}
    - slot{"location": "ajmer"}
    - action_check_location
    - slot{"location": "ajmer"}
    - slot{"location_found": "found"}
    - utter_ask_location
* restaurant_search{"location": "jodhpur"}
    - slot{"location": "jodhpur"}
    - action_check_location
    - slot{"location": "jodhpur"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm{"affirm": "please"}
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart


## interactive_story_53
* greet
    - utter_greet
* restaurant_search{"cuisine": "american", "location": "gurgaon", "price": "lesser than 300"}
    - slot{"cuisine": "american"}
    - slot{"location": "gurgaon"}
    - slot{"price": "lesser than 300"}
    - action_check_location
    - slot{"location": "gurgaon"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"location": "gurgaon"}
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart

## interactive_story_54
* greet
    - utter_greet
* restaurant_search{"cuisine": "south indian", "location": "surat", "price": "lesser than 300"}
    - slot{"cuisine": "south indian"}
    - slot{"location": "surat"}
    - action_check_location
    - slot{"location": "surat"}
    - slot{"location_found": "found"}
    - slot{"price": "lesser than 300"}  
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm{"affirm": "yeah"}
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_55
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "mumbai", "price": "more than 700"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "mumbai"}
    - slot{"price": "more than 700"}
    - action_check_location
    - slot{"location": "mumbai"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* deny{"deny": "no thanks"}
    - utter_final_bye 
    - action_restart

## interactive_story_56
* greet
    - utter_greet
* restaurant_search{"cuisine": "north indian", "location": "delhi", "price": "more than 700"}
    - slot{"cuisine": "north indian"}
    - slot{"location": "delhi"}
    - slot{"price": "more than 700"}
    - action_check_location
    - slot{"location": "delhi"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_57
* greet
    - utter_greet
* restaurant_search{"cuisine": "american", "location": "hyderabad", "price": "between 300 to 700"}
    - slot{"cuisine": "american"}
    - slot{"location": "hyderabad"}
    - slot{"price": "between 300 to 700"}
    - action_check_location
    - slot{"location": "hyderabad"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* deny{"deny": "no thanks"}
    - utter_final_bye 
    - action_restart

## interactive_story_58
* greet
    - utter_greet
* restaurant_search{"cuisine": "american", "price": "between 300 to 700", "location": "chennai"}
    - slot{"cuisine": "american"}
    - slot{"location": "chennai"}
    - slot{"price": "between 300 to 700"}
    - action_check_location
    - slot{"location": "chennai"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm{"affirm": "please"}
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_59
* greet
    - utter_greet
* restaurant_search{"price": "more than 700", "location": "managalore", "cuisine": "north indian"}
    - slot{"cuisine": "north indian"}
    - slot{"location": "managalore"}
    - slot{"price": "more than 700"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "tier3"}
    - utter_foodie_not_working
* restaurant_search{"location": "mumbai"}
    - slot{"location": "mumbai"}
    - action_check_location
    - slot{"location": "mumbai"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"location": "mumbai"}
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_60
* greet
    - utter_greet
* restaurant_search{"location": "delhi", "cuisine": "italian", "price": "more than 700"}
    - slot{"cuisine": "italian"}
    - slot{"location": "delhi"}
    - slot{"price": "more than 700"}
    - action_check_location
    - slot{"location": "delhi"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_61
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "ahmeadabad", "price":"between 300 to 700"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "ahmeadabad"}
    - slot{"price":"between 300 to 700"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "tier3"}
    - utter_foodie_not_working
* restaurant_search{"location": "ahmedabad"}
    - slot{"location": "ahmedabad"}
    - action_check_location
    - slot{"location": "ahmedabad"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* deny{"deny": "no"}
    - utter_final_bye 
    - action_restart

## interactive_story_62
* greet
    - utter_greet
* restaurant_search{"location": "shimla", "cuisine": "italian", "price": "lesser than 300"}
    - slot{"cuisine": "italian"}
    - slot{"price": "lesser than 300"}
    - slot{"location": "shimla"}
    - action_check_location
    - slot{"location": "shimla"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"restaurant_found": "notfound"}
    - utter_final_bye 
    - action_restart

## interactive_story_63
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian", "location": "bangalore", "price": "more than 700"}
    - slot{"cuisine": "italian"}
    - slot{"location": "bangalore"}
    - slot{"price": "more than 700"}
    - action_check_location
    - slot{"location": "bangalore"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_64
* greet
    - utter_greet
* restaurant_search{"cuisine": "north indian", "location": "mumbai", "price": "more than 700"}
    - slot{"cuisine": "north indian"}
    - slot{"location": "mumbai"}
    - slot{"price": "more than 700"}
    - action_check_location
    - slot{"location": "mumbai"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* deny{"deny": "no thanks"}
    - utter_final_bye 
    - action_restart

## interactive_story_65
* greet
    - utter_greet
* restaurant_search{"cuisine": "south indian", "location": "hyderabad", "price": "between 300 to 700"}
    - slot{"cuisine": "south indian"}
    - slot{"location": "hyderabad"}
    - slot{"price": "between 300 to 700"}
    - action_check_location
    - slot{"location": "hyderabad"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm{"affirm": "please"}
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_66
* greet
    - utter_greet
* restaurant_search{"cuisine": "south indian", "location": "hyderabad", "price": "between 300 to 700"}
    - slot{"cuisine": "south indian"}
    - slot{"location": "mysore"}
    - slot{"price": "between 300 to 700"}
    - action_check_location
    - slot{"location": "mysore"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm{"affirm": "please"}
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_67
* greet
    - utter_greet
* restaurant_search{"price": "more than 700", "cuisine": "italian", "location": "vadodara"}
    - slot{"cuisine": "italian"}
    - slot{"location": "vadodara"}
    - slot{"price": "more than 700"}
    - action_check_location
    - slot{"location": "vadodara"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* deny{"deny": "no thanks"}
    - utter_final_bye 
    - action_restart

## interactive_story_68
* greet
    - utter_greet
* restaurant_search{"price": "more than 700", "cuisine": "american", "location": "mumbai"}
    - slot{"cuisine": "american"}
    - slot{"location": "mumbai"}
    - slot{"price": "more than 700"}
    - action_check_location
    - slot{"location": "mumbai"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm{"affirm": "please"}
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_69
* greet
    - utter_greet
* restaurant_search{"price": "more than 700", "cuisine": "chinese", "location": "bangalore"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "bangalore"}
    - slot{"price": "more than 700"}
    - action_check_location
    - slot{"location": "bangalore"}
    - slot{"location_found": "found"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* deny{"deny": "no"}
    - utter_final_bye 
    - action_restart

## interactive_story_70
* greet
    - utter_greet
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - utter_ask_location
* restaurant_search{"location": "surat"}
    - slot{"location": "surat"}
    - action_check_location
    - slot{"location": "surat"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "north indian"}
    - slot{"cuisine": "north indian"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm{"affirm": "please"}
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_71
* greet
    - utter_greet
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - utter_ask_location
* restaurant_search{"location": "hyderabad"}
    - slot{"location": "hyderabad"}
    - action_check_location
    - slot{"location": "hyderabad"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "south indian"}
    - slot{"cuisine": "south indian"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* deny
    - utter_final_bye 
    - action_restart

## interactive_story_72
* greet
    - utter_greet
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - utter_ask_location
* restaurant_search{"location": "mumbai"}
    - slot{"location": "mumbai"}
    - action_check_location
    - slot{"location": "mumbai"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "north indian"}
    - slot{"cuisine": "north indian"}
    - action_restaurant
    - slot{"restaurant_found": "found"}
    - utter_ask_whethermail
* affirm{"affirm": "please"}
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye 
    - action_restart

## interactive_story_73
* greet
    - utter_greet
* unrelated_query
    - utter_unrelated_query

## interactive_story_74
* greet
    - utter_greet
* unrelated_query{"unrelated_query": "car"}
    - utter_unrelated_query

## interactive_story_75
* greet
* unrelated_query{"unrelated_query": "bike"}
    - utter_unrelated_query
* unrelated_query
    - utter_unrelated_query

## interactive_story_76
* greet
    - utter_greet
* unrelated_query{"unrelated_query": "stock"}
    - utter_unrelated_query

## interactive_story_77
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location": "delhi"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "south indian"}
    - slot{"cuisine": "south indian"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_whethermail
* affirm
    - utter_ask_mail
* restaurant_search{"email": "shabbirc@yahoo.com"}
    - slot{"email": "shabbirc@yahoo.com"}
    - email_restaurant_details
    - utter_final_bye
    - action_restart
