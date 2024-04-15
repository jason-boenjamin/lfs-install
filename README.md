# lfs-install
# Commands needed to upload large files

1. Open Git Bash and `cd` to where you want to clone your repository
2. Run the command `git clone "repository url here"`
3. `cd` into the repository and located where you want to upload the file.
4. Once you are in that directory from the terminal, run the command `git lfs track "*.mp4"` (Replace *.mp4 with any other files you need)
5. Then run `git add .gitattributes`
6. Then run `git add teamintro.mp4` (Replace teamintro.mp4 with any other file you need)
7.  Then run `git commit -m "Add comments here"`
8.  The run `git push origin main`
9.  Check your GitHub Repo to see if you pushed the file.

Hope this works for you!
