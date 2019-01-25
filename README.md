# Survey-Form
Survey Form for Green Street Gym
<script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>

<main id="main">
  <h1 id="title">Survey Form</h1>  
  <div id="grey-box">    
    <p id="description"> We are always striving for improvement. <br> Help us improve Green Street Gym!</p>
    
    <form id="survey-form">
      <label id="name-label">* Name: </label>
        <input id="name" type="text" class="textbox" placeholder="Enter your name" required>      
      <br>
      <label id="email-label">* E-mail: </label>
       <input id="email" type="email" class="textbox" placeholder="Enter your e-mail" required>        
      <br>
      <label id="number-label"> Age: </label>
        <input id="number" type="number" class="textbox" min="1" max="150" placeholder="Enter your age"> 
      <br>
      
      <div>        
        <label>Roughly how many times per week do you visit Green Street Gym?</label>
      <div>  
        <select id="dropdown" name="perWeek">
          <option disabled selected value="Select an option">Select an option</option>
          <option value="Less than 1">Less than 1</option> 
          <option value="1-2">1-2</option>
          <option value="2-3">2-3</option>
          <option value="3-4">3-4</option>
          <option value="4-5">4-5</option>
          <option value="5-6">5-6</option>
          <option value="6-7">6-7</option>
          <option value="7-10">7-10</option>
          <option value="More than 10">More than 10</option>
        </select>
        </div>
      </div>
        <br>
      
      <label for="rating">A friend says to you, "Friend, I'm looking for a gym." How likely would you be to recommend Green Street Gym?</label>
      <ul style="list-style: none;">
        <li> <label> Very likely <input name="rating" type="radio" value="1"> </label> </li>
        <li> <label> Somewhat likely <input name="rating" type="radio" value="2"> </label> </li>
        <li> <label> Indifferent <input name="rating" type="radio" value="3"> </label> </li>
        <li> <label> Probably not <input name="rating" type="radio" value="4"> </label> </li>
        <li> <label> Very unlikely <input name="rating" type="radio" value="5"> </label> </li>
      </ul>
            
      <label for"use"> Which of the following do you use at Green Street Gym? Check all that apply:</label>
        <ul id="uses" style="list-style: none">
          <div class="uses1">
          <li> <label> Treadmill <input name="use" type="checkbox" value="Treadmill"> </label> </li>
          <li> <label> Elliptical <input name="use" type="checkbox" value="Elliptical"> </label> </li>
          <li> <label> Stairmaster <input name="use" type="checkbox" value="Stairmaster"> </label> </li>
          <li> <label> Exercise bike <input name="use" type="checkbox" value="Exercise bike"> </label> </li>
          <li> <label> Running/walking track <input name="use" type="checkbox" value="Track"> </label> </li>
          <li> <label> Rowing machine <input name="use" type="checkbox" value="Rowing machine"> </label> </li>
          <li> <label> Stretching/Yoga area <input name="use" type="checkbox" value="Stretching/Yoga area"> </label> </li>
          <li> <label> Punching bags <input name="use" type="checkbox" value="Punching bags"> </label> </li>
          </div>
          <div class="uses2">
          <li> <label> Free weights <input name="use" type="checkbox" value="Free weights"> </label> </li>
          <li> <label> Weight machines <input name="use" type="checkbox" value="Weight machines"> </label> </li>   
          <li> <label> Locker rooms or showers<input name="use" type="checkbox" value="Locker rooms or showers"> </label> </li>
          <li> <label> Sauna <input name="use" type="checkbox" value="Sauna"> </label> </li>
          <li> <label> Swimming pool <input name="use" type="checkbox" value="Swimming pool"> </label> </li>
          <li> <label> Basketball courts <input name="use" type="checkbox" value="Basketball courts"> </label> </li>
          <li> <label> Racquetball courts <input name="use" type="checkbox" value="Racquetball courts"> </label> </li>
          </div>
      </ul>
      <br>
      
      <label for="comment"> Please, tell us how you feel! If you have any suggestions, comments, concerns, compliments, criticisms - please provide them below.</label>
      <textarea id="comments" class="input-field" placeholder="Enter your feedback here...">        
      </textarea>  
      <button type="submit" id="submit"> Submit 
      </button>
      <br>
     </form>
  </div> <!-- end survey box -->
  
</main>  
