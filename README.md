<!DOCTYPE html>
<html>

<head> 
    <title>Forms</title>
</head>

<body>
    <form>
        <!-- <fieldset>
            <legend>Personal information:</legend> -->
                <strong>First name:</strong><br>
                <input type="text" name="first_name"><br>
                <br>
                <strong>Last name:</strong><br>
                <input type="text" name="las_tname"><br>
            <br>
        <!-- </fieldset> -->

        <strong>Gender:</strong><br>
                <input type="radio" name="Gender" value="male" checked/>Male <br>
                <input type="radio" name="Gender" value="female" />Female<br>
                <input type="radio" name="Gender" value="other" />Other<br>
            <br>


        <strong>DOB:</strong> <input type="date"> <br>
        <br>

        <strong>Level of Education:</strong> <input type="text" name="Tel no." placeholder="eg. Doctor, Teacher etc."><br>
        <br>
 

        <strong>Marital Status:</strong> <select name="Marital_Status">
                        <option value="Married">Married</option>
                        <option value="Single">Single</option>
                        <option value="Divorce">Divorce</option>
                        <option value="Seperated">Seperated</option>

                    </select><br>
                <br>


        <strong>E-mail:</strong> <input type="text" name="E-mail" placeholder="eg.lotsunewland@gmail.com"><br>
        <br>

        <strong>Tel:</strong> <input type="text" name="Tel" placeholder="eg. +(233) 5438-60-382"><br>
        <br>
 

        <strong>Nationality:</strong> <select name="dropdown">
                        <option value="Ghana">Ghana</option>
                        <option value="Nigeria">Nigeria</option>
                        <option value="Togo">Togo</option>
                        <option value="Liberia">Liberia</option>
                        <option value="Benin">Benin</option>
                        <option value="Guinea">Guinea</option>
                        <option value="Baukina Faso">Baukina Faso</option>
                        <option value="Mali">Mali</option>

                    </select><br>
                <br>

        <strong>Hobby:</strong><br>
             Swimming <input type="checkbox" name="Hobby" value="Swimming" />
            Reading <input type="checkbox" name="Hobby" value="Reading" />
            Singing <input type="checkbox" name="Hobby" value="Singing" />
            Cooking <input type="checkbox" name="Hobby" value="Cooking" /><br>
            Surfing <input type="checkbox" name="Hobby" value="Surfing" />
            Hiking <input type="checkbox" name="Hobby" value="Hiking" />
            Drawing <input type="checkbox" name="Hobby" value="Drawing" />
            Dancing <input type="checkbox" name="Hobby" value="Dancing" /><br>
        <br>
        
        Address: <input type="text" name="Address"/><br>
        <br>

        <strong>Admission Type:</strong>
                Regular <input type="radio" name="Gender" value="Regular" />
                Evening <input type="radio" name="Gender" value="Evening" />
                Weekend <input type="radio" name="Gender" value="Weekend" /><br>
            <br>

        <textarea name="message" rows="10" cols="50" placeholder="tell us something about yourself..."></textarea><br>
          <br>

           <input type="submit">

    </form>

</body>

</html>
