<template>
    <header class="header">
      <div class="logo">Your Logo</div>
      <ul class="navigation">
        <li><a href="/">Home</a></li>
        <li><a href="/dashboard">Dashboard</a></li>
        <li><a href="/about us">About Us</a></li>
      </ul>
      <button class="cta-button">Get Started</button>
    </header>
  </template>
  
  <style>
  .header {
    background-color: #ffffff;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px;
  }
  
  .header .logo {
    font-size: 24px;
    font-weight: bold;
    color: #00cc66;
  }
  
  .header .navigation {
    list-style: none;
    display: flex;
    gap: 20px;
  }
  
  .header .navigation li a {
    color: #333333;
    text-decoration: none;
    transition: color 0.3s ease;
  }
  
  .header .navigation li a:hover {
    color: #00cc66;
  }
  
  .header .cta-button {
    background-color: #00cc66;
    color: #ffffff;
    padding: 10px 20px;
    border: none;
    border-radius: 4px;
    font-size: 16px;
    cursor: pointer;
    transition: background-color 0.3s ease;
  }
   
  .header .cta-button:hover {
    background-color: #00994d;
  }
  </style>