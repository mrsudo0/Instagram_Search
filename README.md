# Instagram SMS Scraper
This Python script automates the process of scraping Instagram for posts matching specific hashtags. It utilizes browser automation through Selenium to interact with Instagram, extract relevant information, and output the results in JSON format.

# Features:
Automated Login: Logs into Instagram using provided credentials.
Hashtag Search: Searches Instagram for posts containing specified hashtags.
Dynamic Web Scraping: Scrolls through the search results to retrieve post URLs.
Post Analysis: Retrieves metadata from individual posts, including the original poster's profile, message body, and any embedded URLs.
Output Generation: Outputs the scraped data to a JSON file.
Logging: Logs errors and messages for debugging purposes.

# Usage:
Ensure Python and necessary dependencies (such as Selenium) are installed.
Configure Instagram credentials in the config.ini file.
Prepare a file containing hashtags to search for.
Run the script with appropriate command-line arguments:
-k/--keywords: Path to the file containing hashtags.
-t/--time_limit: (Optional) Time limit for scrolling through search results.
-o/--output: Output file path for storing the scraped data.

# Python3 insta.py -k keyword.txt -t 5hour -o output.json

# Additional Notes:
Customize the script as needed for specific use cases or integration with other systems.
Ensure compliance with Instagram's terms of service and data usage policies.
Handle potential changes in website structure or policies that may affect the scraping process.

# Credits:
Credit goes to Mr. Sudo 0 for the initial version of this script.

# Disclaimer:
This script is provided as-is and may not guarantee 100% accuracy or reliability. Use it responsibly and verify its results in real-world scenarios. Ensure compliance with Instagram's terms of service and data usage policies.
