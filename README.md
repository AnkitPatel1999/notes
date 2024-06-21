# notes
apt-get update 
1. to connect ec2 instance
  ssh -i file.pem ubuntu@public ip
2. check nginx version
     nginx -t
3. to install nginx
    apt-get install nginx (Manual Confirmation)
    apt-get install nginx -y (Automatic Confirmation)
   apt-get install <package_name>: This command is used to install a new package.

4. to check nginx service is enable/disable
   service nginx status

5. to see localhost
    curl localhost

6. to see curl locahost output file
     var/www/html
     ls

7. to change file content
   echo "hello world"> index.html
   above command can write hello world in index.html file

8. to check nginx is working or not or more info
     curl -i 13.60.78.141

9. ls command
    - ls - five list of files and folder
    - ls -ltr (list time reverse)
    - ls -l
    - ls -t
    - ls -r

10. less filename.txt   
  The less command in Unix and Linux systems is a powerful tool used for viewing the contents of a file without loading the entire file into memory. It's   particularly useful for inspecting large files or viewing files quickly in a paginated manner.
  **command**
    less filename.txt
    less -N filename.txt (n=line number)

11. Search for a Pattern
    grep "search_pattern" somefile.txt
13. Search for a Pattern and View the Result:
    grep "search_pattern" somefile.txt | less





-----------------------------------------------------
etc/nginx/nginx.conf
/usr/share/nginx/html

error log => /var/log/nginx/error.log

Start Nginx: sudo systemctl start nginx
Enable Nginx to start on boot : sudo systemctl enable nginx
Check Nginx Status : sudo systemctl status nginx
test nginx file : nginx -t



































https://www.bikenbiker.com/collections/on-sale
   
