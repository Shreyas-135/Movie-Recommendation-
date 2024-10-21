# Movie Recommendation System

This project is a Movie Recommendation System built using Streamlit for the frontend and TMDB API for the backend. It recommends movies based on user preferences such as genre, ratings, or previously watched movies.

## Features

Recommends movies based on user input.
Uses TMDB API to fetch movie details such as title, ratings, genre, and description.
Streamlit provides an interactive user interface.
Supports various recommendation methods such as:
Content-based filtering
Collaborative filtering
Displays movie details including title, genre, ratings, and description.

## Table of Contents

- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To get a local copy up and running, follow these steps:

### Prerequisites

- Python 3.7 or newer
- Basic knowledge of how to use Streamlit and TMDBAPI.
- Required Python libraries, which can be installed using requirements.txt

### Installation

1. Clone the repo
    sh 
    gh repo clone git clone https://github.com/Shreyas-135/Movie_Recommendation-system.git
    cd Movie_Recommendation-system

2. Install Python packages
    sh
    pip install -r requirements.txt 
    
4. Run the application
    sh
    streamlit run app.py

 This will start the Streamlit app at http://localhost:8501.


## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

1. Fork the project
2. Create your feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a pull request

## License
This project is licensed under the MIT License. See the LICENSE file for details.
