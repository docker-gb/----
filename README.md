<div>nat64前辍：<div>
<div>[2602:fc59:b0:64::] <div>
<div>[2a02:898:146:64::] <div>
<div>[2602:fc59:1:64::]1<div>
<div>ProxyIP：<div>
<div>proxyIP: bpb.yousef.isegaro.com<div>
<div>https://www.nslookup.io/domains/bpb.yousef.isegaro.com/dns-records/<div>

🧩 查看当前网卡信息
powershell
Get-NetAdapter | Select Name, MacAddress
这条命令可以列出所有网卡的名称和当前 MAC 地址。你需要确认你要修改的网卡名称，比如 "以太网" 或 "Wi-Fi"。

🧩 修改 MAC 地址（临时）
powershell
Set-NetAdapter -Name "以太网" -MacAddress "D8B1C2D1E4A5"
"以太网" 是网卡名称，请根据实际替换；

"A0B1C2D3E4F5" 是你要设置的新 MAC 地址，必须是 12 位十六进制数，不带冒号或横线；

第二位建议为偶数（如 0、2、4、6、8、A、C、E），以避免冲突。

✅ 修改后可以再次运行 Get-NetAdapter 来验证是否生效。
















