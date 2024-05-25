# Custom Ecommerce Web Scraper

This project consists of two main components: a React-based web application that displays products fetched from the FakeStore API and a web scraper that extracts product information from this web application and stores it in a CSV file.

## Project Description

The project is divided into two directories:

- **web**: Contains the React code for a simple webpage that displays products fetched from the FakeStore API using Axios.
- **scraper**: Contains a Jupyter notebook that fetches product names, prices, and ratings from the webpage hosted at [https://prodigy-sd-05.vercel.app/](https://prodigy-sd-05.vercel.app/) and stores this data in a CSV file `products.csv`.

## Tools and Technologies Used

### Frontend (Web Directory)

- **React**: A JavaScript library for building user interfaces.
- **Axios**: A promise-based HTTP client for making API requests.
- **TailwindCSS**: A utility-first CSS framework for styling.

### Backend (Scraper Directory)

- **Selenium**: A browser automation tool used to scrape the web page.
- **BeautifulSoup**: A library for parsing HTML and XML documents.
- **CSV**: Used to write the scraped data into a CSV file.

## Instructions to Run the Project

### Web Application

#### Clone the Repository

```bash
git clone https://github.com/chiragbhatia7/PRODIGY_SD_05.git
cd PRODIGY_SD_05/web
```

#### Install Dependencies

```bash
npm install
```

#### Start the Development Server

```bash
npm start
```

The web application will be available at http://localhost:3000.

### Web Scraper

#### Navigate to the Scraper Directory

```bash
cd ../scraper
```

#### Install Dependencies

Ensure you have Jupyter and the required Python packages installed. You can install the necessary packages using pip:

```bash
pip install selenium beautifulsoup4
```

#### Run the Jupyter Notebook

Open the Jupyter notebook and run the cells to fetch product data from the webpage and store it in products.csv.
