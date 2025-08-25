body {
  margin: 0;
  padding: 0;
  font-family: 'Poppins', sans-serif;
  background: linear-gradient(135deg, #667eea, #764ba2);
  color: #fff;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
  text-align: center;
}

h1 {
  font-size: 2.5rem;
  margin-bottom: 10px;
  text-shadow: 2px 2px 6px rgba(0,0,0,0.3);
}

.sub {
  font-size: 1.1rem;
  margin-bottom: 20px;
  opacity: 0.9;
}

.quote {
  background: rgba(255, 255, 255, 0.15);
  border-radius: 15px;
  padding: 25px;
  font-size: 1.3rem;
  max-width: 600px;
  margin: 20px auto;
  box-shadow: 0px 8px 20px rgba(0,0,0,0.3);
  transition: transform 0.3s ease-in-out;
}

.quote:hover {
  transform: scale(1.02);
}

.controls {
  margin-top: 20px;
  display: flex;
  gap: 15px;
  justify-content: center;
}

button {
  background: linear-gradient(45deg, #ff758c, #ff7eb3);
  border: none;
  border-radius: 30px;
  padding: 12px 25px;
  font-size: 1rem;
  font-weight: bold;
  color: white;
  cursor: pointer;
  box-shadow: 0px 4px 12px rgba(0,0,0,0.3);
  transition: transform 0.2s, box-shadow 0.2s;
}

button:hover {
  transform: translateY(-2px);
  box-shadow: 0px 6px 15px rgba(0,0,0,0.4);
}

.foot {
  margin-top: 25px;
  font-size: 0.9rem;
  opacity: 0.8;
}
