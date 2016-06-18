#Curso de Git e Github

##Primeiros Passos 
'''
#configurar o autor dos commits
git config --global user.name "Camille Nogueira"
git config --global user.email "camillenogueira@gmail.com"

#inicializar um repositório
git init

# Verificar Status do repositório
git status

#adicionar arquivo para próximo commit
git add README.md

# Comitar colocando uma mensagem
git commit -m "Nosso primeiro comentário"

#Visualizar Log
git log
git log --full-diff -p README.md
'''

##TRABALHANDO COM BRANCHS
'''
#Cria um Branch a partir do hash do comite
git checkout <commit>

#Cria um Branch
git checkout -b develop

'''