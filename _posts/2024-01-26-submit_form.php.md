

if ($_SERVER["REQUEST_METHOD"] == "POST") {
    // Retrieve form data
    $username = $_POST['username'];
    $password = $_POST['password'];
    $age = $_POST['age'];

    // Here, you can perform validation on username, password, age, etc.

    // Example: Storing username and password in a text file
    $file = 'user_credentials.txt';
    // Append the username and password to the file
    file_put_contents($file, "Username: $username, Password: $password, Age: $age\n", FILE_APPEND);

    // Redirect user to a success page or do something else
    header("Location: success.html");
    exit();
}
?>

