HOW CAN I IMPORT AN EXISTING FOLDER INTO MY REPOSITORY?

1. If not already done, create your repository on git.epfl.ch

2. Go to your project folder :
   cd /path/to/my/project

3. Add your project files to the repository :
   git init git add .
   git commit -m "Initial import"

4. Launch the following command, replace <username> with your GASPAR username and <repository> with your repository name :

git remote add origin https://<username>@git.epfl.ch/repo/<repository>.git

5. Push the files on the remote server

git push -u origin master

After this initial import, pushing your changes will just require this command :

git push
