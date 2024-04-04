# Country Dropdown Challenge with Javascript

1. Clone the repository
2. Use the useState hook to manage the state for:

countries: An array to store the list of countries fetched from the JSON file.
searchTerm: The user's input for searching countries.
filteredCountries: An array to store the filtered list of countries based on the search term.

3. Use the useEffect hook to fetch the country data from the external JSON file on component mount.
4. Implement logic to filter the countries list based on the searchTerm. Update the filteredCountries state with the filtered list whenever the searchTerm changes.
5. In the JSX, display a dropdown populated with options from the filteredCountries state array. Each option should have a value set to the country name.

## Success Criteria:

The component successfully fetches and displays a list of countries.
The user can search and filter countries using the input field.
The dropdown updates with the filtered results in real-time.
The code adheres to TypeScript type safety best practices.

## Additional Notes:

Consider using a type-safe HTTP client library for data fetching.
Implement proper error handling for fetching and parsing data.
Explore using a state management library for more complex scenarios.
Follow TypeScript conventions for code organization and readability.
