# Psi — instaladores

Psi é um programa para psicólogas e psicólogos autônomos organizarem pacientes, agenda, prontuário e financeiro. Os dados ficam **somente no seu computador**, protegidos por senha. Nada é enviado pela internet.

## [⬇ Baixar a última versão](https://github.com/angelicadf97/psi-releases/releases/latest)

Funciona no Windows 10 e no Windows 11.

---

## Guia de instalação e primeiros passos

### 1. Baixar o instalador

1. Clique em **Baixar a última versão**, acima.
2. Na página que abrir, role até **Assets** e clique no arquivo que termina em **`x64-setup.exe`** (por exemplo, `psi-manager_0.1.4_x64-setup.exe`). Ignore os outros arquivos.
3. O navegador pode avisar que o arquivo "não é baixado com frequência" ou que "pode ser perigoso". Isso acontece com programas novos, que ainda não são conhecidos pelo Windows. Abra o menu (⋯) ao lado do download, escolha **Manter** e depois **Manter assim mesmo**.

### 2. Instalar

1. Abra o arquivo baixado (clique duas vezes).
2. O Windows deve mostrar uma tela azul: **"O Windows protegeu o computador"**. Isso é esperado: o Psi ainda não tem o certificado pago que remove esse aviso. Clique em **Mais informações** e depois em **Executar assim mesmo**.
3. Siga o instalador, que está em português. Ele instala só para o seu usuário e foi feito para **não pedir senha de administrador**.
4. Ao terminar, abra o Psi pelo menu Iniciar.

> **Apareceu "Could not find the WebView2 runtime" (não foi possível encontrar o WebView2)?**
> Isso é raro e acontece em alguns Windows 10 mais antigos. Baixe o componente gratuito da Microsoft em <https://go.microsoft.com/fwlink/p/?LinkId=2124703>, execute o arquivo baixado e abra o Psi de novo.

### 3. Primeiro acesso

Na primeira vez, o Psi guia você em etapas:

1. **Crie sua senha.** Digite duas vezes. Ela é a única forma de abrir seus dados. Escolha uma que você consiga lembrar.
2. **Anote a chave de recuperação.** O Psi mostra uma sequência de letras e números **uma única vez**. É ela que devolve o acesso se você esquecer a senha. Use **Copiar**, **Salvar em arquivo** ou **Imprimir** e guarde em um lugar seguro, **fora deste computador** (papel, pendrive ou gerenciador de senhas). Para continuar, o Psi pede que você digite um trecho da chave, para confirmar que você a guardou.
3. **Pronto.** Você já pode cadastrar o primeiro paciente.

> ⚠ Se você esquecer a senha **e** perder a chave de recuperação, ninguém consegue abrir os dados: nem você, nem quem desenvolveu o Psi. Isso é o que protege as informações dos seus pacientes.

### 4. Onde ficam seus dados e cópias de segurança

- Os dados ficam na pasta `%APPDATA%\com.angel.psi-manager`. Para abrir, aperte as teclas **Windows + R**, cole esse endereço (com os `%`) e pressione Enter.
- O Psi faz uma **cópia de segurança automática por dia**, na subpasta `backups`, e mantém as 7 mais recentes.
- Em **Configurações → Backup** você pode escolher também uma **pasta externa** (por exemplo, um pendrive). O Psi copia o backup do dia para lá.
- Atualizar, reinstalar ou desinstalar o Psi **não apaga seus dados**.

### 5. Bloqueio automático

Se você ficar 15 minutos sem usar o Psi, ele volta para a tela de senha. Para bloquear na hora, use o botão **Bloquear**. Em **Configurações → Segurança** você muda esse tempo.

### 6. Como atualizar

- Quando existe uma versão nova, o Psi mostra um aviso ao abrir, com as novidades. Clique em **Atualizar agora**.
- Antes de instalar, o Psi faz uma cópia de segurança dos seus dados. Se ela falhar, a atualização é cancelada e nada muda.
- O Psi reinicia sozinho ao terminar. Para escolher a hora, clique em **Depois**.
- Para procurar atualizações a qualquer momento: **Configurações → Informações do Sistema → Verificar atualizações**.

### 7. Algo deu errado?

1. No Psi, vá em **Configurações → Informações do Sistema → Exportar log de erros**.
2. Salve o arquivo e envie junto com a descrição do que aconteceu. Ele **não contém dados de pacientes** (nomes, CPFs, telefones e textos são removidos), só a lista de erros dos últimos 30 dias e as versões do programa e do Windows.
3. Para relatar, abra um aviso em <https://github.com/angelicadf97/psi-releases/issues> ou fale diretamente com quem passou o Psi para você.

---

## Perguntas rápidas

**É seguro, já que o Windows avisa?** O aviso aparece porque o Psi ainda não paga o certificado comercial que a Microsoft exige para reconhecer programas novos. Ele não significa que o arquivo tem problema. Baixe sempre apenas desta página.

**Preciso de internet?** Só para baixar e para receber atualizações. No dia a dia o Psi funciona sem internet.

**Posso usar em mais de um computador?** Ainda não: os dados ficam em um único computador. Para trocar de computador, copie uma cópia de segurança (a pasta `backups` ou a pasta externa) e restaure com a mesma senha.
