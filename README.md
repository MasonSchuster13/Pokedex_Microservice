<h2>REQUEST HANDLING</h2>
<p>By default the application sends a get request to the microservice for the initial list of pokemon (by default it is empty). </p>
<p>There is a button labeled "add pokemon" and when it is pressed there is a post request sent to the microservice to add the pokemon to the list.</p>
<p>        If the user did not set a name for the pokemon, then an error alert is displayed instead.</p>
<p>Each of the names in the list of pokemon is a button and when pressed will remove the clicked pokemon from the list.</p>
<p>    This is done through an app.delete function.</p>
<h2>RESPONSE HANDLING</h2>
<p>When the app receives a response from the microservice (in the form of a json object) it simply displays the information to the user in a neat manner.</p>
<h2>UML DIAGRAM</h2>
<img width="656" alt="UML Diagram for Pokedex App" src="[https://github.com/MasonSchuster13/Pokedex/assets/52943710/8082006d-7787-43a0-b7b6-6645c6cca886](https://github.com/MasonSchuster13/Pokedex/assets/52943710/0dde9595-6964-4634-b9de-b853026b1269)">
