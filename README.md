# University Finder 🌍

This project allows users to search for universities around the world based on a country name. It uses the [Hipolabs University API](http://universities.hipolabs.com/) to retrieve university data and displays it dynamically on the webpage when the user enters a country.

---

## Features
- Search for universities by country.
- Display the names of universities in a list format.
- Dynamically fetch data from the [Hipolabs University API](http://universities.hipolabs.com/search?name=).

---

## Key Points
- **Search Functionality**: Users can enter a country name and click the button to search for universities.
- **Asynchronous Data Fetching**: Uses `async/await` and `axios` to fetch university data.
- **Dynamic Display**: The results are displayed as a list on the webpage.
- **Error Handling**: Logs errors to the console and provides fallback messaging if no data is available.

---

## How to Use
1. **Clone the Repository**:  
   Clone this repository to your local machine using the following command:  
   ```bash
   git clone https://github.com/eabhishek24/getColleges.git

## Technologies Used
- HTML: For the structure of the webpage.
- JavaScript: For making API requests and updating the DOM.
- Axios: For making HTTP requests to fetch university data.

## Future Improvements  
- Add pagination or scrolling for large numbers of universities.
- Implement more detailed information about each university (e.g., website, location).
- Include a loading indicator while fetching the data.
