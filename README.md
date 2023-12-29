<!DOCTYPE html>
<html>
    <body align="center">
        <table align="center" border="2">
            <form action="ad.php" method="POST">
                <th><h1>simple calculater</h1></th>

                <tr>
                    <td>number1:<input type="number" name="NUM1" placeholder="enter value"></td>
                </tr>

                <tr>
                    <td>number2:<input type="number" name="NUM2" placeholder="enter value"></td>
                </tr>

                <tr>
                    <td>opertator:
                    <select name="opr">
                        <option value="1">+</option>
                        <option value="2">-</option>
                        <option value="3">*</option>
                        <option value="4">/</option>
                    </select></td>
                 
                </tr>

                <tr>
                    <td><input type="submit" name="submit" value="calculate">
                    <input type="reset" name="reset" value="clear"></td>
                </tr>
            </form>
        </table>
    </body>
</html>
