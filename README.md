## Hi there 👋

<!--
**amservicespro/amservicespro** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

header {
    background: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    margin: 10px 0;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.hero {
    background: url('construction.jpg') no-repeat center center/cover;
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: #fff;
}

.hero h2 {
    font-size: 2.5em;
}

.hero p {
    font-size: 1.2em;
    margin: 20px 0;
}

.hero .btn {
    background: #f4b41a;
    color: #333;
    padding: 10px 20px;
    text-decoration: none;
    font-size: 1.2em;
    border-radius: 5px;
}

.about, .services, .contact {
    padding: 50px 20px;
    text-align: center;
}

.about h2, .services h2, .contact h2 {
    font-size: 2em;
    margin-bottom: 20px;
}

.services ul {
    list-style: none;
}

.services ul li {
    margin-bottom: 10px;
    font-size: 1.2em;
}

form {
    max-width: 600px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
}

form label {
    margin-bottom: 10px;
    text-align: left;
}

form input, form textarea {
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 1em;
}

form button {
    background: #333;
    color: #fff;
    padding: 10px;
    border: none;
    cursor: pointer;
    font-size: 1.2em;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    margin-top: 50px;
}
