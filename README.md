# Webscraping Actor

This Apify actor scrapes all `<h2>` headings from a given web page.

## Usage

1. **Input:**  
   Provide a `startUrl` in the actor input.  
   Example:
   ```json
   {
     "startUrl": "https://example.com"
   }
   ```

2. **Output:**  
   The actor saves all `<h2>` headings found on the page to the dataset.

## Technologies

- [Apify SDK](https://sdk.apify.com/)
- [Axios](https://axios-http.com/)
- [Cheerio](https://cheerio.js.org/)

## Example

Run the actor with:
- `startUrl`: `https://example.com`

The output will be a list of headings like:
```json
[
  { "heading": "Welcome" },
  { "heading": "Features" }
]
```