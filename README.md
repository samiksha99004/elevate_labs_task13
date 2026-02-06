# elevate_labs_task13
<br>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Task 13 - Secure API Testing</title>
</head>
<body>

    <h1>Task 13: Secure API Testing & Authorization Validation</h1>

    <p>
        This task focuses on understanding and testing REST API security by validating authentication,
        authorization, input handling, and rate limiting mechanisms.
    </p>

    <p>
        The APIs were tested using Postman by sending different HTTP requests such as GET and POST.
        Authentication was verified by sending requests with valid and invalid credentials and observing
        the responses returned by the server.
    </p>

    <p>
        Authorization testing was performed by removing authentication headers and modifying resource
        identifiers to check whether unauthorized users could access restricted data.
        Input validation was tested by sending malformed and unexpected values in the request body.
    </p>

    <p>
        Rate limiting was checked by sending multiple rapid requests to the API to observe whether the
        server restricted excessive traffic. HTTP response codes and error messages were analyzed to
        identify potential security weaknesses.
    </p>

    <p>
        The identified issues were mapped to OWASP API Security Top 10 risks such as Broken Object Level
        Authorization, Broken Authentication, and Lack of Rate Limiting.
    </p>

    <p>
        This task helped in gaining hands-on experience in API security testing and understanding common
        security misconfigurations present in real-world APIs.
    </p>

    <p>
        <strong>Tools Used:</strong> Postman (Primary), cURL (Alternative)
    </p>

</body>
</html>
