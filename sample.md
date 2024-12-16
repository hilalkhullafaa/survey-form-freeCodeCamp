<h1 id="title">Survey Form</h1>
<p id="description">Thanks you for collaboration</p>

<form id="survey-form">
<label id="name-label">Name: <input type="text" id="name" required placeholder="Name"></label>
<label id="email-label">Email: <input type="email" required id="email" placeholder="Email"></label>
<label id="number-label">Age (option) <input id="number" min="1" max="100" type="number" placeholder="age"></label>

<label>what's Your Role?
<select id="dropdown">

  <option disable>Select your role...</option>
  <option>FullStack Developer</option>
  <option>Front-end Developer</option>
  <option>Back-end Developer</option>
</select>
</label>

<p>Would you recommend freeCodeCamp to a friend?
  </p>
   <label>
            <input type="radio" name="gender" value="male"> Laki-laki
        </label><br>
        <label>
            <input type="radio" name="gender" value="female"> Perempuan
        </label><br>
        <label>
            <input type="radio" name="gender" value="other"> Lainnya
        </label>

<p>where did you get the information from?</p>
<label>Instagram <input type="checkbox" value="instagram"><label>
  <br>
<form>Facebook <input type="checkbox" value="facebook"><label>

  <p>Any comments or suggestions?</p>
  <textarea placeholder="Write in here..." cols="30" rows="3"></textarea>
  <br>
  <button id="submit" type="submit">
  Send
  </button>
</label>
</form>
