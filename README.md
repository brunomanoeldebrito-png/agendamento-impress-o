.container {
  max-width: 700px;
  margin: 30px auto;
  background: #fff;
  padding: 30px;
  border-radius: 12px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
}

h1 {
  text-align: center;
  background-color: #000;
  color: #fff;
  padding: 20px;
  border-radius: 8px;
  position: relative;
  z-index: 1;
}

h1::after {
  content: "";
  background: url('https://i.imgur.com/4ZQzJ0s.png') no-repeat center;
  opacity: 0.1;
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-size: contain;
  z-index: 0;
}

h2 {
  text-align: center;
  color: #333;
}

table {
  width: 100%;
  border-collapse: collapse;
  margin: 20px 0;
}

th, td {
  border: 1px solid #ccc;
  padding: 10px;
  text-align: center;
}

th {
  background-color: #f7f7f7;
}

button {
  background-color: #28a745;
  color: white;
  font-weight: bold;
  cursor: pointer;
  transition: background-color 0.3s ease;
  margin-top: 20px;
  padding: 10px 15px;
  border: none;
  border-radius: 6px;
  width: 100%;
}

button:hover {
  background-color: #218838;
}

input, select {
  width: 100%;
  padding: 10px;
  margin-top: 5px;
  border-radius: 6px;
  border: 1px solid #ccc;
  font-size: 16px;
  box-sizing: border-box;
}

.hidden {
  display: none;
}

@media (max-width: 600px) {
  .container {
    padding: 20px;
    margin: 10px;
  }
}



