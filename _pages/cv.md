---
layout: cv
permalink: /cv/
title: CV
nav: true
nav_order: 5
cv_pdf: /assets/pdf/example_pdf.pdf # you can also use external links here
cv_format: rendercv # options: rendercv, jsonresume
toc:
  sidebar: left
---

<script>
  var my_password = "xsceric"; // 在这里修改你想要的密码
  var user_input = prompt("🎓 个人简历页面受密码保护，请输入访问密码：");
  
  if (user_input !== my_password) {
    document.write("<div style='text-align:center; margin-top:100px; font-family: Arial, sans-serif;'><h2>🔒 密码错误，无权访问此页面。</h2><p>请刷新页面重试，或 <a href='/'>返回主页</a>。</p></div>");
    window.stop(); 
  }
</script>
