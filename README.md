<html>
  <head>
    <!-- This is your page title that appears on the browser window or tab -->
   

  </head>
  <body>
      <section id="home">
           <!-- This is the main heading -->
    <header><b>Unit Conversions</b></header>
    <nav>
        <!-- Button for redirecting users to the temperature section -->
        <a href="#temperature"><button>Temperature</button></a>
        <!-- Button for redirecting users to the weight section -->
        <a href="#weight"><button>Weight</button></a>
        <!-- Button for redirecting users to the distance section -->
        <a href="#distance"><button>Distance</button></a>
      </nav>
      </section>
      <div id="all-conversion-sections">
        <!-- This will have the conversion sections for Temperature, Weight, and Distance -->
        <section id="temperature">
        <!-- Temparature conversion section -->
        <div id="tmp">
            <figure>
                <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-CD0101EN-SkillsNetwork/labs/Theia%20Labs/02%20-%20HTML5%20Elements/images/thermo.png" width="200px"/>
                <figcaption>Celsius to Fahrenheit Conversion</figcaption>
              </figure>
              <article>
                <!-- This contains the specific elements for temperature conversion-->
                <fieldset>
                    <legend>Temperature</legend>
                   
                    <!-- The fields and button for temperature input will come here -->
                  <!-- Label for Temperature input -->
  <label for="Temperature">Celsius</label> <br/>
  <input type="number" id="c"> <br/>
  <!-- Label for Temperature output -->
  <button id="temperature"> Convert </button> <br/>
  <input type="number" id="f"> <br/>
  <label for="Temperature">Fahrenheit</label>
                </fieldset>
            </article>
            <button id="temperature"> Convert </button> <br/>
          </div>
        </section>
      </div>
  </body>
</html>
