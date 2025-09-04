Caso existe algum inconvienio acabe afetando as pastas e/ou configurações base, é preciso haver maneiras de trazer todos os arquivos de volta. Pode parecer bobo mas salva vidas, o filme toy story 2 não tinha e certo dia um estagiario acabou deletando mais da metade do filme pronto, por sorte uma funcionaria tinha salvo para fazer em casa e conseguiram recuperar. Agora imagine isso acontecendo com dezenas de linhas de código do seu programa, por isso precisamos de planos para recuperar versões anteriores, fora diversos outras razões que se tornam importante

**Ambiente de Teste:**
  Realizaremos os testes de recuperação utilizando da ferramenta online chamada "git-hub"

**✓ Etapas de Backup:**
    O git-hub possui um sequência de códigos que você deve aplicar no git ou terminal para fazer o salvamento, geralmente deixamos o arquivos em alguma pasta
Os comandos são :

 --git init        //  (inicializa)
 
 --git add .           //adiciona as informações 
 
 --git commit -m "plano-de-recuperação.mb" // (salva os dados)  
 PS: dentro das aspas você insere o nome que deseja
 
 --git remote add origin (Agora insere o link da página do github, meu caso seria  git remote add origin https://github.com/fleiper/pra-teste.git)
 
 --git push
 Depois copie e cole  ""git push --set-upstream origin master"" e envie novamente, assim você terá terminado o backup.

Existe a opção git branch para atualizações

**✓ Simulação de Falha:**
Durante o Desenvolvimento do projeto "Palmer", o rudrian iria cuidar da página de cadastro, fazendo alterações próprias corrigindo um erro de código do caio, infelizmente o julio derrubou o computador no chão dando perda total, felizmente a nicolle tinha acabado de fazer o salvamento do código antes da perda do notebook.

**✓ Procedimento de Recuperação:**
Existem diversas formas de importar os dados do back-up e a mais simples é abrir o git ou terminal e inserir
git clone "+ link da página do github"

**✓ Critérios de Aceitação:**
Se tudo ocorrer nos conformes, no direito que você colocou irá ver seus arquivos em suas versões de quando foram salvos
