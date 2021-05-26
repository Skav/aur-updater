
#!/usr/bin/bash
aur_directory="/path/to/directory/*"
i=1

for dir in ${aur_directory}
do
        echo "You are now in ${dir}"
        cd ${dir} && git remote update >> /dev/null

        if git status -uno | grep "up to date" >> /dev/null; then
                echo "Your repository is up to date"
        else
                echo "Updating and installing newest avaliable version..."
                git pull && makepkg -sri
        fi
        printf "\n\n\n\n\n\n"
done
