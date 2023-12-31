To clone the repo with the submodules, use

```bash
git clone --recursive git@github.com:oenegm/vehicle-renter-microservices.git
```

other versions of this project include:

- [vehicle-renter-kotlin](https://github.com/oenegm/vehicle-renter-kotlin)
- [vehicle-rental](https://github.com/oenegm/vehicle-rental)



description of the project:
- the system should have a user table
- each user can be an owner or a renter
- each user has profile that has his info, name, a link to his profile picture, his bio
- each profile has multiple communication methods like multiple phones, multiple emails, etc.
- each user has a website setting entry with his preferences like dark mode, etc.
- each user can be own multiple vehicles
- each vehicle has a lot of properties like, color, engine type, number of doors, etc.
- each vehicle has a setting entry with settings like visibility, out of order, etc.
- each vehicle has a statistic entry with some statistic like number of successful rentals, number of unsuccessful rentals, last request timestamp, last rental timestamp, etc.
- a renter can submit a request to rent a vehicle and the system should track the request through its phases from submitted, seen, accepted, payment accepted, with renter, until returned
- the request should have some info like request date, rent date, accepted price, etc.
