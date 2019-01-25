1. create a venv.

python3 -m venv ~/.virtualenvs/djangodev

2. start the created v. env. 

source ~/.virtualenvs/djangodev/bin/activate

3. Save a sample report file in: "/root/depot/report.txt"

4. Uncompress the project: hayder.tar

tar -xvf hayder.tar

5. cd hayder

6. python3 manage.py runserver 0:8000

7. visit the webpage http://your_iP:8000/threadReport/
exe: http://192.168.1.200:8000/threatReport/

8. if you got an error of ALLOWED_HOST, go to hayder/settings.py, add your IP to the list in ALLOWED_HOSTS

9. run the server again.

10 At real time, you can change the contents of the sample file: /root/depot/report.txt
