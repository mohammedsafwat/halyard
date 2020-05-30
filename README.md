# Halyard
An inspirational travel web app powered by [Booking](http://booking.co)

###### How to run the project

```bash
git clone git@github.com:taliescher/halyard.git
# using yarn
yarn && yarn dev
# using npm
npm i && npm run dev
```
___

#### Important Notes
###### _API Credentials_
We use the API credentials provided to us by booking.com to access the APIs. 
These credentials are stored inside `.env` file in two variables: `REACT_APP_BOOKING_AUTH_USERNAME` and `REACT_APP_BOOKING_AUTH_PASSWORD`. We understand that if our access is revoked to the APIs that our API requests will return 401. If this happens, please replace the values of `REACT_APP_BOOKING_AUTH_USERNAME` and `REACT_APP_BOOKING_AUTH_PASSWORD` inside `.env` with valid API credentials. 

___
#### What

Based in a random inspirational location the app suggests several hotels with their Booking score and price. On click the user is redirected to the main booking hotel page.
The user also can search for an specific place and receive suggestions for the given location.

![mobile screenshot of the application](/static/mobile.png)
___
