# Muiyanaturals
Muiyanaturals homepage...beginners project 
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Muiyanaturals Homepage</title>
    <style>
      body {
        background-color: #fed39f;
        font-family: "Courier New", Courier, monospace;
      }
      h1 {
        text-align: center;
        font-size: 42px;
      }
      .subheading {
        font-size: 16px;
        line-height: 20px;
        font-style: italic;
        font-weight: lighter;
      }
      .about {
        font-weight: bolder;
        color: green;
        text-decoration: underline;
      }
      .offers {
        font-weight: bolder;
        color: red;
        text-decoration: underline;
      }
      .photos {
        font-weight: bolder;
        color: purple;
        text-decoration: underline;
      }
      .reachout {
        font-weight: bolder;
        color: blue;
        text-decoration: underline;
      }

      img {
        width: 300px;
        margin: 0 auto;
        display: block;
        border-radius: 5px;
        padding: auto;
      }
      h2 {
        text-align: center;
        margin: 20px 0 auto 20px 0 auto;
      }
      ul {
        padding: 0;
        margin: 20px;
        text-align: center;
        list-style: none;
      }
      li {
        text-align: center;
        line-height: 20px;
        display: inline;
        padding: 16px;
        margin: 20px 20px 20px 20px;
      }
      button {
        display: block;
        margin: 0 auto;
        padding: 15px 20px;
        font-weight: lighter;
        color: whitesmoke;
        font-size: 16px;
        background: #a75265;
        border-radius: 20px;
        border: 1px solid black;
        box-shadow: 5px 5px 10px #a75265;
        transition: all 200ms ease-in-out;
      }
      button:hover {
        background: burlywood;
        cursor: pointer;
        color: black;
      }
      p {
        text-align: center;
        font-size: 16px;
        font-style: italic;
        margin: 20px 0 auto 20px;
      }
      .insta {
        color: red;
      }
      .webcontact {
        color: red;
      }
    </style>
  </head>
  <body>
    <h1>
      <strong
        >MuiyaNaturals
        <div class="subheading">Your Hair & Skin Haven</div></strong
      >
    </h1>
    <ul>
      <li class="about"><strong>About us</strong></li>
      <li class="offers"><strong>Products & Services</strong></li>
      <li class="photos"><strong>Gallery</strong></li>
      <li class="reachout"><strong>Contact us</strong></li>
    </ul>
    <img
      src="https://data.whicdn.com/images/303340075/original.jpg"
      alt="dreadlocksWoman"
    />
    <h2>
      Muiyanaturals is committed to ensuring <br />
      you have the most healthy and beautiful dreadlocks. <br />
      With over 10 years of experience in making <br />
      dreadlocks, your dreadlocks journey with us is guarranteed.
    </h2>
    <button><strong>Book Appointment</strong></button>

    <p>
      <span class="insta">Instagram:</span> @muiyanaturals
      <span
        ><span class="webcontact">Email:</span> muiyagoglobal@gmail.com</span
      >
    </p>
    <script>
      function bookAppointment() {
        let clientName = prompt("What is your name?");
        let age = prompt("What is your age?");
        let clientEmail = prompt("What is your email address?");
        let heading = document.querySelector("p");
        if (age <= 5) {
          heading.innerHTML =
            "Sorry " + clientName + ", We only take clients 6years and above";
        } else {
          heading.innerHTML =
            "Thank You " +
            clientName +
            " An email has been sent to " +
            clientEmail +
            " regarding apppoinment date";
        }
      }

      let bookAppointmentbutton = document.querySelector("button");
      bookAppointmentbutton.addEventListener("click", bookAppointment);
    </script>
  </body>
</html>
