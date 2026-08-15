---
layout: null
permalink: /
---
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <script>
    // 偵測瀏覽器語言，自動分流
    var userLang = navigator.language || navigator.userLanguage; 
    if (userLang.toLowerString().indexOf('ja') !== -1) {
      window.location.href = "{{ site.baseurl }}/ja/";
    } else {
      window.location.href = "{{ site.baseurl }}/zh/";
    }
  </script>
</head>
<body>
  <p>Redirecting / 正在重新導向...</p>
</body>
</html>
