# place.js
This is a plugin to populate Countries and their Mobile code, also populate States and Cities for India only.

Methods Available : 

place.getCountries() : will return all the countries from the json defined in the plugin.

place.getCountryMobileCode(country) : will return the country mobile code from the json defined in the plugin.

place.getStates(country) : will return the states of a country from the json defined in the plugin (currently only states of India are defined).

place.getCities(country,state) : will return the cities based on country and state from the json defined in the plugin (currently only cities of Indian states are defined).
