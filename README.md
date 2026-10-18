Atue como um especialista em N8N.

Crie uma automação no N8N para registrar diagnóstico de clientes recebidos por formulário

Público:
Equipe comercial.

Ferramentas envolvidas:
Google Forms, Google Sheets e Gmail.

Fluxo:
Receber uma resposta, salvar os dados na planilha e enviar um e-mail de confirmação.

Regras:
Ignorar registros sem e-mail válido.

Google Forms
Cliente preenche o diagnóstico 
1. Trigger — Google Sheets Trigger
Deteta uma nova resposta na folha ligada ao formulário
2. Edit Fields (Set)
Organiza os campos e normaliza o email
3. IF — Validar email
Verifica se o email existe e tem um formato válido
4. Google Sheets — Append Row
Regista o diagnóstico na base comercial
5. Gmail — Send a Message
Envia confirmação ao cliente
