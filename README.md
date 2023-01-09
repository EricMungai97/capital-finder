# LAB - Class 16

## Project: capital-finder

This project utilizes a serverless function to enable the user to enter a country to learn its capital, or enter a capital to find out its country.

### Author: Eric Mungai  Kinuthia

#### Links and Resources

* [REST Countries API](https://restcountries.com/#rest-countries)

* [requests library](https://requests.readthedocs.io/en/latest/)

* [Python requirements](https://vercel.com/docs/concepts/functions/supported-languages#python)

##### How to run

Visit https://capital-finder-eric-kinuthia.vercel.app/api/capital_finder

To search for a country's capital, append `?country=your country's name` to the base url.

To search for a capital's country, append `?capital=your capital's name` to the above base url.

Hit enter to view results.

Examples:

https://capital-finder-eric-kinuthia.vercel.app/api/capital_finder?country=Kenya

Output -> The capital of Kenya is Nairobi

https://capital-finder-eric-kinuthia.vercel.app/api/capital_finder?capital=Cairo

Output -> Cairo is the capital of Egypt.

If an invalid country/capital is entered, the output is: Invalid Request. Please try again.