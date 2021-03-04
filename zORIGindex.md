import React from 'react';
import ReactDOM from 'react-dom';
 
class MovieCard extends React.Component {
  render() {
    return (
      <div className="movie-card">
        <img src="https://m.media-amazon.com/images/M/MV5BN2EwM2I5OWMtMGQyMi00Zjg1LWJkNTctZTdjYTA4OGUwZjMyXkEyXkFqcGdeQXVyMTMxODk2OTU@._V1_UY1200_CR90,0,630,1200_AL_.jpg" alt="Mad Max: Fury Road" height="200px"/>
        <h2>Mad Max: Fury Road</h2>
        <small>Genres: Action, Adventure, Science Fiction, Thriller</small>
      </div>
    );
  }
}
 
ReactDOM.render(
  <MovieCard />,
  document.getElementById('root')
);
