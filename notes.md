$ xmllint --recover --xpath "/html//body//h2[@class='package-title']/a/text()" prometheus 2>/dev/null
prometheus
$ xmllint --recover --xpath "/html//body//h2[@class='package-title']/a/text()" pot 2>/dev/null
pot
$ xmllint --recover --xpath "/html//body//span[@class='version']/text()" tmp/pot 2>/dev/null
1.0.0
for lib in $(cat non-otp.txt); do wget -P tmp $lib; done
