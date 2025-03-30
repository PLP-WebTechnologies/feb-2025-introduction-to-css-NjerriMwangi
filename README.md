# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced HTML5 Elements and Form</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <section>
        <h2>Ordered List (Roman Numerals)</h2>
        <ol type="a">
            <li>First item</li>
            <li>Second item</li>
            <li>Third item</li>
            <li>Fourth item</li>
        </ol>
    </section>
    <section>
        <h2>Favourite scenery</h2>
        <img class = "scenerypic" src="data:image/jpeg;base64,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" 
             width="600"
             style="max-width: 100%; height: auto;">
    </section>
    <section>
        <h2>Table</h2>
        <table>
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Mary Mwangi</td>
                    <td>254 797 569</td>
                    <td>mary@gmail.com</td>
                </tr>
                <tr>
                    <td>Mary Mwangi</td>
                    <td>254 797 569</td>
                    <td>mary@gmail.com</td>
                </tr>
                <tr>
                    <td>Emily Davis</td>
                    <td>255 764</td>
                    <td>emily@yahoo.com</td>
                </tr>
                <tr>
                    <td>Michael Brown</td>
                    <td>257 055</td>
                    <td>michael@gmail.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <section>
        <h2>Registration Form</h2>
        <form action="/submit" method="post">
            <div class="form-group">
                <label for="name">Full Name:</label>
                <input type="text" id="name" name="name" 
                       placeholder="Enter your full name" 
                       required
                       minlength="3">
            </div>

            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" 
                       placeholder="Enter your email" 
                       required>
            </div>

            <div class="form-group">
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" 
                       placeholder="Create a password" 
                       required
                       minlength="8">
            </div>

            <div class="form-group">
                <label for="birthdate">Date of Birth:</label>
                <input type="date" id="birthdate" name="birthdate" required>
            </div>

            <div class="form-group">
                <label for="country">Country:</label>
                <select id="country" name="country" required>
                    <option value="" disabled selected>Select your country</option>
                    <option value="usa">Kenya</option>
                    <option value="canada">Uganda</option>
                    <option value="uk">Tanzania</option>
                    <option value="australia">Sudan</option>
                    <option value="other">Other</option>
                </select>
            </div>

            <div class="form-group">
                <label>Gender:</label>
                <div>
                    <input type="radio" id="male" name="gender" value="male" required>
                    <label for="male" style="display: inline;">Male</label>
                </div>
                <div>
                    <input type="radio" id="female" name="gender" value="female">
                    <label for="female" style="display: inline;">Female</label>
                </div>
                <div>
                    <input type="radio" id="other" name="gender" value="other">
                    <label for="other" style="display: inline;">Other</label>
                </div>
            </div>

            <div class="form-group">
                <label>Interests (select all that apply):</label>
                <div>
                    <input type="checkbox" id="sports" name="interests" value="sports">
                    <label for="sports" style="display: inline;">Sports</label>
                </div>
                <div>
                    <input type="checkbox" id="music" name="interests" value="music">
                    <label for="music" style="display: inline;">Music</label>
                </div>
                <div>
                    <input type="checkbox" id="reading" name="interests" value="reading">
                    <label for="reading" style="display: inline;">Reading</label>
                </div>
            </div>
            <button class="form-group">
                <input type="submit" value="Register">
            </button>
        </form>
    </section>
</body>
</html>
CSS!
/*  Type Simple selector for paragraphs */
p {
  color: #333;
  font-size: 16px;
}
body 
{ font-family: Arial, sans-serif; line-height: 1.6; max-width: 800px; margin: 0 auto; padding: 20px; 
}
 
table 
        
        { width: 100%; border-collapse: collapse; margin: 20px 0; }

        th, td 
        { border: 1px solid #ddd; padding: 8px; text-align: left; 
        }
        th 
        { background-color: #f2f2f2; 
        }
        form 
        { background: #f9f9f9; padding: 20px; border-radius: 5px; 
        }
        /* Class Simple selector */
        .form-group 
        { margin-bottom: 15px; 
          padding: 30px;
          border-radius: 34px;
        }
        label 
        { display: block; margin-bottom: 5px; 
        }
        /* Group Simple selector */
        input, select, textarea 
        {
           width: 100%; padding: 8px; box-sizing: border-box; 
        }
        .scenerypic {
          width: 100px; height: auto; border-radius: 10px; margin-top: 20px; 
        }
