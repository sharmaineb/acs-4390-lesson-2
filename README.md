# GraphQL Server Challenges

## Overview
Your goal is to create a GraphQL server that serves a list of items. These items can be anything from pets to songs, recipes, movies, etc.

## Challenge 1 🐶
Make an array of objects. Each object should have at least three properties.

## Challenge 2 🐶
Make a Type in your schema for your objects.

Use an enum for something!

Advanced: Use an interface!

## Challenge 3 🐈
Make a Query type that will return all of the things.

## Challenge 4 🐈
Write a resolver for your query.

This should return the entire list.

## Challenge 5 🐡
Test your work in GraphiQL.

The query should display a list of names.

## Challenge 6 🐸
Add a query that returns a thing at an index.

Add the new query to your Query types in your schema.

## Challenge 7 🐿
Add a new resolver. The parameters from the query will be received in the resolver function.

## Challenge 8 🐹
Test your work, write a query in GraphiQL.

## Challenge 9 👽
Write a query that gets the last item and the first item from the collection.

## Challenge 10 ⏰
We need a type that represents time.

## Challenge 11 🎲
Imagine we need the server to return a random number. Your job is to write a query type and resolver that makes the GraphQL query below function:

```graphql
{
  getRandom(range: 100) 
}
```
Which should return:

```json
{
  "data": {
    "getRandom": 77
  }
}
```

## Challenge 12 🤔
Create a type that represents a die roll. It should take the number of dice and the number of sides on each die. It should return the total of all dice, sides, and an array of the rolls.

## Challenge 13 📋
Add a query that returns the count of elements in your collection. You'll need to add a query and a resolver.

The trick of this problem is how to form this query.

## Challenge 14 ✅
Add a query that returns some of your collection in a range. 

## Challenge 15 🔎
Get things by one of their features. 

## Challenge 16 ➡️
Choose a field. This query should return all of these values that exist in the things in your list. This would work best for a field with a fixed or limited set of values, like a field that uses an enum as its type.
