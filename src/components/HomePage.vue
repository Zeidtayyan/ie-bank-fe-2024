<template>
    <div class="welcome-container">
      <h1 class="welcome-title">Welcome to IE Banking</h1>
      <nav class="navigation">
        <router-link to="/accounts" class="link-button">Accounts</router-link>
        <router-link to="/skull" class="link-button">Skull</router-link>
      </nav>
    </div>
  </template>
  
  <style scoped>
  .welcome-container {
    text-align: center;
    padding: 20px;
  }
  
  .welcome-title {
    font-size: 2em;
    margin-bottom: 20px;
  }
  
  .navigation {
    display: flex;
    justify-content: center;
    gap: 15px;
  }
  
  .link-button {
    padding: 10px 20px;
    background-color: #007bff;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s;
  }
  
  .link-button:hover {
    background-color: #0056b3;
  }
  </style>
  