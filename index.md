<!--  ----------------------------------------------------------------------  -->
<!--  NOTE: Please add the following <META> element to your page <HEAD>.      -->
<!--  If necessary, please modify the charset parameter to specify the        -->
<!--  character set of your HTML page.                                        -->
<!--  ----------------------------------------------------------------------  -->

<META HTTP-EQUIV="Content-type" CONTENT="text/html; charset=UTF-8">

<!--  ----------------------------------------------------------------------  -->
<!--  NOTE: Please add the following <FORM> element to your page.             -->
<!--  ----------------------------------------------------------------------  -->

<form action="https://test.salesforce.com/servlet/servlet.WebToLead?encoding=UTF-8" method="POST">

<input type=hidden name="oid" value="00D3R0000008hfP">
<input type=hidden name="retURL" value="https://www.lockheedmartin.com/en-us/index.html">

<!--  ----------------------------------------------------------------------  -->
<!--  NOTE: These fields are optional debugging elements. Please uncomment    -->
<!--  these lines if you wish to test in debug mode.                          -->
<!--  <input type="hidden" name="debug" value=1>                              -->
<!--  <input type="hidden" name="debugEmail"                                  -->
<!--  value="jdelucas@salesforce.com">                                        -->
<!--  ----------------------------------------------------------------------  -->

<label for="first_name">First Name</label><input  id="first_name" maxlength="40" name="first_name" size="20" type="text" /><br>

<label for="last_name">Last Name</label><input  id="last_name" maxlength="80" name="last_name" size="20" type="text" /><br>

<label for="email">Email</label><input  id="email" maxlength="80" name="email" size="20" type="text" /><br>

<label for="company">Company</label><input  id="company" maxlength="40" name="company" size="20" type="text" /><br>

<label for="state">State/Province</label><input  id="state" maxlength="20" name="state" size="20" type="text" /><br>

Initial Program Value:<input  id="00N3R000000uXgY" name="00N3R000000uXgY" size="20" type="text" /><br>

Business Area:<select  id="00N3R000000uXgd" name="00N3R000000uXgd" title="Business Area"><option value="">--None--</option><option value="Aero">Aero</option>
<option value="MFC">MFC</option>
<option value="RMS">RMS</option>
<option value="Space">Space</option>
<option value="None">None</option>
</select><br>
<input type="submit" name="submit">
</select><br>
<label for="lead_source"><input type="hidden" name="lead_source">Lead Source</label><select  id="lead_source" name="lead_source"><option value="Website">Website</option>
</form>
