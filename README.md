# Netflix Movies and TV Shows API

## Overview
This API provides comprehensive data on the movies and TV shows available on Netflix, one of the world's most popular streaming services. You can use this API to discover titles, their types, directors, cast, countries of production, dates added to Netflix, release years, ratings, durations, genres, and descriptions.

With over 8,000 titles as of mid-2021 and a global subscriber base exceeding 200 million, Netflix is a leading platform for media and video streaming. This dataset offers tabular information about Netflix’s content, making it an ideal resource for developers building applications, data analysts, and entertainment enthusiasts.

---

## Key Features
- **Title**: The name of the movie or TV show.
- **Type**: Identifies if the content is a movie or TV show.
- **Director**: Name of the director(s) associated with the content.
- **Cast**: Names of the cast members.
- **Country**: Countries where the content was produced.
- **Date Added**: The date the content was added to Netflix.
- **Release Year**: The year the content was originally released.
- **Rating**: Age rating of the content (e.g., PG-13, TV-MA).
- **Duration**: Length of the content (e.g., minutes for movies or seasons for TV shows).
- **Genre**: The genre(s) of the content.
- **Description**: A brief description of the content.

---

## How to Access the API

### Prerequisites
- A RapidAPI account
- An API token (available through RapidAPI)

### Steps to Get Started

1. **Sign Up on RapidAPI**
   - Visit [RapidAPI](https://rapidapi.com/robotfa-robotfa-default/api/netflix-movies-and-tv-shows1) and create an account if you don’t already have one.

2. **Subscribe to the API**
   - Search for the "Netflix Movies and TV Shows API" and subscribe to it.

3. **Get Your API Token**
   - After subscribing, navigate to the API's "Endpoints" section and copy your unique API token.

4. **Integrate the API**
   - Use the token to authenticate your requests. Here’s an example in cURL:
     ```bash
     curl -X GET "https://netflix-movies-and-tv-shows1.p.rapidapi.com/list" \
     -H "X-RapidAPI-Key: YOUR_API_KEY" \
     -H "X-RapidAPI-Host: netflix-movies-and-tv-shows1.p.rapidapi.com"
     ```

---

## Example Endpoints

### 1. Get Movie or TV Show Details
Retrieve detailed information about a specific title:
```bash
GET /list
```

### 2. Search Titles
Search for movies or TV shows by keywords:
```bash
GET /search?query={keyword}
```

### 3. Filter by Genre
Get a list of titles filtered by genre:
```bash
GET /genres/{genre}
```

### 4. Trending Content
Explore trending movies or TV shows:
```bash
GET /trending
```

---

## Contribution
If you have suggestions or would like to contribute to this project, feel free to open an issue or submit a pull request.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.
