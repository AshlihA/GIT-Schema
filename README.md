# GIT-Schema
bashCopy code
git checkout develop 
12.	git merge <branch>: Menggabungkan branch tertentu ke branch saat ini.
bashCopy code
git merge feature-branch 
13.	git reset <file>: Menghapus file dari staging area (tetap di working directory).
bashCopy code
git reset index.html 
14.	git stash: Menyimpan perubahan sementara untuk digunakan nanti.
bashCopy code
git stash 
15.	git remote add <name> <url>: Menambahkan remote repository dengan nama tertentu.
bashCopy code
git remote add origin https://github.com/user/repository.git 
16.	git fetch: Mengambil perubahan dari repository remote namun tidak menggabungkannya ke dalam branch lokal.
bashCopy code
git fetch origin 
17.	git rebase <branch>: Mengubah urutan commit di branch saat ini berdasarkan branch lain.
bashCopy code
git rebase main 
18.	git diff: Menampilkan perbedaan antara working directory, staging area, dan repository.
bashCopy code
git diff 
19.	git tag <tagname>: Menandai commit tertentu dengan tag tertentu.
bashCopy code
git tag v1.0 
20.	git config --global user.name "<name>": Mengatur nama pengguna global untuk Git.
bashCopy code
git config --global user.name "John Doe" 
21.	git help: Menampilkan bantuan untuk perintah Git tertentu.
bashCopy code
git help commit
