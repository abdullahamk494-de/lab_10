body {
    font-family: Arial, sans-serif;
    background-color: #f0f4f8;
    margin: 0;
    padding: 20px;
    color: #333;
}

.container {
    width: 85%;
    margin: auto;
    background-color: white;
    padding: 25px;
    border-radius: 12px;
    box-shadow: 0 0 15px rgba(0,0,0,0.1);
}

header {
    text-align: center;
    background-color: #17365d;
    color: white;
    padding: 20px;
    border-radius: 10px;
}

header h1 {
    margin: 5px;
}

header h2 {
    color: white;
    border: none;
    margin: 5px;
}

p {
    line-height: 1.7;
    font-size: 16px;
}

h2 {
    color: #17365d;
    border-bottom: 2px solid #3498db;
    padding-bottom: 7px;
    margin-top: 25px;
}

ul {
    background-color: #eaf2f8;
    padding: 15px 35px;
    border-radius: 8px;
}

li {
    padding: 5px;
}

li:hover {
    color: #0077b6;
}

table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 15px;
    margin-bottom: 25px;
}

th {
    background-color: #17365d;
    color: white;
    padding: 12px;
    border: 1px solid #ccc;
}

td {
    padding: 12px;
    text-align: center;
    border: 1px solid #ccc;
}

tr:nth-child(even) {
    background-color: #eaf2f8;
}

tr:hover {
    background-color: #d6eaf8;
}

.contact {
    background-color: #eaf2f8;
    padding: 15px;
    border-left: 5px solid #3498db;
    border-radius: 5px;
}

footer {
    text-align: center;
    background-color: #17365d;
    color: white;
    padding: 12px;
    margin-top: 25px;
    border-radius: 8px;
}

@media (max-width: 768px) {
    .container {
        width: 95%;
        padding: 12px;
        box-sizing: border-box;
    }

    table {
        font-size: 12px;
    }

    th, td {
        padding: 7px;
    }
}
