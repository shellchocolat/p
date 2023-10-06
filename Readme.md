msfvenom -p windows/x64/messagebox -a x64 --platform windows -f raw TEXT="Don't execute everything you find on github" TITLE="shellchocolat" EXITFUNC=thread -o p.hex
