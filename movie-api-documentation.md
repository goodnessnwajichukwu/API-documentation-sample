Authorization: Bearer YOUR_API_KEY
GET https://api.moviedatabase.com/movie/550
Authorization: Bearer YOUR_API_KEY
{
  "id": 550,
  "title": "Fight Club",
  "release_date": "1999-10-15",
  "overview": "A depressed man suffering from insomnia meets a strange soap salesman and forms an underground fight club.",
  "genres": ["Drama"],
  "rating": 8.8,
  "cast": [
    {
      "name": "Brad Pitt",
      "role": "Tyler Durden"
    },
    {
      "name": "Edward Norton",
      "role": "The Narrator"
    }
  ]
}
GET https://api.moviedatabase.com/search/movie?query=Inception
GET https://api.moviedatabase.com/movie/550
GET https://api.moviedatabase.com/person/1
