# POST
> curl --location --request POST 'http://localhost:8080/recipes' --header 'Content-Type: application/json' --data-raw '{ "name": "Homemade Pizza", "tags" : ["italian", "pizza", "dinner"], "ingredients": [ "1 1/2 cups (355 ml) warm water (105°F-115°F)", "1 package (2 1/4 teaspoons) of active dry yeast", "3 3/4 cups (490 g) bread flour", "feta cheese, firm mozzarella cheese, grated" ], "instructions": ["Step 1.", "Step 2.", "Step 3." ] }' | jq -r

# GET
> curl -s -X GET 'http://localhost:8080/recipes' | jq length