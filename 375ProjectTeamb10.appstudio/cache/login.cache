
btnLogin.onclick=function(){
  let loginUsername = inptLoginUsername.value
  let loginPassword = inptLoginPassword.value
  query = "Select username, password FROM customer"
  req = Ajax("https://ormond.creighton.edu/courses/375/ajax-connection.php", "POST", "host=ormond.creighton.edu&user=" + netID + "&pass=" + pw + "&database=" + databaseSchema + "&query=" + query)
  results = JSON.parse(req.responseText)
  lblMessage.value = results
}
