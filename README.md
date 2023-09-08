https://sudarshan34.github.io/AnimePicGenerator/

Dear Team,

I have used  document.getElementById to get the html elements and added the  click event listener to the 'Generate Anime Picture' button ('btn').When the button is clicked, 
it makes an API request to Unsplash. The API URL includes your Unsplash API access key and a query for 'anime' photos,by receiving API response, it parses the JSON data returned by the API
and extracts the URL of a random anime image from the 
API response and creates an HTML img element.If there is any error during the API request, it logs an error message to the console.
