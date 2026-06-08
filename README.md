@import url('https://fonts.googleapis.com/css2?family=Cairo:wght@400;700;900&display=swap');

body {
margin: 0;
font-family: "Cairo", sans-serif;
background: radial-gradient(circle at top, #1a001f, #000);
color: white;
}

header {
text-align: center;
padding: 40px;
background: linear-gradient(90deg, #6a00ff, #ff003c);
box-shadow: 0 0 30px #ff003c;
}

header h1 {
font-size: 40px;
text-shadow: 0 0 20px white;
}

nav {
display: flex;
justify-content: center;
flex-wrap: wrap;
gap: 10px;
padding: 15px;
background: #0b0010;
border-bottom: 2px solid #ff003c;
}

nav a {
color: white;
text-decoration: none;
padding: 10px 15px;
border-radius: 10px;
background: rgba(255,255,255,0.05);
transition: 0.3s;
}

nav a:hover {
background: #ff003c;
box-shadow: 0 0 15px #ff003c;
}

section {
width: 90%;
max-width: 1000px;
margin: 20px auto;
padding: 20px;
background: rgba(255,255,255,0.04);
border: 1px solid rgba(255,255,255,0.1);
border-radius: 15px;
}

h2 {
text-align: center;
color: #ff4d6d;
text-shadow: 0 0 10px #6a00ff;
}

ul {
list-style: none;
padding: 0;
}

li {
margin: 8px 0;
padding: 10px;
background: rgba(255,255,255,0.05);
border-left: 4px solid #ff003c;
border-radius: 8px;
transition: 0.3s;
}

li:hover {
transform: scale(1.02);
background: rgba(255,0,60,0.2);
box-shadow: 0 0 10px #ff003c;
}

form input, form select {
width: 100%;
padding: 10px;
margin: 6px 0;
border: none;
border-radius: 10px;
}

form button {
width: 100%;
padding: 12px;
background: linear-gradient(90deg, #6a00ff, #ff003c);
border: none;
color: white;
font-size: 18px;
border-radius: 10px;
cursor: pointer;
box-shadow: 0 0 15px #ff003c;
}

form button:hover {
transform: scale(1.05);
}

#offers div {
padding: 15px;
margin: 10px 0;
background: rgba(255,255,255,0.05);
border-radius: 10px;
border-left: 4px solid #6a00ff;
}
