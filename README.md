# 8.HTML-forms-with-radio-and-select-buttons
# program:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Form Example</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
        }
        form {
            max-width: 400px;
            margin: 0 auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .form-group {
            margin-bottom: 15px;
        }
        label {
            display: block;
            margin-bottom: 5px;
        }
        input[type="text"],
        select {
            width: 100%;
            padding: 8px;
            box-sizing: border-box;
        }
        .radio-group {
            display: flex;
            justify-content: space-between;
        }
        .radio-group label {
            margin-right: 10px;
        }
        button {
            background-color: #333;
            color: white;
            border: none;
            padding: 10px 15px;
            cursor: pointer;
            width: 100%;
            box-sizing: border-box;
            font-size: 16px;
            border-radius: 5px;
        }
    </style>
</head>
<body>

<form action="#" method="POST">
    <div class="form-group">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
    </div>

    <div class="form-group">
        <label>Gender:</label>
        <div class="radio-group">
            <label for="male">
                <input type="radio" id="male" name="gender" value="male" required> Male
            </label>
            <label for="female">
                <input type="radio" id="female" name="gender" value="female" required> Female
            </label>
            <label for="other">
                <input type="radio" id="other" name="gender" value="other" required> Other
            </label>
        </div>
    </div>

    <div class="form-group">
        <label for="country">Country:</label>
        <select id="country" name="country" required>
            <option value="">Select a country</option>
            <option value="USA">United States</option>
            <option value="CANADA ">Canada</option>
            <option value="UK">United Kingdom</option>
            <option value="AUSTRALIA">Australia</option>
            <option value="INDIA">India</option>
        </select>
    </div>

    <div class="form-group">
        <button type="submit">Submit</button>
    </div>
</form>

</body>
</html>
```
# output:
![image](https://github.com/samson0512/8.HTML-forms-with-radio-and-select-buttons/assets/172907275/ba667ab3-b0fe-4bff-98f8-96469c8657cc)
