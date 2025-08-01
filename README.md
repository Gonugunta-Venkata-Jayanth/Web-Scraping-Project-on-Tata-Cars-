🚗 Successfully Completed Web Scraping Project on Tata Cars! 🧑‍💻

I have successfully scraped detailed information on Tata car models and their available color variants from the provided URL, https://lnkd.in/gtRnhRVq. The scraping script, written in Python, utilizes requests and BeautifulSoup to parse the HTML and json to extract structured data embedded within a <​script> tag with the id __NEXT_DATA__.

📌 What I Accomplished:
Sends an HTTP GET request to the specified URL and verifies a successful response.

Locates and parses the 
__NEXT_DATA__ JSON object from the HTML, which contains detailed car and variant information.

Iterates through each car model and its variants to extract specific details:

Car Make (e.g., Tata) 

Full Car Model name (e.g., Punch Pure) 

Price, formatted in Lakhs (e.g., ₹6.41 L) 

Fuel Type (e.g., Petrol, CNG, Diesel, Electric) 

Transmission Type (e.g., Manual, Automatic) 

The number of available color variants 

A detailed list of all available colors, including their names and hex codes (e.g., Orcus White (hashtag#f1f6f9)) 

Stores the extracted data in a list of dictionaries.
Converts the list into a pandas DataFrame for a clear, tabular format.

Saves the DataFrame to a CSV file named 
scraped_tata_cars_with_colors.csv for easy sharing and further analysis.

🛠️ Technologies Utilized: Python, BeautifulSoup, Pandas, Jupyter Notebook

This practical project significantly enhanced my expertise in data collection and web scraping. 🚀
