# Collections

## Products

- Name
- Description
- Price
- ImageURL
- Category

```json
[
  {
    "name": "Mini Cheese Burger",
    "description": "Mini Cheese Burger Description",
    "price": 129.99,
    "imageURL": "https://example.com/mini-cheese-burger.jpg",
    "category": "Burger"
  },
  {
    "name": "Mini Chicken Burger",
    "description": "Mini Chicken Burger Description",
    "price": 139.99,
    "imageURL": "https://example.com/mini-chicken-burger.jpg",
    "category": "Burger",
    "addons": ["Cheese", "Bacon", "Egg"]
  },
  {
    "name": "Mini Veggie Burger",
    "description": "Mini Veggie Burger Description",
    "price": 119.99,
    "imageURL": "https://example.com/mini-veggie-burger.jpg",
    "category": "Burger"
  },
  {
    "name": "Mini Cheese Pizza",
    "description": "Mini Cheese Pizza Description",
    "price": 149.99,
    "imageURL": "https://example.com/mini-cheese-pizza.jpg",
    "category": "Pizza"
  },
  {
    "name": "Mini Chicken Pizza",
    "description": "Mini Chicken Pizza Description",
    "price": 159.99,
    "imageURL": "https://example.com/mini-chicken-pizza.jpg",
    "category": "Pizza",
    "addons": ["Cheese", "Bacon", "Egg"]
  },
  {
    "name": "Mini Veggie Pizza",
    "description": "Mini Veggie Pizza Description",
    "price": 139.99,
    "imageURL": "https://example.com/mini-veggie-pizza.jpg",
    "category": "Pizza"
  }
]
```

## Orders

- CustomerID
- Items
  - ProductID
  - Price
  - Quantity
- CreatedAt
- Status
- Notes

## Customers

- Name
- Email
- Phone
- Address
- Location
  - Latitude
  - Longitude
- Password

```json
[
  {
    "name": "John Doe",
    "email": "john@doe.com",
    "phone": "1234567890",
    "address": "123 Main St, New York, NY 10001",
    "location": {
      "latitude": 40.7128,
      "longitude": -74.0060
    },
    "password": "password"
  }
]
```
