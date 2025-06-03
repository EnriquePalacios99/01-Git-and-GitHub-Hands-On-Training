# 01-Git-and-GitHub-Hands-On-Training


Si deseas crear tus carpetas para practicar de la misma forma, puedes crearlas con estas lineas de código 

```
#!/bin/bash

echo "Creando subcarpetas dentro de la carpeta actual: $(pwd)"

# 01-Git-Fundamentals
mkdir -p "01-Git-Fundamentals"
cd "01-Git-Fundamentals"
mkdir "01-Installation-and-Configuration"
mkdir "02-Basic-Commands"
mkdir "03-Understanding-Commits"
mkdir "04-Branches-and-Merges"
mkdir "05-Resolving-Merge-Conflicts"
cd ..

# 02-GitHub-Collaboration
mkdir -p "02-GitHub-Collaboration"
cd "02-GitHub-Collaboration"
mkdir "01-GitHub-Basics"
mkdir "02-Forking-and-Pull-Requests"
mkdir "03-Code-Reviews"
mkdir "04-Issues-and-Project-Management"
mkdir "05-GitHub-Pages"
cd ..

# 03-Advanced-Git-Techniques
mkdir -p "03-Advanced-Git-Techniques"
cd "03-Advanced-Git-Techniques"
mkdir "01-Rebasing"
mkdir "02-Stashing"
mkdir "03-Cherry-Picking"
mkdir "04-Reverting-and-Resetting"
mkdir "05-Git-Tags"
cd ..

# 04-Git-in-Full-Stack-Workflows
mkdir -p "04-Git-in-Full-Stack-Workflows"
cd "04-Git-in-Full-Stack-Workflows"
mkdir "01-Frontend-Workflow"
mkdir "02-Backend-Workflow"
mkdir "03-Monorepos-vs-Polyrepos"
mkdir "04-Environment-Specific-Configurations"
mkdir "05-Dependency-Management-and-.gitignore"
cd ..

# 05-CI-CD-with-GitHub-Actions
mkdir -p "05-CI-CD-with-GitHub-Actions"
cd "05-CI-CD-with-GitHub-Actions"
mkdir "01-Introduction-to-CI-CD"
mkdir "02-GitHub-Actions-Basics"
mkdir "03-Automated-Testing"
mkdir "04-Automated-Deployments"
mkdir "05-Secrets-Management"
cd ..

echo "¡Estructura de subcarpetas creada con éxito!"
echo "Puedes verificarla con 'ls -R'."

```