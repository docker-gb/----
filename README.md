<div>nat64前辍：<div>
<div>[2602:fc59:b0:64::] <div>
<div>[2a02:898:146:64::] <div>
<div>[2602:fc59:1:64::]<div>
<div>ProxyIP：<div>
<div>bpb.yousef.isegaro.com<div>
<div>https://www.nslookup.io/domains/bpb.yousef.isegaro.com/dns-records/<div>

<div>🧩 查看当前网卡信息<div>
<div>powershell<div>
<div>Get-NetAdapter | Select Name, MacAddress<div>
<div>这条命令可以列出所有网卡的名称和当前 MAC 地址。你需要确认你要修改的网卡名称，比如 "以太网" 或 "Wi-Fi"。<div>

<div>🧩 修改 MAC 地址（临时）<div>
<div>powershell<div>
<div>Set-NetAdapter -Name "以太网" -MacAddress "1AB1C2D1E4A5"<div>
<div>"以太网" 是网卡名称，请根据实际替换；<div>

<div>"A0B1C2D3E4F5" 是你要设置的新 MAC 地址，必须是 12 位十六进制数，不带冒号或横线；<div>

<div>第二位建议为偶数（如 0、2、4、6、8、A、C、E），以避免冲突。<div>

<div>✅ 修改后可以再次运行 Get-NetAdapter 来验证是否生效。<div>


<div>国内加速域名列表：<div>
<div>https://raw.githubusercontent.com/felixonmars/dnsmasq-china-list/master/accelerated-domains.china.conf<div>
<div>https://raw.githubusercontent.com/felixonmars/dnsmasq-china-list/master/bogus-nxdomain.china.conf<div>

<div>fifo.info<div>
<div>https://www.51tracking.com/country_two_code.php<div>
<div>asn!="13335"&&country="JP"&&server=="cloudflare"<div>
<div>asn="16509" && port="443" && cert.subject.org="Amazon"<div>
<div>asn="31898"<div>









