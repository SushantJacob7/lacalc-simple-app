# lacalc-simple-app
A very simple app. But good to get your feet wet if it is the first react native app you ever played with.

The app uses expo as framework to run react native.<br>
Here are the steps:<br>
1, install docker on your computer<br>
2, git clone from this repo<br>
3, run ./dev_container.sh<br>
4, cd larn2/ <br>
5, expo start<br>
<You have app being served from your computer>
--------------------
  In case of errors
1. install docker on your computer
2. git clone  https://github.com/codervijo/lacalc-simple-app 
3. incase you runinto error when trying ./dev_containe.sh
  mkdir B2B
4. Update Dockerfile to the latest version of npm (14.13.1 as of 10/11/20)
  incase you encounter an error when trying expo start
5. Make sure you are inside Larn2 
6. expo init <name>
7. cd <name>
7. expo start
8. Ctrl+C
9. find ip: ifconfig |grep inet
10. export REACT_NATIVE_PACKAGER_HOSTNAME=<YOUR_IP_HERE>
11. expo start
11. cd ..
12. cd lacalc-app
13. npm install
14. npm install react-scripts@3.0.1 -g —silent
15. expo start


