# Comandos Git

>Cria repositório remoto
```
git remote add origin servidorRemoto
</br>

>Copia todo repositório
```
git clone https://github.com/riuzoc/sistema-de-cadastro.git

git clone <repositorio> <meu-projeto-clone>  ->pasta específica
git clone -branch new_feature <repositorio>   ->branch específico
```
</br>

>Puxar tudo do repositório e atualizar.
```
git pull
```
</br>

>Mostra o status dos arquivos.
```
git status
```
</br>

>Adicionar arquivos para commitar.
```
git add ComandosGit.md 

git add .     ->todos arquivos da pasta
```
</br>

>Commit das alterações.
```
git commit index.html -m "linkando o app js com o html"

git commit . -m "".   ->diretório atual
```
</br>

>Enviar todos commits para o respositório.
```
git push origin main
git push
```
</br>

>Ver logs(histórico) dos commits.
```
git log
git log --oneline   ->Menos Info
git log -p   ->Mais Info
git log --author="user_name"

```
</br>

>Voltar para um commit do histórico.
```
git restore --source a0c893b
```
</br>

>Criar branch desenvolvimento e alternar entre branchs.
```
git checktou -b desenvolvimento   ->cria nova branch e já faz o switch.
git switch main   ->volta para branch.
git switch desenvolvimento
  git add contato.html
  git commit -m "adicionado e-mail de contato" contato.html
  git push origin desenvolvimento
```
</br>

>Merge desenvolvimento com main
```
git switch main
git merge desenvolvimento
git push origin main
```
</br>

>.
```
git
```
</br>

>.
```
git
```
</br>

>.Carregar vsCode no Browser
```
Pressionar . e esperar carregar(dentro do github)
```
</br>
