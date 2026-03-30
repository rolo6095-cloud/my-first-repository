root@896cf839cf9a:/# cd {my-first-repository}/
root@896cf839cf9a:/{my-first-repository}#
root@896cf839cf9a:/{my-first-repository}# mkdir my-first-project
root@896cf839cf9a:/{my-first-repository}# echo 'My first readme' > my-first-project/README.md                                                                 
root@896cf839cf9a:/{my-first-repository}# cat my-first-project/README.md                                                                                      
My first readme   
root@896cf839cf9a:/{my-first-repository}# git add .
root@896cf839cf9a:/{my-first-repository}# git commit -m 'My first commit'
[master (root-commit) 98eef93] My first commit
 1 file changed, 1 insertion(+)
 create mode 100644 my-first-project/README.md
root@896cf839cf9a:/{my-first-repository}# git push                                                                                           
Enumerating objects: 3, done.                                                                                                         
Counting objects: 100% (3/3), done.                                                                                                   
Writing objects: 100% (3/3), 212 bytes | 212.00 KiB/s, done.                                                                          
Total 3 (delta 0), reused 0 (delta 0)                                                                                                 
To https://github.com/{ROLO}/{my-first-repository}.git                                                                                       
 * [new branch]      main -> main 
