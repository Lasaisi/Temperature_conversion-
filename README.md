<!DOCTYPE html>
<html>
  <head>
    <!-- This is your page title that appears on the browser window or tab -->
    <title>Unit Conversions</title>
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
        <section id="weight">
            <!-- Weight conversion section -->
            <div id="wgt">
                <figure>
                    <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-CD0101EN-SkillsNetwork/labs/Theia%20Labs/02%20-%20HTML5%20Elements/images/weight.png" width="200px"/>
                    <figcaption>Kilogram to Pound Conversion</figcaption>
                </figure>
                <article>
                    <!-- This contains the specific elements for weight conversion -->
                    <fieldset>
                        <legend>Weight</legend>
                        <!-- Label for Weight input -->
                        <label for="Weight">Kilograms</label> <br/>
                        <input type="number" id="kg"> <br/>
                        <!-- The conversion button -->
                        <button id="weight"> Convert </button> <br/>
                        <!-- Label for Weight output -->
                        <input type="number" id="lbs"> <br/>
                        <label for="Weight">Pounds</label>
                    </fieldset>
                </article>
                <aside>
                    To convert kilograms to pounds yourself, use this formula replacing the `kg` with your weight in kilograms: kg x 2.205
                </aside>
            </div>
        </section>
        <section id="distance">
            <!-- Distance conversion section -->
            <div id="dst">
                <figure>
                    <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-CD0101EN-SkillsNetwork/labs/Theia%20Labs/02%20-%20HTML5%20Elements/images/speedo.png" width="200px"/>
                    <figcaption>Kilometer to Mile Conversion</figcaption>
                </figure>
                <article>
                    <!-- This contains the specific elements for distance conversion -->
                    <fieldset>
                        <legend>Distance</legend>
                        <!-- Label for Distance input -->
                        <label for="Distance">Kilometers</label> <br/>
                        <input type="number" id="km"> <br/>
                        <!-- The conversion button -->
                        <button id="distance"> Convert </button> <br/>
                        <!-- Label for Distance output -->
                        <input type="number" id="m"> <br/>
                        <label for="Distance">Miles</label>
                    </fieldset>
                </article>
                <aside>
                    To convert kilometers to miles yourself, use this formula replacing the `km` with your distance in kilometers: km &divide; 1.609
                </aside>
            </div>
       </section>
       <footer>Learn more about HTML as a part of the IBM Fullstack Cloud Developer Certification</footer>
      </div>
  </body>
</html>
