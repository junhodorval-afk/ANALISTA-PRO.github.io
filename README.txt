ANALISTA FF — VERSÃO INSTALÁVEL (PWA)

COMO PUBLICAR NO MESMO GITHUB
1. Extraia este ZIP.
2. No mesmo repositório do GitHub, envie/substitua os arquivos mantendo todos na mesma pasta: index.html, manifest.webmanifest, service-worker.js e icon.svg.
3. Faça commit/salve as alterações e aguarde o GitHub Pages publicar. Não crie outro repositório nem outro site.
4. Abra o link HTTPS do seu site no Google Chrome do Android.
5. Toque nos três pontinhos (⋮) e escolha “Instalar app” ou “Adicionar à tela inicial”. O nome ANALISTA FF ficará como ícone e abrirá em tela própria, sem precisar da Play Store.

IMPORTANTE SOBRE O ACESSO COMPARTILHADO
Esta versão prepara a instalação como aplicativo (PWA) e cache básico. Ela NÃO transforma o armazenamento local existente em banco compartilhado. No código atual, os dados ficam principalmente no navegador de cada aparelho; portanto, usuários diferentes não terão automaticamente os mesmos dados e o administrador não verá os logins de todos. Para isso é necessário conectar autenticação e banco de dados compartilhado, por exemplo Firebase Authentication + Firestore, e configurar regras seguras. Não coloque senhas de administrador no HTML público.

Não é um APK Android nativo; é um aplicativo web instalável pelo navegador, sem Play Store.
