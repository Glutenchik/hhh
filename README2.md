root@vanisimo056:~# mkdir pokta
root@vanisimo056:~# cd pokta
root@vanisimo056:~/pokta# git init
root@vanisimo056:~/pokta# echo "# hhh" >> README2.md
root@vanisimo056:~/pokta# ls
README2.md
root@vanisimo056:~/pokta# git remote add origin https://github.com/Glutenchik/hhh.git
root@vanisimo056:~/pokta# git branch -M main
root@vanisimo056:~/pokta# git branch
root@vanisimo056:~/pokta# cp /etc/nginx/sites-available/жуков.conf ~/pokta/
root@vanisimo056:~/pokta# ls
README2.md  жуков.conf
root@vanisimo056:~/pokta# https://github.com/Glutenchik/hhh.git
-bash: https://github.com/Glutenchik/hhh.git: No such file or directory
root@vanisimo056:~/pokta# git remote add origin https://github.com/Glutenchik/hhh.git
error: remote origin already exists.
root@vanisimo056:~/pokta# nano REARME2.md
root@vanisimo056:~/pokta# git add README2.md жуков.conf
root@vanisimo056:~/pokta# git commit -m "Перенос конфигурации на GitHub"
[main (root-commit) d09c434] Перенос конфигурации на GitHub
 2 files changed, 39 insertions(+)
 create mode 100644 README2.md
 create mode 100644 "\320\266\321\203\320\272\320\276\320\262.conf"
root@vanisimo056:~/pokta# git push -u origin main
Username for 'https://github.com': Glutenchik
Password for 'https://Glutenchik%20@github.com':

