<!-- <html>
    <head>
        <title>Welcome to Kitchen Buddy</title>
    </head>
    <body>
        <h1>Welcome to Kitchen Buddy!</h1>

        <br />
        <p> The <a href="/GroceryList">Grocery List</a></p>    
    
    </body>
</html> -->


<section>
    <h1>Welcome to Kitchen Buddy!</h1>

    <br />
    <p> The <a href="/GroceryList">Grocery List</a></p>    
</section>


<style>
    section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
        background-color:lavender;
	}

    :global(body) {
        background-color: lavender;
        transition: background-color 0.3s
    }

    :global(text) {
        color: rgb(21, 21, 23);
    }

    h1 {
        width: 100%;
        text-align: center;
        color: rgb(21, 21, 23);
    }

    a {
        font-size: large;
    }



</style>