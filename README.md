# API Documentation

## Fetch N news articles:

Endpoint: /articles
Method: GET
Query Parameters:
count (optional): The number of news articles to fetch (default: 10).
q (optional): Keywords to search for in the news articles.
Example usage: http://localhost:3000/articles?count=5&q=technology

## Fetch news articles by title:

Endpoint: /articles/title/:title
Method: GET
Path Parameters:
title: The title of the news article to search for.
Example usage: http://localhost:3000/articles/title/SpaceX%20launch

## Fetch news articles by author:

Endpoint: /articles/author/:author
Method: GET
Path Parameters:
author: The name of the author whose news articles to fetch.
Example usage: http://localhost:3000/articles/author/John%20Doe