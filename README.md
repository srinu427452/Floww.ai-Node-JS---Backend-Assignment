# API Documentation

## 1. Get All Transactions
- **Endpoint:** `api/transactions/get`
- **Description:** Retrieves all transactions.
- **Response:** 200 OK

![Get All Transactions](https://github.com/user-attachments/assets/dd436f55-ab17-40c3-a008-6dd1424a8d8f)

### Visualize:
![Visualization](https://github.com/user-attachments/assets/d81b68b9-637e-48e2-a847-67d0a324c22c)

---

## 2. Create a New Transaction
- **Endpoint:** `api/transactions`
- **Description:** Creates a new transaction.
- **Request Body:**
  
![Create Transaction Request Body](https://github.com/user-attachments/assets/45af0283-a6d5-4645-a3ad-2cb0ea91c1ce)

- **Response:** 201 Created

![Create Transaction Response](https://github.com/user-attachments/assets/2b298da8-62f2-4d21-b57f-5aa731455a20)

- **400 Bad Request:**
  
![400 Bad Request](https://github.com/user-attachments/assets/043bb94c-f4b2-4cac-9577-fa19ad6c1550)

---

## 3. Get Transaction by ID
- **Endpoint:** `api/transactions/:id`
- **Description:** Retrieves a transaction by its ID.
- **Response:** 200 OK

![Get Transaction by ID Response](https://github.com/user-attachments/assets/fc19b511-d162-4c37-9b8e-aa344630c90d)

- **404 Not Found:**

![404 Not Found](https://github.com/user-attachments/assets/ae425eb6-f471-4a28-9cbe-1b00d953f59e)

---

## 4. Update a Transaction
- **Endpoint:** `PUT /transactions/:id`
- **Description:** Updates an existing transaction by its ID.
- **Request Body:**
  
![Update Transaction Request Body](https://github.com/user-attachments/assets/110ef5d0-9c62-4053-bf76-eacd51c522e8)

- **Response:** 200 OK

![Update Transaction Response](https://github.com/user-attachments/assets/6cc47873-84ab-43b7-8c16-019b55965177)

- **404 Not Found:**

![404 Not Found](https://github.com/user-attachments/assets/9eda1811-a670-43dc-82d0-ec85b8cbb42b)

---

## 5. Delete a Transaction
- **Endpoint:** `api/transactions/:id`
- **Description:** Deletes a transaction by its ID.
- **Response:** 200 OK

![Delete Transaction Response](https://github.com/user-attachments/assets/02680bd5-ea7c-46c2-8d99-617712efe990)

- **404 Not Found:**

![404 Not Found](https://github.com/user-attachments/assets/d60a7d8c-7448-41f6-905f-a3e3a488af4c)

---

## 6. Get Transaction Summary
- **Endpoint:** `api/summary`
- **Description:** Retrieves a summary of transactions, such as total income, total expenses, and balance.
- **Response:** 200 OK

![Transaction Summary Response](https://github.com/user-attachments/assets/4d64e050-01db-43c3-bf75-952b576c2b29)

---
