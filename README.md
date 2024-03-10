# Registration-Form
<!DOCTYPE html>
<html>
<style>
  table,
  th,
  td {
    border: 1px solid black;
  }
</style>

<body>


  <table>
    <tr>
      <th colspan="2">Registration Form</th>
    </tr>
    <tr>
      <td>Student Name</td>
      <td><input type="text" /></td>

    </tr>
    <tr>
      <td>Father's Name</td>
      <td><input type="text" /></td>

    </tr>
    <tr>
      <td>Mother's Name</td>
      <td><input type="text" /></td>
    </tr>
    <tr>
      <td>Date of Birth</td>
      <td>
        <form>
          <label for="birthday"></label>
          <input type="date" id="birthday" name="birthday">
        </form>
      </td>

    </tr>
    <tr>
      <td>Gender</td>
      <td><label>
          Male<input type="radio" name="gender" value="male">
        </label>
        <label>
          Female<input type="radio" name="gender" value="female">
        </label>
      </td>

    </tr>
    <tr>
      <td>Email ID</td>
      <td><input type="text" /></td>

    </tr>
    <tr>
      <td>Mobile No.</td>
      <td><input type="text" /></td>

    </tr>
    <tr>
      <td>Address</td>
      <form>
        <label for="Address"></label>
      </form>
      <td><input type="text" /></td>

    </tr>
    <tr>
      <td>State</td>
      <td><input type="text" /></td>

    </tr>
    <tr>
      <td>City</td>
      <td><input type="text" /></td>

    </tr>
    <tr>
      <td></td>
      <td><input type="submit">
      </td>

    </tr>
  </table>


</body>

</html>
