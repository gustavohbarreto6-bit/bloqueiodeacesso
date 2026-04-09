🔐 Sistema de Bloqueio de Acesso

Este projeto é uma aplicação simples em HTML, CSS e JavaScript que simula um sistema de login com controle de tentativas. Após um número limitado de erros, o sistema bloqueia o acesso.

📌 Funcionalidades
✔️ Validação de login e senha
✔️ Mensagem exibida diretamente na tela (sem alert)
✔️ Controle de tentativas (máximo de 3)
✔️ Bloqueio automático após exceder tentativas
✔️ Feedback visual com cores diferentes:
Verde → acesso liberado
Laranja → erro com tentativas restantes
Vermelho → sistema bloqueado
👤 Usuários cadastrados
Login	Senha
admin	1234
gustavo	1111
mari	2222
🛠️ Tecnologias utilizadas
HTML5
CSS3
JavaScript (Vanilla)
▶️ Como executar
Copie o código do projeto

Salve em um arquivo com nome:

index.html
Abra o arquivo no navegador
🔄 Lógica do sistema
O usuário insere login e senha
O sistema verifica se existe um usuário válido na lista
Caso esteja correto:
Exibe "Acesso Liberado"
Caso esteja incorreto:
Diminui o número de tentativas
Após 3 erros:
O botão é desativado
Exibe "Sistema Bloqueado"
⚠️ Observações
Este projeto é apenas para fins educacionais
Não é seguro para uso real (não utiliza banco de dados nem criptografia)
As senhas estão expostas no código
💡 Melhorias futuras
🔐 Criptografia de senha
🗄️ Integração com banco de dados
🔄 Reset automático após tempo
👁️ Mostrar/ocultar senha
🎨 Melhorar design (UI/UX)
📄 Licença

Este projeto é livre para uso e estudo.

💻 Desenvolvido para prática de lógica com JavaScript
