body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  margin: 0;
  padding: 0;
  background-color: #f9f9f9;
  color: #333;
}

header {
  background: #ffcccb;
  color: #fff;
  padding: 10px 0;
  text-align: center;
}

header h1 {
  margin: 0;
}

nav ul {
  list-style: none;
  padding: 0;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
}

.section {
  padding: 20px;
  background: #fff;
  margin: 20px 0;
}

.container {
  width: 80%;
  margin: auto;
  overflow: hidden;
}

.cat-list {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}

.cat-item {
  flex: 1 1 calc(50% - 20px);
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  padding: 10px;
  text-align: center;
}

.cat-item img {
  max-width: 100%;
  height: auto;
}

footer {
  background: #333;
  color: #fff;
  text-align: center;
  padding: 10px 0;
}
