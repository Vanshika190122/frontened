import React, { useState } from 'react';

import './App.css';


const App = () => {

const [jsonInput, setJsonInput] = useState('');

const [responseData, setResponseData] = useState(null);

const [error, setError] = useState('');

const [filters, setFilters] = useState({

alphabets: false,

numbers: false,

highestAlphabet: false,

});


const handleInputChange = (event) => {

setJsonInput(event.target.value);

};


const handleFilterChange = (event) => {

const { name, checked } = event.target;

setFilters((prevFilters) => ({ <html>

<head>

<title>Hello World!</title>


<style>

.button {

background-color: #4CAF50;

</style>

</head>

<body style="text-align:center;"style="font-family: Times new roman";background-color: rgb(255, 122, 89);>


<style>

.button {

background-color: #4CAF50;

</style>

<h1 style=" color:red"><center>MAVERICKS CLASSROOM</center></h1>

<h2 style="color:blue" class="title"><center>LOGIN PAGE</center> </h2>

<form>

<b>Username :</b>

<input type="text" name="Fname"><br>

<b>Password :</b>

<input type="text" name="Fname"><br>

<button class="button"><n><b><t>LOGIN</t></b></n></button>

<td>

Not have an account!<a href="">Register</a>

</td>

</form>

</body>

</html>
</body>
</html>
