import React from "react";
import { Link } from "react-router-dom";

function MoviesList ({ movies }) {
    const renderMovies = Object.keys(movies).map((movieID) => (
        <li key={movieID}>
        <link to ={`{/movies/${movieID}`}>{movies[movieID.title]}</ link>
        </li>
    ))
    return <ul>{renderMovies}</ul>
}

export default MoviesList;