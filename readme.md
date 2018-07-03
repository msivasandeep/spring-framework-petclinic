## Running petclinic locally
```
	git clone https://github.com/spring-petclinic/spring-framework-petclinic.git
	cd spring-framework-petclinic
	./mvnw tomcat7:run-war
```

You can then access petclinic here: http://localhost:8080/petclinic/
 ## show list of already added owners 
Click on Find Owners -> Find Owner --> Shows list of owners


## add new owner
Click on Find Owners ->  Add Owner

## add new pet
Click on Find Owners -> Find Owner --> Shows list of owners --> Add New Pet

## add new visit
Click on Find Owners -> Find Owner --> Shows list of owners --> Add New Pet -> Add Visit

1. New visit shows list of vets along with latest appointment dates
2. Each vet has 2 slots per day(10 AM and 2 PM)
3. Assumption is, we select shown available data while scheduling appointments.
4. Once scheduling is done, it redirects to owner information page where you see owner, pet and visit details.
5. When you click on add visit again, it shows visit page with all vets along with latest appointment dates.

## database configs
1.HSQLDB in memory database used
2.For shema and tables info, look here
src/main/resources/db/hsqldb/initDB.sql








