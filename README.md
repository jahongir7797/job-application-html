# job-application-html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Job Application Form</title>
</head>
<body>
<h2>Job Application</h2>
<form action="submit.php" method="POST">
  <label for="full_name">Full Name*</label><br>
  <input type="text" id="first_name" name="first_name" placeholder="First Name" required><br>
  <input type="text" id="middle_name" name="middle_name" placeholder="Middle Name"><br>
  <input type="text" id="last_name" name="last_name" placeholder="Last Name" required><br>

  <label for="body_size">Body Size*</label><br>
  <input type="text" id="height" name="height" placeholder="Height" required> sm<br>
  <input type="text" id="weight" name="weight" placeholder="Weight" required> kg<br>

  <label for="birth_date">Birth Date*</label><br>
  <select id="month" name="month">
    <option value="1">January</option>
    <!-- Add other months -->
  </select>
  <select id="day" name="day">
    <!-- Add days -->
  </select>
  <select id="year" name="year">
    <!-- Add years -->
  </select><br>

  <label for="family_status">Family Status</label><br>
  <!-- Add options for family status -->
  
  <label for="current_address">Current Address</label><br>
  <input type="text" id="street_address" name="street_address" placeholder="Street Address" required><br>
  <input type="text" id="street_address_2" name="street_address_2" placeholder="Street Address Line 2"><br>
  <!-- Add other address fields -->

  <label for="email">Email Address</label><br>
  <input type="email" id="email" name="email" placeholder="example@example.com" required><br>

  <label for="phone_number">Phone Number</label><br>
  <input type="tel" id="area_code" name="area_code" placeholder="Area Code" required>
  <input type="tel" id="phone_number" name="phone_number" placeholder="Phone Number" required><br>

  <label for="linkedin">LinkedIn</label><br>
  <input type="url" id="linkedin" name="linkedin" placeholder="LinkedIn Profile URL"><br>

  <label for="experience">Experience</label><br>
  <!-- Add options for experience -->

  <label for="position_applied">Position Applied</label><br>
  <select id="position_applied" name="position_applied">
    <!-- Add positions -->
  </select><br>

  <label for="how_hear_about_us">How did you hear about us</label><br>
  <!-- Add options for how you heard about them -->

  <label for="available_start_date">Available Start Date</label><br>
  <input type="date" id="available_start_date" name="available_start_date" value="2024-06-14"><br>

  <label for="computer_skills">Computer Skills</label><br>
  <!-- Add checkboxes or dropdowns for computer skills -->

  <label for="english_ability">Ability knowing English Language</label><br>
  <!-- Add radio buttons or dropdown for English ability -->

  <label for="applicant_document">Applicant Document(Diploma, Certificate)</label><br>
  <input type="file" id="applicant_document" name="applicant_document"><br>

  <label for="resume">Upload Your Resume</label><br>
  <input type="file" id="resume" name="resume"><br>

  <label for="cover_letter">Cover Letter</label><br>
  <textarea id="cover_letter" name="cover_letter" rows="4" cols="50"></textarea><br>

  <input type="submit" value="Apply">
</form>
</body>
</html>
