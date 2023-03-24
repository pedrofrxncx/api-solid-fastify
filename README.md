# App

GymPass style app.

## FRs (Functional Requirements)

- [X] Must be possible to register a gym;
- [X] Must be possible to register an user;
- [X] Must be possible to authenticate an user;
- [X] Must be possible to get a logged in user's profile;
- [X] Must be possible to get the number of check-ins made by the logged in user;
- [X] Must be possible to validate an user's check-in;
- [X] Must be possible for the user to get his check-ins historic;
- [X] Must be possible for the user to find near gyms;
- [X] Must be possible for the user to find gyms by name;
- [X] Must be possible for the user to check-in to a gym;

## BRs (Business Rules)

- [X] The user should not be able to register with a duplicated e-mail;
- [X] The user should not be able to make 2 check-ins on the same day;
- [X] The user should not be able to check-in if he isn't near (100m) the gym;
- [X] The check-in can only be validated until 20 minutes after it is created;
- [ ] The check-in can only be validated by administrators;
- [ ] The gym can only be registered by administrators;

## NFRS (Non-functional requirements)

- [X] User password must be hashed;
- [X] Application data bust be persisted in a PostgreSQL database;
- [X] All data list must be paginated with 20 items by page;
- [ ] User must be identified by a JWT;
