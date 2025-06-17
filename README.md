# BO Scripts

<b>Tổng hợp các script hỗ trợ cho game BO (Roblox).</b>  
Dễ sử dụng, nhẹ, tự động hóa các chức năng phổ biến như Auto Race, Auto Boss, v.v.

---

## 🚗 Auto Race
Tự động tham gia và hoàn thành cuộc đua trong game.

<pre>
<code id="code1">loadstring(game:HttpGet("https://raw.githubusercontent.com/goodick145/BO/main/AutoRace"))()</code>
<button onclick="copyToClipboard('code1')">📋 Sao chép</button>
</pre>

---

## 🌌 Auto Spec
Tự động farm chỉ số (Spec).

<pre>
<code id="code2">loadstring(game:HttpGet("https://raw.githubusercontent.com/goodick145/BO/main/AutoSpec"))()</code>
<button onclick="copyToClipboard('code2')">📋 Sao chép</button>
</pre>

---

## 🎮 Cuttay Hub
Hub tổng hợp các tiện ích gameplay.

<pre>
<code id="code3">loadstring(game:HttpGet("https://raw.githubusercontent.com/goodick145/BO/main/CutTsy"))()</code>
<button onclick="copyToClipboard('code3')">📋 Sao chép</button>
</pre>

---

## 🐉 Auto Boss
Tự động tìm và đánh boss trong game.

<pre>
<code id="code4">loadstring(game:HttpGet("https://raw.githubusercontent.com/goodick145/BO/main/AutoBoss"))()</code>
<button onclick="copyToClipboard('code4')">📋 Sao chép</button>
</pre>

---

## 🔐 Lưu ý

- Script dùng cho mục đích học tập & cá nhân.
- Nên dùng acc phụ để tránh bị xử phạt.
- Đảm bảo kiểm tra link script trước khi sử dụng.

---

<script>
function copyToClipboard(id) {
  const code = document.getElementById(id).textContent;
  navigator.clipboard.writeText(code).then(() => {
    alert("Đã sao chép!");
  });
}
</script>
