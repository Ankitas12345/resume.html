<!DOCTYPE html>
<html>
<head>
    <title>Resume Form</title>
</head>
<body>

    <h2>Resume Submission Form</h2>

    <form>

        <label>Field Name:</label><br>
        <input type="text" name="fieldName"><br><br>

        <label>Full Name:</label><br>
        <input type="text" name="fullName" required><br><br>

        <label>Email Address:</label><br>
        <input type="email" name="email" required><br><br>

        <label>Phone Number:</label><br>
        <input type="tel" name="phone" required><br><br>

        <label>Date of Birth:</label><br>
        <input type="date" name="dob"><br><br>

        <label>Gender:</label><br>
        <select name="gender">
            <option value="">--Select--</option>
            <option>Male</option>
            <option>Female</option>
            <option>Other</option>
        </select><br><br>

        <label>Marital Status:</label><br>
        <select name="maritalStatus">
            <option value="">--Select--</option>
            <option>Single</option>
            <option>Married</option>
            <option>Other</option>
        </select><br><br>

        <label>Nationality:</label><br>
        <input type="text" name="nationality"><br><br>

        <label>Address:</label><br>
        <textarea name="address"></textarea><br><br>

        <label>LinkedIn Profile URL:</label><br>
        <input type="url" name="linkedin"><br><br>

        <label>GitHub Profile URL:</label><br>
        <input type="url" name="github"><br><br>

        <label>Upload Profile Photo:</label><br>
        <input type="file" name="photo" accept="image/*"><br><br>

        <label>Upload Resume (PDF Only):</label><br>
        <input type="file" name="resume" accept=".pdf"><br><br>

        <label>Career Objective:</label><br>
        <textarea name="objective"></textarea><br><br>

        <label>Highest Qualification:</label><br>
        <input type="text" name="qualification"><br><br>

        <label>College / University:</label><br>
        <input type="text" name="college"><br><br>

        <label>Year of Graduation:</label><br>
        <input type="number" name="graduationYear" min="1900" max="2099"><br><br>

        <label>Technical Skills (HTML, CSS, etc.):</label><br>
        <textarea name="skills"></textarea><br><br>

        <label>Programming Languages Known:</label><br>
        <textarea name="languages"></textarea><br><br>

        <label>Certifications (if any):</label><br>
        <textarea name="certifications"></textarea><br><br>

        <label>Work Experience (in years):</label><br>
        <input type="number" name="experience" min="0"><br><br>

        <label>Last Company Worked At:</label><br>
        <input type="text" name="lastCompany"><br><br>

        <label>Your Job Role / Designation:</label><br>
        <input type="text" name="jobRole"><br><br>

        <label>Languages Known:</label><br>
        <textarea name="knownLanguages"></textarea><br><br>

        <label>Hobbies:</label><br>
        <textarea name="hobbies"></textarea><br><br>

        <label>
            <input type="checkbox" name="declaration" required>
            I declare that the above information is true.
        </label><br><br>

        <input type="submit" value="Submit Resume">

    </form>

</body>
</html>
