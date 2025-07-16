Here’s a clean, **human-style README.md** you can use for your project. It includes space for screenshots and explains each part like a real developer would.

---

markdown
# URL Shortener with Logging and Authentication

This is a full-stack URL Shortening application built with:

- **Frontend**: React (Vite)
- **Backend**: Express.js (Node.js)
- **Database**: MongoDB
- **Auth**: JWT (JSON Web Token)
- **Logging**: Custom logging middleware with token-based access

---

## Features

- Users can register and receive a JWT token.
- Authenticated users can shorten any valid URL.
- Optional custom short code and expiry time.
- Logs every frontend and backend API interaction.
- Displays shortened URL along with expiry, click count, and redirection.

---

## Tech Stack

| Layer      | Technology     |
|------------|----------------|
| Frontend   | React (Vite)   |
| Backend    | Node.js, Express |
| Database   | MongoDB (via Mongoose) |
| Auth       | JWT            |
| Logging    | Custom Middleware with Logging Server |
| Styling    | Plain CSS      |

---

## Folder Structure



212222040155/
│
├── backend/
│   ├── index.js
│   ├── routes/
│   └── controllers/
│
├── url-shortener-client/
│   ├── src/
│   │   ├── components/
│   │   ├── App.js
│   │   └── main.jsx
│
├── Logging-Middleware/
│   ├── log.ts
│   └── getLogToken.cjs

`

---

## How to Use

### 1. Clone the repo

bash

git clone (https://github.com/Shreyassanthosh7/212222040155).git

cd 212222040155
`

### 2. Setup the Backend

bash
cd backend
npm install
node index.js


Make sure your `.env` file has the correct MongoDB URI and PORT (e.g., 5056).

### 3. Setup the Frontend

bash
cd url-shortener-client
npm install
npm run dev


Visit `http://localhost:3000`

### 4. Setup Logging Token

Get your logging token using:

bash
node getLogToken.cjs


Save the token in `localStorage` as `log_token`.

---

## Output Screenshots

> Screenshots of the working frontend and backend will go here.


### ✅ Shortener Page
<img width="1919" height="965" alt="Shorten" src="https://github.com/user-attachments/assets/4c4beeac-0ffb-43b6-a1ca-8285c0ac662d" />


### ✅ Backend Console Logs

<img width="1914" height="967" alt="stats" src="https://github.com/user-attachments/assets/c783e705-dda7-4da8-b64a-26b5c3ac84ba" />


---

## Author

**Shreyas S**
Roll No: 212222040155
GitHub: [Shreyassanthosh7](https://github.com/Shreyassanthosh7)

---

## License

This project is built for educational purposes.



---

### To Use:
- Save this as README.md in the root of your project.
- Create a screenshots/ folder and add your images (e.g., register.png, shorten.png, backend.png).

Let me know if you also want a .gitignore or package.json cleanup!
```
