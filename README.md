# Fernando Duarte — site completo

Site estático em HTML, CSS e JavaScript. Não exige Node, npm, banco de dados ou compilação.

## Arquivos
- index.html: página, estilos e interações.
- assets/: imagens e fontes locais.
- vercel.json: configuração de publicação.
- .gitignore: arquivos locais que não devem entrar no Git.

## Abrir no computador
Extraia o ZIP inteiro e abra index.html. Mantenha assets ao lado dele.

## GitHub e Vercel
1. Extraia o ZIP no Windows.
2. Crie um repositório no GitHub e envie o conteúdo extraído. index.html deve ficar na raiz, junto com assets e vercel.json.
3. Na Vercel, importe esse repositório.
4. Framework Preset: Other. Root Directory: raiz do repositório. Deixe Build Command e Install Command vazios e use a raiz como Output Directory (ou mantenha a detecção automática para site estático).
5. Publique e confira o domínio resultante.

## Pendências conhecidas
- Instagram: falta o endereço oficial. No início do script de index.html, substitua instagram:null por instagram:'https://www.instagram.com/PERFIL_CORRETO/'. Todos os botões passam a usar esse endereço. Até lá, abrem uma mensagem explicando a pendência; não levam a um perfil.
- WhatsApp: foi usado 5549999947574, correspondente a (49) 99994-7574 no anúncio. Confirme esse número, pois o primeiro número enviado tinha um dígito a menos.
- Confirme situação atual do CRECI/SC, horários, autorização das imagens, disponibilidade e encargos do imóvel antes da divulgação pública.
- Revise o aviso de privacidade conforme a hospedagem final. Não foram adicionados analytics, pixels ou cookies publicitários.
- Após definir o domínio, troque og:image por sua URL absoluta seguida de /assets/escritorio.jpg para compatibilidade de compartilhamento.

## Verificação realizada
Referências locais, IDs únicos, âncoras internas, integridade do ZIP e sintaxe JavaScript conferidos. Todos os arquivos usados estão incluídos. Sem teste visual automatizado em navegador ou aparelhos nesta entrega; não representa garantia de funcionamento em todos os navegadores.

## Recursos
Introdução com logo, cabeçalho e navegação lateral, movimento associado à rolagem nativa, menu mobile, galeria ampliada com controles e gesto lateral, acordeões, WhatsApp com mensagens contextuais, endereço/rota e privacidade. Respeita preferência de movimento reduzido.
