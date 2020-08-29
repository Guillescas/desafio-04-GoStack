<h1 align="center">
  Challenge 04 - Course GoStack
</h1>

## What is dealt with in the challenge?

This challenge is about Concepts of NodeJS

## What does the exercise aks for?

Now that you have the template cloned, and ready to continue, you must open the src / App.js file, and complete where you don't have the code with the code to achieve the objectives of each feature.

```POST / transactions```: The route must receive ```title```, ```value``` and ```type``` within the body of the request, ```type``` is the type of the transaction, which must be income for entries (deposits) and ```outcome``` for exits (withdrawals). When registering a new transaction, it must be stored inside an object with the following format:

```json
{
  "id": "uuid",
  "title": "Salário",
  "value": 3000,
  "type": "income"
}
```


```GET / transactions```: This route should return a listing with all the transactions you have registered so far, together with the sum of the entries, withdrawals and total credit. This route must return an object with the following format:

```json
{
  "transactions": [
    {
      "id": "uuid",
      "title": "Salário",
      "value": 4000,
      "type": "income"
    },
    {
      "id": "uuid",
      "title": "Freela",
      "value": 2000,
      "type": "income"
    },
    {
      "id": "uuid",
      "title": "Pagamento da fatura",
      "value": 4000,
      "type": "outcome"
    },
    {
      "id": "uuid",
      "title": "Cadeira Gamer",
      "value": 1200,
      "type": "outcome"
    }
  ],
  "balance": {
    "income": 6000,
    "outcome": 5200,
    "total": 800
  }
}
```

Link to the challenge repository from RocketSeat **[here!](https://github.com/rocketseat-education/gostack-template-fundamentos-node)**

## Does Gui made it?

Hmm not yet... :(

<!-- <img src="./assets/note.png">

<img src="./assets/requirements.png"> -->
