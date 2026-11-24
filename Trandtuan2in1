# TranDangTuan-locket-youtube
#!name=Locket Gold - Tran Dang 
#!desc=Module cấu hình Locket Widget - NightMarket Server
# 💬 FB: [https://www.facebook.com/share/1ND8TfskDe/?mibextid=wwXIfr](https://www.facebook.com/tran.dang.tuan1042006)
# 🚀 Rewrite by: Tran Dang Tuan

[General]
user-agent = Locket/1.0.0 (iPhone; iOS 26.3; Scale/3.00)

[Script]
# ~ Locket Gold - Shadowrocket / Surge / LanceX

# RevenueCat Response
revenuecat = type=http-response, pattern=^https:\/\/api\.revenuecat\.com\/.+\/(receipts$|subscribers\/[^/]+$), script-path=https://raw.githubusercontent.com/vbachtr25/TrBachLocket/refs/heads/main/Locket%20Gold/locketfix8.js, requires-body=true, max-size=-1, timeout=60

# RevenueCat Request Header
deleteHeader = type=http-request, pattern=^https:\/\/api\.revenuecat\.com\/.+\/(receipts|subscribers), script-path=https://raw.githubusercontent.com/vbachtr25/TrBachLocket/refs/heads/main/Locket%20Gold/header7.js, timeout=60

# Locket Firebase Remote Config
locket_rc = type=http-response, pattern=^https:\/\/firebaseremoteconfig\.googleapis\.com\/v1\/projects\/locket-4252a\/.+, script-path=https://raw.githubusercontent.com/vbachtr25/TrBachLocket/refs/heads/main/Locket%20Gold/forceGold4.3.js, requires-body=true, max-size=-1, timeout=60

# --- YouTube ---
# Lưu ý: Thay thế các tham số trong argument nếu ứng dụng của bạn không hỗ trợ variable mustache {{{ ... }}}
youtube.response = type=http-response,pattern=^https:\/\/youtubei\.googleapis\.com\/youtubei\/v1\/(browse|next|player|search|reel\/reel_watch_sequence|guide|account\/get_setting|get_watch),requires-body=1,max-size=-1,binary-body-mode=1,script-path=https://raw.githubusercontent.com/Maasea/sgmodule/master/Script/Youtube/youtube.response.js,argument="{"lyricLang":"zh-Hans","captionLang":"zh-Hans","blockUpload":true,"blockImmersive":true,"debug":false}"

[MITM]
hostname = %APPEND%, api.revenuecat.com, firebaseremoteconfig.googleapis.com
