### Quick Notes : 

-  JSON.stringify(< js object >) : allows to pack a JS object to an JSON
-  JSON.parse(< js object >) : do the opposite

##### To access to a property of a JS object we have : 
##### Pointed Notation

	let objet = { propriete1: "valeur1"};
	console.log(objet.propriete1); // affiche "valeur1"
##### Bracket notation 

	let objet = {
	  "propriete 1": "valeur1",
	  propriete2: "valeur2"
	};
	
	let nomPropriete = "propriete2";
	
	console.log(objet["propriete 1"]); // affiche "valeur1"
	console.log(objet[nomPropriete]); // affiche "valeur2"
This is useful when the property name is stored in a variable, or if the property name is not a valid JavaScript identifier.
#### Don't confuse object arrays with objects

	An element of an object array can be accessed with its index enclosed in square brackets, just like any other element.

