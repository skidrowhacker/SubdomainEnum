Yasser | Skidrow  Twitter: @firfox20 
# Manual - > SubdomainEnum 
# First use this command to get target index page    wget "https://www.yahoo.com"
# 2nd use this command to grep 'Subs A-Z & 0-0 ' save it to .txt file /    cat index.html | grep -i -o "[a-z0-9]*.yahoo.com" > sub_yahoo.txt
# 3d use this command to get live hosts with status code '200' and save it to .txt file  cat sub_yahoo.txt| httpx -mc 200 > live.txt    
# 4th Ejoy 
