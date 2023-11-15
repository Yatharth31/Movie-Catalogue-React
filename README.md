
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body>

 <h1>Movie Catalogue App with React.js and OMDB API</h1>

  <h2>Overview</h2>

   <p>This React.js application allows users to search for movies using the OMDB API, create a Netflix-style horizontal
        scroll effect, add movies to favorites, and save favorites to local storage for persistence.</p>

  <h2>Getting Started</h2>

  <h3>Prerequisites</h3>

  <ul>
        <li>Node.js installed</li>
        <li>OMDB API key (Follow instructions <a href="http://www.omdbapi.com/apikey.aspx">here</a> to obtain one)</li>
    </ul>

  <h3>Installation</h3>
    <ol>
        <li>Clone the repository:</li>
    </ol>

  <pre><code>git clone https://github.com/your-username/movie-catalog-react.git
cd movie-catalog-react
</code></pre>
   <ol start="2">
      <li>Install dependencies:</li>
    </ol>

   <pre><code>npm install
</code></pre>

  <ol start="3">
        <li>Create a <code>.env</code> file in the root directory and add your OMDB API key:</li>
    </ol>

   <pre><code>REACT_APP_OMDB_API_KEY=your-api-key-here
</code></pre>

  <h3>Running the App</h3>

  <pre><code>npm start
</code></pre>

  <p>Visit <a href="http://localhost:3000">http://localhost:3000</a> in your browser to see the app.</p>

  <h2>Features</h2>

  <h3>Movie Search</h3>

  <ul>
        <li>Utilizes the OMDB API to search for movies by title.</li>
        <li>Real-time search updates based on user input.</li>
    </ul>

  <h3>Horizontal Scroll</h3>

  <ul>
        <li>Implements a Netflix-style horizontal scroll effect for an enhanced user experience.</li>
    </ul>

  <h3>Favorites</h3>

  <ul>
        <li>Users can add movies to their favorites.</li>
        <li>Favorites are stored in local storage for persistence.</li>
    </ul>

  <h3>Remove from Favorites</h3>

  <ul>
        <li>Provides an option to remove movies from the favorites list.</li>
    </ul>
    <h2>Folder Structure</h2>

  <ul>
        <li><code>src/components</code>: Contains React components.</li>
        <li><code>src/styles</code>: Includes CSS styles.</li>
    </ul>

   <h2>API Interaction</h2>

   <ul>
      <li>Interacts with the OMDB API to retrieve movie data.</li>
    </ul>

  <h2>Local Storage</h2>

  <ul>
        <li>Utilizes local storage to save and retrieve favorite movies.</li>
    </ul>

  <h2>Customization</h2>

   <h3>Styling</h3>

   <p>CSS is implemented using Bootstrap for styling and positioning.</p>
    <h2>Contributing</h2>
    <p>Feel free to contribute by opening issues or submitting pull requests.</p>
</body>
</html>
