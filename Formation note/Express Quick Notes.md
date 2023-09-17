### To set the static folder files 
###### We have to use the express.static middleware like that : 
	app.use(express.static("public"));

### To open a server 
###### We gotta use : 
	app.listen(port, () => {
	
	  console.log(`Server is running on port ${port}`);
	
	});

### To catch an error we can proceed like that : 
	  try {
	
	    res.render("index.ejs");
	
	  } catch (error) {
	
	    console.log(error.response.data);
	
	    res.status(500);
	
	  }