<!DOCTYPE html>
<html lang="en">
  <head>
    <style>
body {
    background-color: #9fd3c7;
    font-family: papyrus;
    text-align: center;
}
form {
    background-color: #ffffff;
    max-width: 500px;
    margin: 50px auto;
    padding: 30px 20px;
    box-shadow: 2px 5px 10px rgba(0, 0, 0, 0.5);
}
.form-control {
    text-align:left;
    margin-bottom:15px;
}


.form-control label {
    display: block;
    margin-bottom: 5px;
}
 .form-control input[type="text"],
 .form-control textarea {
    border: 1px solid #777;
    border-radius: 2px;
    font-family: inherit;
    padding: 10px;
    display: block;
    width: 100% ;
 }



 .form-control input[type="radio"],
 .form-control input[type="checkbox"] {
    margin-right: 5px;
 }


 button {
    background-color: rgba(69, 219, 139, 0.74);
    border: 1px solid #777;
    font-family: inherit;
    border-radius: 2px;
    font-size: 21px;
    display: block;
    width: 100%;
    margin-top: 20px;
    margin-bottom: 20px;
 }
    </style>
  </head>

  <body>
    <h1>Survey form</h1>
    <form id="form">
      <div class="form-control">
        <label for="name" id="lable-nama">Name</label>
        <input type="text" id="name" placeholder="Enter your name" />
        <label for="email" id="lable-email">Email</label>
        <input type="text" id="email" placeholder="Enter your email" />
        <label for="age" id="lable-age">Age</label>
        <input type="text" id="age" placeholder="Enter your age" maxlength="2"/>
      </div>
      <div class="form-control">
        <label> Are you happy?</label>
        <label> <input type="radio" name="happy" id="recommed-1">Yes</label>
        <label> <input type="radio" name="happy" id="recommed-2">No</label>
        <label> <input type="radio" name="happy" id="recommed-3">Maybe</label>
      </div>
      <div class="form-control">
        <label>
          Language and Frameworks know
          <small>(Check all that apply)</small>
        </label>
        <label for="inp-1">
        <input type="checkbox" name="inp" />C
        </label>
        <label for="inp-2">
          <input type="checkbox" name="inp">JavaScript
        </label>
        <label for="inp-3">
          <input type="checkbox" name="inp">python
        </label>
      </div>
      <div class="form-control">
        <label for="comment">Any comment or suggestion</label>
        <textarea name="comment" id="comment" placeholder="Enter your comment here"></textarea>
      </div>
      <button type="submit" value="submit">Submit</button>
    </form>
  </body>
</html>
