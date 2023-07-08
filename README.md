# GURU SCRAPPER API

Welcome to the GURU SCRAPPER API documentation! This API provides various endpoints to scrape data from different sources, including comics, social media platforms, and adult websites.

Base URL: `https://guru-scrapper.cyclic.app`

## Endpoints

### GET /api/sekaikomik

This endpoint allows you to fetch the image URLs of a comic from a given URL.

**Usage:** `GET /api/sekaikomik?url=<comic-url>`

Example:


### GET /api/facebook

This endpoint allows you to fetch the download links for a video from a Facebook post URL.

**Usage:** `GET /api/facebook?url=<video-url>`

Example:


### GET /api/ig

This endpoint allows you to fetch information about an Instagram user, such as name, username, follower count, etc.

**Usage:** `GET /api/ig?username=<username>`

Example:


### GET /api/tiktok

This endpoint allows you to fetch information about a TikTok user, such as profile picture, username, followers count, etc.

**Usage:** `GET /api/tiktok?user=<username>`

Example:


### GET /api/xnxxdl

This endpoint allows you to fetch the download links for a video from an XNXX video URL.

**Usage:** `GET /api/xnxxdl?url=<video-url>`

Example:


### GET /api/xnxxsearch

This endpoint allows you to search for videos on XNXX based on the provided search query.

**Usage:** `GET /api/xnxxsearch?query=<search-query>`

Example:


### GET /api/chatgpt

This endpoint utilizes a ChatGPT model to generate responses to user queries.

**Usage:** `GET /api/chatgpt?query=<user-query>`

Example:


### GET /api/xvideossearch

This endpoint allows you to search for videos on Xvideos based on the provided keyword.

**Usage:** `GET /api/xvideossearch?keyword=<search-keyword>`

Example:


### GET /api/xvideos

This endpoint allows you to fetch information about a video from an Xvideos video URL.

**Usage:** `GET /api/xvideos?url=<video-url>`

Example:


Adjust the URLs and query parameters according to your specific use case and requirements.

## Response Structure

For all endpoints, the response will include a JSON object with the following structure:

```json
{
  "data": { /* endpoint-specific data */ },
  "creator": "Guru"
}
