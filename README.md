
    <main>


        <div class="personal_details">

            <p>Personal details</p>
            <ul>



                <li>Name: <input type="text" value="Enter name here" name="" id="name"></li>

                <li>Address: <input type="text" value="Enter address here" name="" id="address"></li>

                <li>Phone Number: <input type="text" value="Enter phone number here" name="ph_number" id=""></li>

                <li>IQ: <input type="text" value="Enter IQ here" name="IQ" id=""></li>

            </ul>

            <p style="font-weight: 100; margin-left: 0; margin-top: 2rem; margin-bottom: 1rem;">
                Gender:</p>
            <ul style="margin-bottom: 2rem;">
                <li style="margin:0 0 0 1rem;"><input type="radio" name="gender" id=""> Male </li>
                <li style="margin:0 0 0 1rem;"><input type="radio" name="gender" id=""> Female </li>
                <li style="margin:0 0 0 1rem;"><input type="radio" name="gender" id=""> Other </li>
            </ul>

            <p style="display: flex; max-width: 100%; font-size: 15px; font-weight: 100; margin-left: 0; margin-top: 2rem;">
                Date of Proposed Outing:<input type="date" name="" id=""></p>


        </div>

        <div class="check_apply">
            <p style="display: flex; max-width: 100%; font-weight: 100; margin-left: 0; margin-top: 1rem;">
                Check All That Apply
            </p>
            <ul>
                <li><input type="checkbox" name="" id=""> I have tattos and/or piercings </li>
                <li><input type="checkbox" name="" id=""> I am more than 2 years older than my daughter </li>
                <li><input type="checkbox" name="" id=""> I own a panel van or V8 ute </li>
                <li><input type="checkbox" name="" id=""> I work full-time </li>
                <li><input type="checkbox" name="" id=""> My parents are rich </li>
                <li><input type="checkbox" name="" id=""> Is the date at a well lit public location </li>
            </ul>
        </div>

        <div class="select">

            <p style="display: flex; max-width: 100%; font-weight: 100; margin-left: 0;">
                Political Persuasion:</p>
            <select name="Political" id="">
                        <option>Left Wing</option>
            </select>


            <p style="display: flex; max-width: 100%; font-weight: 100; margin-left: 0; margin-top: 1rem;">
                Education Level Completed:

            </p>
            <select>
                    <option value="">University</option>
                </select>


        </div>

        <div class="essay">
            <p>Essay Section</p>
            <p style="display: flex; max-width: 100%; font-weight: 100; margin-left: 0; margin-top: 1rem;">
                In 50 words or more explain why you want to date my daughter
            </p>
            <textarea name="" id="" cols="50" rows="5"> Enter Text Here </textarea>

            <p style="display: flex; max-width: 100%; font-weight: 100; margin-left: 0; margin-top: 2rem;">
                Please upload contact details for 2 references
            </p>
            <textarea name="" id="" cols="50" rows="5"> Enter Text Here </textarea>

            <p style="display: flex; max-width: 100%; font-weight: 100; margin-left: 0; margin-top: 2rem;">
                Upload Police Clearance Certificate, Bank Statement and Medical Certificates here:
            </p>
            <button style="border: none; background-color: white; cursor:default; color: lightgray; display: flex; font-size: 20px; max-width: 100%; font-weight: 100; margin: 1rem 1rem 1rem 1rem;">
                Attach Files
                </button>
        </div>

        <button type="submit" style="font-size: 25px; border: none; background-color: white; color: lightgray; position: relative; left: 30%; ">Send Ypur Application</button>

<style>* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}

html {
    height: 100%;
}

body {
    height: 100%;
}

main {
    width: 50%;
    border: 3px solid lightgray;
    border-radius: 10px;
    margin-left: 20%;
    margin-top: 2rem;
    margin-bottom: 2rem;
}

.personal_details {
    display: block;
    border: 1px solid lightgray;
    margin: 5rem 1rem 1rem 1rem;
}

input {
    border: 1px solid gray;
    border-radius: 3px;
    padding-left: 0.5rem;
    margin-left: 0.5%;
}

p {
    max-width: 25%;
    margin-left: 1rem;
    padding-left: 1rem;
    background-color: white;
    position: relative;
    top: -10px;
    font-weight: bold;
}

ul {
    list-style-type: none;
}

ul li {
    margin: 1rem 1rem 1rem 1rem;
}

.check_apply {
    display: block;
    border: 1px solid lightgray;
    margin: 1rem 1rem 1rem 1rem;
}

.select {
    display: flex;
    align-items: flex-end;
    justify-content: left;
    border: 1px solid lightgray;
    margin: 1rem 1rem 1rem 1rem;
}

select {
    display: block;
    position: relative;
    top: -10px;
    margin-left: 0.5rem;
}

.essay {
    display: block;
    border: 1px solid lightgray;
    margin: 1rem 1rem 1rem 1rem;
}

textarea {
    display: flex;
    margin-left: 1rem;
    margin-bottom: 2rem;
    width: 60%;
    height: 30%;
} </style>
    </main>
