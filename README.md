# Perseus-Githubactions
A collection of files to compile Perseus (Rust webframework) through Github Actions

# Foreword

This repository is meant to be a collection of YAML files to compile Perseus to different architectures.

I am by no means a Github actions wizzard, so please feel free to make PR's if you have better better configurations.

Also, *compiling perseus is not lightweight*, it will go through your Github Actions credits rather quickly. Especially the storage one.
So be aware!:)


# Tailwindcss

I have not yet succeeded in compiling Tailwindcss with Perseus through Github actions.
The current solutions to this is to disable the Tailwindcss plugin, compile the css beforehand, upload it in the static folder, and refer to it as stylesheet by 
using `.perseus/static/tailwind.css`


