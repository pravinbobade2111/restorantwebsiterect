/* styles.css */

body {
  margin: 0;
  font-family: 'Arial', sans-serif; /* Adjust the font-family as needed */
}

/* Add any other global styles here */


/* Header.css */

body {
  margin: 0;
  font-family: 'Arial', sans-serif; /* Adjust the font-family as needed */
}

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px;
  background: url('./images/background.jpg') center/cover; /* Adjust the path and properties as needed */
  color: #fff; /* You can adjust the text color */
}

.logo {
  font-size: 24px;
  font-weight: bold;
}

.nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

.nav li {
  cursor: pointer;
}

.cart {
  display: flex;
  align-items: center;
  cursor: pointer;
}

.cart-count {
  background-color: #fff; /* You can adjust the background color */
  color: #333; /* You can adjust the text color */
  padding: 5px 10px;
  border-radius: 50%;
  margin-left: 5px;
}


// App.js

import React from 'react';
import Header from './Header';
import './styles.css'; // Import global styles

const App = () => {
  return (
    <div>
      <Header />
      {/* Other components and content */}
    </div>
  );
};

export default App;
